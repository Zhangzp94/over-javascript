异步I/O  input/output
+ 文件操作
+ 网络操作

在浏览器中也存在异步操作：
+ 定时任务
+ 事件处理
+ ajax回调处理


js的运行是单线程的，
引入事件队列机制 

node.js中的事件模型与浏览器中的事件模型类似：单线程+事件队列；

node.js中异步执行的任务：
+ 文件I/O
+ 网络I/O

node.js 是基于回调函数的编码风格