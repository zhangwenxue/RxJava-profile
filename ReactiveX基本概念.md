# ReactiveX基本概念

在ReactiveX中observer（观察者）subscribes(订阅)到一个Observable（被观察者）上。然后observer就会对observable发送的事件或者事件序列做出回应。这种方式使得并发操作更容易实现，因为在等待Observable发送事件时并不会阻塞，与之相反，响应式编程用Observer的形式创建了一个哨兵，它会对未来Observable产生的事件做出反应。

本页面将解释什么是响应式编程以及什么是Observable和observers（包括observers如何注册到Observable上）其他页面将展示如何用多种Observable操作符来连接Observables并且改变他们的行为。

本文档用弹珠球表的方式来解释，下面就是弹珠图表代表了Observables以及Observables的变形：

![](http://reactivex.io/assets/operators/legend.png)





##### 更多

[Single ]()- 一个特殊的Observable只产生一个事件
