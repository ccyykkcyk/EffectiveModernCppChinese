# 第3章 移步现代C++

**CHAPTER 3 Moving to Modern C++**

说起知名的特性，C++11/14有一大堆可以吹的东西，`auto`，智能指针（*smart pointer*），移动语义（*move semantics*），*lambda*，并发（*concurrency*）——每个都是如此的重要，这章将覆盖这些内容。掌握这些特性是必要的，要想成为高效率的现代C++程序员需要小步迈进。在从C++98小步迈进到现代C++过程中遇到的每个问题，本章都会一一回答。你什么时候应该用{}而不是()创建对象？为什么别名（*alias*）声明比`typedef`好？`constexpr`和`const`有什么不同？常量（`const`）成员函数和线程安全有什么关系？这个列表越列越多，这章将会逐个回答这些问题。

- [Item 7:区别使用()和{}创建对象](./item7.md)
- [Item 8:优先考虑nullptr而非0和NULL](./item8.md)
- [Item 9:优先考虑别名声明而非typedefs](./item9.md)
- [Item 10:优先考虑限域枚举而非未限域枚举](./item10.md)
- [Item 11:优先考虑使用deleted函数而非使用未定义的私有声明](./item11.md)
- [Item 12:使用override声明重载函数](./item12.md)
- [Item 13:优先考虑const_iterator而非iterator](./item13.md)
- [Item 14:如果函数不抛出异常请使用noexcept](./item14.md)
- [Item 15:尽可能的使用constexpr](./item15.md)
- [Item 16:让const成员函数线程安全](./item16.md)
- [Item 17:理解特殊成员函数函数的生成](./item17.md)