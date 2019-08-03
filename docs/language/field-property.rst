field与property
===============
field常被翻译为 **字段** 或者 **域** ，property常被翻译为 **属性** 。

面向对象编程的主要工作是创造类和使用类，而类中则包含了众多成员，其中主要有 **成员变量** 和 **成员方法** ，成员变量定义了这个类有什么，而成员方法则定义了这个类能干什么。

从某种意义上来说，以上所说的成员变量就等同于字段。

面向对象的三大特征之一就是 **封装**，封装具体指：字段（成员变量）应该 **私有** 化，此外定义一些 **公共** 的方法以便从外部访问私有的字段（成员变量）。

以Java为例::

    class Phone{
        private int size;

        public getSize(){
            return size;
        }
        public setSize(int size){
            this.size = size;
        }
    }

这难免有些麻烦，因为每写一个字段，都要实现相应的getter/setter方法，而属性就是为此而设计的，使用属性的C#示例如下::

    class Phone{
        public int size {get; set}
    }

所以，请记住，Java中没有属性！