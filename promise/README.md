#Deferred 和 promise

> * Deferred 提供了一个抽象的非阻塞的解决方案（如 Ajax 请求的响应），它创建一个 “promise” 对象，其目的是在未来某个时间点返回一个响应
* 抽象来说，deferreds 可以理解为表示需要长时间才能完成的耗时操作的一种方式，相比于阻塞式函数它们是异步的，而不是阻塞应用程序等待其完成然后返回结果。deferred对 象会立即返回，然后你可以把回调函数绑定到deferred对象上，它们会在异步处理完成后被调用。

###promise
> * Promise 对象用于延迟(deferred) 计算和异步(asynchronous ) 计算.。一个Promise对象代表着一个还未完成，但预期将来会完成的操作。
* promise是CommonJS的规范之一，作为一个模型，提供了一个在软件工程中描述延时（或将来）概念的解决方案。它背后的思想：不是执行一个方法然后阻塞应用程序等待结果返回，而是返回一个promise对象来满足未来值。
* Promise能够帮助我们控制代码的流程，避免函数的多层嵌套 [参考实例][1]





[1]: https://segmentfault.com/a/1190000000684654#articleHeader1
