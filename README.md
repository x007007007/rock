# rock

rock是编译型，由基于栈的虚拟机运行的一门弱类型语言。

用java编写而成，主要用于教学目的，为了让代码可读易懂，所以并没有在优化上下功夫，故其性能很差，同样的逻辑用rock实现，运行耗时是java语言的40-50倍。

目前已经支持基本的赋值、流程控制（if、while）和调用java扩展函数，能够编写简单的逻辑。

接下来准备让其支持list & hashDict容器、自定义作用域，以及自定义函数。

