parameter与argument
=====================
按照直译，parameter与argument都可翻译为参数，但在编程语言中，两者略有不同：

**parameter** 通常指 **形参** （形式参数，formal parameter），即定义函数时括号里的变量；而 **argument** 通常指 **实参** （实际参数，actual argument），即函数调用时使用的值。

在K&R那本著名的C语言圣经中谈到过这个问题，如下：

    "We will generally use parameter for a variable named in the parenthesized list in a function definition, and argument for the value used in a call of the function. The terms formal argument and actual argument are sometimes used for the same distinction."

    -- 《The C Programming Language》Section 1.7 K&R