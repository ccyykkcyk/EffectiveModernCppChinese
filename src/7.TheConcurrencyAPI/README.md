# 第7章 并发API

**CHAPTER 7 The Concurrency API**

C++11的伟大成功之一是将并发整合到语言和库中。熟悉其他线程API（比如pthreads或者Windows threads）的开发者有时可能会对C++提供的斯巴达式（译者注：应该是简陋和严谨的意思）功能集感到惊讶，这是因为C++对于并发的大量支持是在对编译器作者约束的层面。由此产生的语言保证意味着在C++的历史中，开发者首次通过标准库可以写出跨平台的多线程程序。这为构建表达库奠定了坚实的基础，标准库并发组件（任务*tasks*，期望*futures*，线程*threads*，互斥*mutexes*，条件变量*condition variables*，原子对象*atomic objects*等）仅仅是成为并发软件开发者丰富工具集的基础。

在接下来的条款中，记住标准库有两个*future*的模板：`std::future`和`std::shared_future`。在许多情况下，区别不重要，所以我们经常简单的混于一谈为*futures*。

- [Item 35:优先考虑基于任务的编程而非基于线程的编程](./Item35.md)
- [Item 36:如果有异步的必要请指定std::launch::threads](./item36.md)
- [Item 37:从各个方面使得std::threads unjoinable](./item37.md)
- [Item 38:关注不同线程句柄析构行为](./item38.md)
- [Item 39:考虑对于单次事件通信使用void](./item39.md)
- [Item 40:对于并发使用std::atomic，volatile用于特殊内存区](./item40.md)
