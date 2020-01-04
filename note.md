




# spring-tips


- Spring Tips: Distributed Locks with Spring Integration

github.com/spring-tips/[distributed-locks-with-spring-integration](https://github.com/spring-tips/distributed-locks-with-spring-integration)


`jdbc-lock-registry` : 
[reference](https://docs.spring.io/spring-integration/reference/html/jdbc.html#jdbc-lock-registry) , 
[api](https://docs.spring.io/spring-integration/api/org/springframework/integration/jdbc/lock/JdbcLockRegistry.html)




```java
    //TODO 如何指定了 哪个对象的锁? 获取锁有数据库交互?
    String key = Integer.toString(id);
	Lock lock = registry.obtain(key);
```


- Spring Tips: Spring's Support for Kotlin Coroutines

github.com/[spring-tips/koroutines](https://github.com/spring-tips/koroutines)

 - [基础 - Kotlin 语言中文站](https://www.kotlincn.net/docs/reference/coroutines/basics.html)
 - [Basics - Kotlin Programming Language](https://kotlinlang.org/docs/reference/coroutines/basics.html)
 - [你的第一个 Kotlin 协程程序 - Kotlin 语言中文站](https://www.kotlincn.net/docs/tutorials/coroutines/coroutines-basic-jvm.html)
 - [Your first coroutine with Kotlin - Kotlin Programming Language](https://kotlinlang.org/docs/tutorials/coroutines/coroutines-basic-jvm.html)
 - [异步流 - Kotlin 语言中文站](https://www.kotlincn.net/docs/reference/coroutines/flow.html)
 - [Asynchronous Flow - Kotlin Programming Language](https://kotlinlang.org/docs/reference/coroutines/flow.html)


```kotlin
//简单的协程
fun one();
//同步阻塞代码块
fun two()
//带返回值的协程
fun three()
//异步流
fun four()
// ??? 和前面的有毛线关系?
fun five() 
```



# javaSe


- Laziness is the Ultimate Sophistication, both in Life and in Programming

懒惰是生活和编程中的终极 优雅/睿智

Most mainstream programming languages have adapted the functional style. We often hear why immutability is so important and how wonderful higher order functions are. These are but tools to reach a higher goal. In this presentation we will start by discussing the functional capabilities found in almost any language today, and quickly dive into the real essence of functional programming and learn how languages like Java have focused on what really matters.

大多数主流编程语言都适应了函数式风格。 我们经常听到为什么不变性如此重要，以及高阶函数多么出色。 这些只是达到更高目标的工具。 在本演示中，我们将首先讨论当今几乎所有语言中都具有的功能，然后快速深入探讨功能编程的实质，并学习Java之类的语言如何专注于真正重要的事情。


- [《目送》Sophistication_龙应台_单色书](https://www.danseshu.com/books/2884/116315)
- [《Sophistication》_流沙飞沫_新浪博客](http://blog.sina.com.cn/s/blog_6ca844930102wnrp.html)
[Oracle BrandVoice: Lazy Java Code Makes Applications Elegant, Sophisticated -- And Efficient at Runtime](https://www.forbes.com/sites/oracle/2018/01/22/lazy-java-code-makes-applications-elegant-sophisticated-and-efficient-at-runtime/#46fcda6855fa)
