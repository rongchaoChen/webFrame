###1.1
---
####mvc:
>mvc 分为
>
>* model(模型)
>* controller(控制)
>* view (视图)  
>* ![](https://i.imgur.com/L74X6ev.jpg)
>>* 在mvc中一般都是通过controller 和model 来联系，contr 是model和view的协调者 ，view和model 是不直接联系的
>
####mvp:
>* 从mvc模式演变而来，他们的基本思想有相通的地方， controller 和 Presenter 负责逻辑的处理，model 提供数据，view 负责显示， 在mvp 中view 和model 进行了隔离，而且Presenter 与具体的view 是没有直接关联的，而是通过定义好的借口使得在变更view 的时候，保持presenter 不变
>* ![](https://i.imgur.com/tskU5Zj.jpg)

### mvvm
>* 相比前面两种模式，MVVM只是把MVC的Controller和MVP的Presenter改成了ViewModel。View的变化会自动更新到ViewModel，ViewModel的变化也会自动同步到View上显示。这种自动同步是因为ViewModel中的属性实现了Observer，当属性变更时都能触发对应的操作
>* ![](https://i.imgur.com/stYvRea.jpg)

---
#### 指令
----
v- bind 都是绑定的指令,配合元素使用<br>
v -on: 点击事件 , 可以简写v-on: 直接 @:click