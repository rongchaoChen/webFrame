#vue
<hr>
vue的两个核心
> 1. 响应数据的绑定
>>+ 当数据发生改变是,自动更新试图
>>+ 利用Object.defineProperty中的getter /setter代理数据
>
> 2.视图组件
> >+ ui页面映射组件树
> >+ 组件可重用,可维护 
<hr>
>虚拟DOM<br>
>1.提供一种方便的工具,是的开发效率得到保证 <br>
>2.保证最小化的DOM操作,是的执行效率得到保证 <br>

---
npm install -g @vue/cli <br>
npm install -g @vue/cli-service-global

-------
#### 快速创建项目

* 目录结构
```

		assets -- 当前项目的静态文件
		components --- 组件
			   模块       模块地址名称,如果是./ 是自定义模块
		import App from './App.vue'

```

	vue create 项目名称
	默认回车
	根据提示来
* 条件循环
	* v- if
