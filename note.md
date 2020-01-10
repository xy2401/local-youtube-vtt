




# spring-tips


## Spring Tips: Distributed Locks with Spring Integration

github.com/spring-tips/[distributed-locks-with-spring-integration](https://github.com/spring-tips/distributed-locks-with-spring-integration)


`jdbc-lock-registry` : 
[reference](https://docs.spring.io/spring-integration/reference/html/jdbc.html#jdbc-lock-registry) , 
[api](https://docs.spring.io/spring-integration/api/org/springframework/integration/jdbc/lock/JdbcLockRegistry.html)




```java
    //TODO 如何指定了 哪个对象的锁? 获取锁有数据库交互?
    String key = Integer.toString(id);
	Lock lock = registry.obtain(key);
```


## Spring Tips: Spring's Support for Kotlin Coroutines

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


## Laziness is the Ultimate Sophistication, both in Life and in Programming

懒惰是生活和编程中的终极 优雅/睿智

Most mainstream programming languages have adapted the functional style. We often hear why immutability is so important and how wonderful higher order functions are. These are but tools to reach a higher goal. In this presentation we will start by discussing the functional capabilities found in almost any language today, and quickly dive into the real essence of functional programming and learn how languages like Java have focused on what really matters.

大多数主流编程语言都适应了函数式风格。 我们经常听到为什么不变性如此重要，以及高阶函数多么出色。 这些只是达到更高目标的工具。 在本演示中，我们将首先讨论当今几乎所有语言中都具有的功能，然后快速深入探讨功能编程的实质，并学习Java之类的语言如何专注于真正重要的事情。


From the past:
- The past mainstream
- Imperative Style 
To the future:
- The new mainstream 
- Declarative and Functional 
- Declarative First 
- Functional Next
- very old idea, but a renewed interest 
- The charms of functional style 
"But" you ask?:
- The big elephant in the room 
- Not all languages created equal 
- Let's take a peek at Ruby
- What attracted me to Java 8 
- ELegance is useful 
- Performance is critical 
- What gives? 
Lessons from FP: 
- Let 's turn to a truly functional language—Haskell 
- How's that possible? 
- Benefits of pure functions 
  - Idempotent 
  - Referentially transparent 
  - Memoizable 
  - Easier to test 
  - Easier to parallelize 
  - can be lazy 
- Languages and defaults 
- A look at Scala 
an important decision for java 
- What 's special about Java 8? 
- Laziness is the ultimate sophistication 

从过去:
- 过去的主流
- 命令式
面向未来:
- 新的主流
- 声明式和函数式
- 声明式优先
- 函数式次之
- 很老的想法，但重新产生了兴趣
- 函数式风格的魅力
“但是”你问？:
- 房间里的大象
- 并非所有语言都是平等的
- 让我们来看看Ruby
- 吸引我学习Java 8的原因
- 优雅有用
- 性能很重要
- 是什么赋予了 ？
FP的经验教训：
- 让我们转向一种真正的函数语言-Haskell
- 那怎么可能？
- 纯函数的好处
  - 幂等
  - 引用透明
  - 可记忆
  - 更容易测试
  - 更容易并行化
  - 可以偷懒
- 语言和默认值
- 看看Scala
Java的重要决定
- Java 8有什么特别之处？
- 懒惰是终极的成熟

命令式编程(Imperative)、声明式编程(Declarative)和函数式编程(Functional)

- [《目送》Sophistication_龙应台_单色书](https://www.danseshu.com/books/2884/116315)
- [《Sophistication》_流沙飞沫_新浪博客](http://blog.sina.com.cn/s/blog_6ca844930102wnrp.html)
- [Oracle BrandVoice: Lazy Java Code Makes Applications Elegant, Sophisticated -- And Efficient at Runtime](https://www.forbes.com/sites/oracle/2018/01/22/lazy-java-code-makes-applications-elegant-sophisticated-and-efficient-at-runtime/#46fcda6855fa)
- [编程范式：命令式编程(Imperative)、声明式编程(Declarative)和函数式编程(Functional) - backslash112 - 博客园](https://www.cnblogs.com/sirkevin/p/8283110.html)
- [基本概念 | 引用透明 & 纯函数 & 代换模型 | 随便写写](http://songkun.me/2018/06/08/2018-06-08-referentially-transparent/)
- [函数副作用 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E5%87%BD%E6%95%B0%E5%89%AF%E4%BD%9C%E7%94%A8)






# JDK8MOOC

- JDK 8 MOOC: Lesson 1-1
    
    JDK 8 MOOC: Functional Programming in Java with Lambdas and Streams 
    This video goes through the reasons for adding lambda expressions to the Java language.    
    该视频介绍了将lambda表达式添加到Java语言的原因。

    In this course, you will learn how to use Lambda expressions and the 
    Streams API to program in a more functional style using JDK8. This 
    will enable you to solve common problems in a more concise and 
    more flexible way that can take advantage of multiple cores and 
    CPUs in your machine 

    在本课程中，您将学习如何使用Lambda表达式和
    流式API以使用JDK8以更实用的样式进行编程。 这个
    使您能够更简洁地解决常见问题，
    可以利用多个内核的更灵活的方式
    机器中的CPU


