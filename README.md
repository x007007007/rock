# rock

rock是一门编译型，由基于栈的虚拟机运行的一门语言。

目前已经支持基本的赋值、流程控制（if、while）和调用java扩展函数，能够编写简单的逻辑。

接下来准备让其支持list & hashDict容器、自定义作用域，以及自定义函数。

rock是基于java编写的，主要目的用于教学，为了代码可读易懂，所以并没有在性能优化上下功夫，故其性能很差，同样的逻辑用rock实现运行耗时是java语言的40-50倍。