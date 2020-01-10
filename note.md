




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


[Oracle大规模开放在线课程：Java SE 8 Lambda和Streams，2016年](https://apexapps.oracle.com/pls/apex/f?p=44785:141:7184327235923::::P141_PAGE_ID,P141_SECTION_ID:478,3496)

 
## Lesson 1: Lambda Expressions    

Homework:
[Instructions Lesson01.pdf](Java.JDK 8 MOOC/resources/Lesson01.pdf) , 
[Java Start File - Lesson1.java](Java.JDK 8 MOOC/resources/Lesson1.java) , 
[Java Solutions File - SolutionsLesson1.java](Java.JDK 8 MOOC/resources/SolutionsLesson1.java) , 

Slides:
[Lesson-1-1.pdf](Java.JDK 8 MOOC/resources/Lesson-1-1.pdf) , 
[Lesson-1-2.pdf](Java.JDK 8 MOOC/resources/Lesson-1-2.pdf) , 
[Lesson-1-3.pdf](Java.JDK 8 MOOC/resources/Lesson-1-3.pdf) , 
[Lesson-1-4.pdf](Java.JDK 8 MOOC/resources/Lesson-1-4.pdf) , 
[Lesson-1-5.pdf](Java.JDK 8 MOOC/resources/Lesson-1-5.pdf) , 
[Lesson-1-6.pdf](Java.JDK 8 MOOC/resources/Lesson-1-6.pdf) , 
[Lesson-1-7.pdf](Java.JDK 8 MOOC/resources/Lesson-1-7.pdf) , 


This week covers the new lambda expressions feature added to Java SE 8. The lessons cover:

    Why lambda expressions are needed in Java.
    Why this feature was added to Java after twenty years.
    The syntax of lambda expressions.
    How to use lambda expressions and the rules that govern their use.
    Examples of classes and methods that use lambda expressions like the new removeIf and replaceAll methods in the Collections API.

 这周介绍了Java SE 8中新增的lambda表达式功能。课程内容包括：

    为什么在Java中需要lambda表达式。
    为什么二十年后将此功能添加到Java。
    lambda表达式的语法。
    如何使用lambda表达式以及控制其使用的规则。
    使用lambda表达式的类和方法的示例，例如Collections API中新的removeIf和replaceAll方法。

 

- Lesson 1-1 Why Does Java Need Lambda Expressions? (21:46)
- Lesson 1-2 Lambda Expression Syntax (9:55)
- Lesson 1-3: Functional Interfaces And Their Definition (11:36)
- Lesson 1-4: Functional Interfaces in the java.util.function Package (10:37)
- Lesson 1-5: Method and Constructor References (08:53)
- Lesson 1-6: Referencing External Variables in Lambda Expressions (07:10)
- Lesson 1-7: Useful New Methods In JDK8 That Can Use Lambdas (11:02)

## Lesson 2: Introduction to the Streams API 

Homework:
[Instructions Lesson01.pdf](Java.JDK 8 MOOC/resources/Lesson02.pdf) , 
[Java Start File - Lesson2.java](Java.JDK 8 MOOC/resources/Lesson2.java) , 
[Text File - SonnetI.txt](Java.JDK 8 MOOC/resources/SonnetI.txt) , 
[Java Solutions File - SolutionsLesson2.java](Java.JDK 8 MOOC/resources/SolutionsLesson2.java) , 

Slides:
[Lesson-2-1.pdf](Java.JDK 8 MOOC/resources/Lesson-2-1.pdf) , 
[Lesson-2-2.pdf](Java.JDK 8 MOOC/resources/Lesson-2-2.pdf) , 
[Lesson-2-3.pdf](Java.JDK 8 MOOC/resources/Lesson-2-3.pdf) , 
[Lesson-2-4.pdf](Java.JDK 8 MOOC/resources/Lesson-2-4.pdf) , 
[Lesson-2-5.pdf](Java.JDK 8 MOOC/resources/Lesson-2-5.pdf) , 
[Lesson-2-6.pdf](Java.JDK 8 MOOC/resources/Lesson-2-6.pdf) , 
[Lesson-2-7.pdf](Java.JDK 8 MOOC/resources/Lesson-2-7.pdf) , 


In lesson 2 you will learn how to use the new Streams API to apply functional programming techniques in Java. You will learn to:

    Use functional programming concepts.
    Define streams and stream pipelines in Java.
    Create object streams and primitive streams.
    Create streams using Java classes.
    Use intermediate operations in a stream pipeline.
    Use terminal operations in a stream pipeline.
    Use the Optional class to handle null values.

在第2课中，您将学习如何使用新的Streams API在Java中应用功能编程技术。 您将学习：

     使用函数式编程概念。
     在Java中定义流和流管道。
     创建对象流和原始流。
     使用Java类创建流。
     在流管道中使用中间操作。
     在流管道中使用终端操作。
     使用Optional类处理空值。
 
 
- Lesson 2-1: Introduction to Functional Programming Concepts (14:48)
- Lesson 2-2: Elements of a Stream (10:27)
- Lesson 2-3: Streams of Objects and Primitive Types (6:21)
- Lesson 2-4: Stream Sources in JDK8 (11:23)
- Lesson 2-5: Stream Interface: Intermediate Operations (13:17)
- Lesson 2-6: Stream Interface: Terminal Operations (11:43)
- Lesson 2-7: The Optional Class (14:28)


## Lesson 3: Advanced Lambda and Stream Concepts    

Homework:
[Instructions Lesson03.pdf](Java.JDK 8 MOOC/resources/Lesson03.pdf) , 
[Java Start File - Lesson3.java](Java.JDK 8 MOOC/resources/Lesson3.java) , 
[Java File RandomWords.java](Java.JDK 8 MOOC/resources/RandomWords.java) , 
[Java File Levenshtein.java](Java.JDK 8 MOOC/resources/Levenshtein.java) , 
[words text file](Java.JDK 8 MOOC/resources/words) , 
[RandomWordsSolution.java](Java.JDK 8 MOOC/resources/RandomWordsSolution.java) , 
[Solutions File - Lesson3Solution.java](Java.JDK 8 MOOC/resources/Lesson3Solution.java) , 
 

Slides:
[Lesson-3-1.pdf](Java.JDK 8 MOOC/resources/Lesson-3-1.pdf) , 
[Lesson-3-2.pdf](Java.JDK 8 MOOC/resources/Lesson-3-2.pdf) , 
[Lesson-3-3.pdf](Java.JDK 8 MOOC/resources/Lesson-3-3.pdf) , 
[Lesson-3-4.pdf](Java.JDK 8 MOOC/resources/Lesson-3-4.pdf) , 
[Lesson-3-5.pdf](Java.JDK 8 MOOC/resources/Lesson-3-5.pdf) , 
[Lesson-3-6.pdf](Java.JDK 8 MOOC/resources/Lesson-3-6.pdf) , 
[Lesson-3-7.pdf](Java.JDK 8 MOOC/resources/Lesson-3-7.pdf) , 

In lesson 3 you will learn advance stream concepts like reduction and collection. You will learn to:

Perform a reduction using streams.
Create and use finite and infinite streams in Java.
Avoid the use of forEach.
Save items from from a stream using the Collectors class and the collect method.
Use parallel stream and also learn when not to.
Use techniques for debugging and troublshooting streams.
Homework is linked in the Supporting Materials section.

在第3课中，您将学习高级概念，例如减少和收集。 您将学习：

使用流执行归约。
在Java中创建和使用有限流和无限流。
避免使用forEach。
使用Collectors类和collect方法从流中保存项目。
使用并行流，并了解何时不使用。
使用技术对流进行调试和故障排除。
作业在支持材料部分中链接。

- Lesson 3-1: Understanding and Using Reductions (18:41)
- Lesson 3-2: Finite and Infinite Streams (6:34)
- Lesson 3-3: Avoiding the Use of forEach (5:13)
- Lesson 3-4: Using Collectors (13:48)
- Lesson 3-5: Parallel Streams (And When Not To Use Them) (11:01)
- Lesson 3-6: Debugging Lambdas and Streams (6:17)
- Lesson 3-7: Course Conclusions (5:43)




## JDK 8 MOOC: Lesson 1-1 Lambda Expressionsc
    
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


Lesson Agenda   
- Why does Java need Lambda expressions 
- Lambda expression syntax 
- Functional interfaces and their definition 
- Functional Interfaces in the java.util.function package 
- Method and constructor references 
- Referencing external variables in Lambdas 
- Useful new methods in JDK 8 that can use Lambdas 

课程议程   
- 为什么Java需要Lambda表达式
- Lambda表达式语法
- 函数式接口及其定义
- java.util.function包中的函数式接口
- 方法和构造方法引用
- 在Lambdas中引用外部变量
- JDK 8中可以使用Lambda的有用新方法


1.0 java.lang.Thread    
5.0 java.utils.concurrent(jsr166)    
6.0 Phasers , etc (jsr166)    
7.0 Fork/Join Framework (jsr166y)    
8.0 Project Lambda    

 

The Problem: External Iteration  
- Our code controls iteration 
- Inherently serial: iterate from beginning to end 
- Not thread-safe 
  - Business logic is stateful 
  - Mutable accumulator variable 


问题：外部迭代    
- 我们的代码控制迭代   
- 固有序列：从头到尾重复  
- 不是线程安全的   
   - 业务逻辑是有状态的   
   - 可变的累加器变量   


### Internal Iteration With Inner Classes 
内部类的内部迭代


- Iteration handled by the library 
- Not inherently serial — traversal may be done in parallel 
- Traversal may be done lazily — so one pass, rather than three 
- Thread safe — client logic is stateless 
- High barrier to use 
  - Syntactically ugly 


- 由库处理的迭代
- 本质上不是串行的-遍历可以并行进行
- 遍历可能会比较懒惰-因此只能通过一次，而不是三遍
- 线程安全-客户端逻辑是无状态的
- 高使用障碍
   - 语法上很丑  