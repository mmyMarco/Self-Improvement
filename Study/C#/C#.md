# C# 

[Microsft Docs](https://docs.microsoft.com/zh-cn/dotnet/csharp/)

1. [C# 中 USING 的一些用法讲解](http://shunji.wang/608.html)
2. [三种 C# using 的用法](https://developer.51cto.com/art/200908/147158.htm)
3. [C# 中的 Using 的用法](https://www.cnblogs.com/Pzhenzhen/p/8528587.html)
4. [C#中的IDisposable模式用法详解](https://www.jb51.net/article/54899.htm)
5. [C# 命名空间和程序集](https://www.cnblogs.com/GreenLeaves/p/7922590.html)
6. [C#中的程序集和反射介绍](https://www.xp.cn/b.php/70034.html)
7. [C#委托使用详解（Delegates）](https://www.cnblogs.com/liuhaorain/p/3911845.html)
8. [Lambda 表达式（C# 编程指南）](https://docs.microsoft.com/zh-cn/dotnet/csharp/programming-guide/statements-expressions-operators/lambda-expressions)
9. [DLL文件到底是什么，它们是如何工作的？](https://cloud.tencent.com/developer/ask/69913)
10. [堆和栈的区别 之 数据结构和内存](http://www.cleey.com/blog/single/id/776.html)

## Questions

1. 构造函数？类的声明中如果没有显示地提供实例构造函数，那么编译器会提供一个隐式默认构造函数，没有参数，方法体为空。可以为类声明构造函数，用以初始化字段和属性。**说明：可以像其他成员一样，为构造函数设置访问修饰符。**
2. 序列化？
3. 虚方法的用法？用于基类使用派生类中的方法时，使用修饰符 override（派生类中标记为需要被覆写） 和 virtual（基类中标记为虚方法） 标注，覆写方法可以在继承的任何层级出现，当使用对象基类中的覆写方法时，会一直上溯执行，直到找到标记 override 方法的最高派生版本。可以使用修饰符 new 来隐藏（终止）覆写方法。

## Record 

### 《C# 图解教程》

1. 编译时和运行时：C# 源文件 > C# 编译器 > CIL > JIT > 本机代码 at page.5
2. 参数类型：值参数、引用参数、输出参数数组参数  at page.59
3. 命名空间和程序集 at page.440
4. 构造函数 at page.100
5. 虚方法 at page.125
