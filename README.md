
Samanea: coding in the runtime
------

### Status: thinking on it

This is really a hard idea to try. I'll give more details here.
By now I have no idea about it.
You may fork it if you think there are good ideas to implement.

### Plan

Writing code and compile it to an excutable is an old style way of coding.
Suppose you are drawing, you just draw it right, would you like to program to draw?
Computers unveil the great magics of thinkings and thoeries, I think we can do it.

Samanea wants to provide a way people code in the run time, rather in an editor.
It might be much like a file system, just touch a file an it will be saved.
And that would be like living things, where programs run by them selves.

Since I'm not good at English, there are more details in Chinese.

### Plan in Chinese

文件系统很像编程语言的作用域, 有变量, 有函数, 还有相互的分隔.
文件系统优于编程环境的是文件系统在操作后马上保存, 而程序不是.
我尝试想一种方案, 人们在程序正常跑的环境中进行编程, 并且被保存.
文件的目录结构就像是代码的作用域, 不同的代码, 变量, 在不同的作用域和隔开.
因此在调试的同时作为编码, 调试结束就是运行的代码.

比如:
* 进入作用域 `set s-a (number 1)` 在作用域保存数据 `1`,
* `def f-a { x -> x ^ 2 }` 在作用域保存函数为 `f-a`
* `print ../p-a/d-a` 打印另一个作用域里的数据 `d-a`
* 将目录的结构作为数据类型
* 函数运行作为进程, 可以定时, 可以被 Kill

这样编程的用途可能有限, 但就算有限也已经可以走很远.
我目前没有足够的知识去设计这样的系统, 但会保持关注的.
