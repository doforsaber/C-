# C#程序结构

在我们学习研究C#编程语言的基本构建模块，让我们来看看一个最低限度的C#程序结构，使我们可以把它作为后面章节的参考。

## C# Hello World示例

一个C#程序主要由以下几部分组成：
- 命名空间声明
- 一个类
- 类方法
- 类属性
- 一个Main方法
- 语句和表达式
- 注释

让我们来看看下面的示例，将打印字的简单的代码 “Hello World”:
```
using System;
namespace HelloWorldApplication
{
    class HelloWorld
    {
        /* my first program in C# */
        Console.WriteLine("Hello World");
        console.ReadKey();
    }
}
```
让我们编译和运行上面的程序，这将产生以下结果：
``` 
Hello World
```