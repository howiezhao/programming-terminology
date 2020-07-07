多重继承（Multiple inheritance）与多层继承（Multilevel inheritance）
===========================================================================

Multiple inheritance 常被翻译为 **多重继承** 或 **多继承**，Multilevel inheritance 常被翻译为 **多层继承**。

多重继承指一个类同时继承多个类，而多层继承指一个类继承了多个层次。

以 Python 为例来说，多重继承的示例如下::

    class A(B, C):
        pass

多层继承的示例如下::

    class B(C):
        pass

    class A(B):
        pass

.. note::
    有的文章将 **多重继承** 解释为 **多层继承**，这是有问题的。

    时刻记住，**多重继承** 和 **多继承** 是一个东西。

.. seealso::
   `<https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming)>`_
