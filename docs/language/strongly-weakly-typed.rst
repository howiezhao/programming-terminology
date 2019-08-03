强类型与弱类型
=================

编程语言常被分为： **强类型** （Strongly Typed）语言和 **弱类型** （Weakly Typed）语言。

以下引用自知乎用户 `vczh <https://www.zhihu.com/people/excited-vczh>`_ 的回答：

    强类型：偏向于不容忍隐式类型转换。譬如说haskell的int就不能变成double

    弱类型：偏向于容忍隐式类型转换。譬如说C语言的int可以变成double

举例来说，在C语言中，以下语句是合法的，故其是弱类型::

    int a = 1;
    char b = '2';
    a + b;

在Python中，以下语句是不合法的，故其是强类型::

    a = 1
    b = '2'
    a + b


.. note::
    强、弱类型并不是指在定义变量时要加上类型名，这种行为应该称为 **显式** 、**隐式** 类型。