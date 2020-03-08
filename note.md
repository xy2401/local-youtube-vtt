




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

大多数主流编程语言都适应了函数式风格。 我们经常听到为什么不变性如此重要，以及高阶函数多么出色。 这些只是达到更高目标的工具。 在本演示中，我们将首先讨论当今几乎所有语言中都具有的功能，然后快速深入探讨函数式编程的实质，并学习Java之类的语言如何专注于真正重要的事情。


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
- [基本概念 引用透明 & 纯函数 & 代换模型 随便写写](http://songkun.me/2018/06/08/2018-06-08-referentially-transparent/)
- [函数副作用 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E5%87%BD%E6%95%B0%E5%89%AF%E4%BD%9C%E7%94%A8)





###### jdk8mooc
# JDK8MOOC


[Oracle大规模开放在线课程：Java SE 8 Lambda和Streams，2016年](https://apexapps.oracle.com/pls/apex/f?p=44785:141:7184327235923::::P141_PAGE_ID,P141_SECTION_ID:478,3496)

[JDK 8: Lambdas and Streams Introduction](https://apexapps.oracle.com/pls/apex/f?p=44785:50:102256436925696)
  
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

 

- Lesson 1-1 Why Does Java Need Lambda Expressions? (21:46) [note](#jdk8mooc_lesson_1-1)
- Lesson 1-2 Lambda Expression Syntax (9:55) [note](#jdk8mooc_lesson_1-2)
- Lesson 1-3: Functional Interfaces And Their Definition (11:36) [note](#jdk8mooc_lesson_1-3)
- Lesson 1-4: Functional Interfaces in the java.util.function Package (10:37) [note](#jdk8mooc_lesson_1-4)
- Lesson 1-5: Method and Constructor References (08:53) [note](#jdk8mooc_lesson_1-5)
- Lesson 1-6: Referencing External Variables in Lambda Expressions (07:10) [note](#jdk8mooc_lesson_1-6)
- Lesson 1-7: Useful New Methods In JDK8 That Can Use Lambdas (11:02) [note](#jdk8mooc_lesson_1-7)

### Quiz

- Lambda expressions can be used anywhere a functional interface type is required, true or false?  [Answer](#True)
- Lambda表达式可以在需要功能接口类型的任何地方使用，是对还是错？
    - True
    - False
- Which of the following is an invalid lambda expression?   [Answer](#C)
- 以下哪个是无效的lambda表达式？
    - x -> x * 5
    - (x, y) -> x.length() – y.length()
    - () -> {process()}
    - (String x, String y) -> x + y
- How many methods must a functional interface have?[Answer](#D)
- 一个功能接口必须有几种方法？
    - 0
    - 1
    - As many as you want
    - Any nymber, so long as only 1 is abstract
- What is the annotation for a functional interface?[Answer](#C)
- 函数式接口的注解是?
    - @functional
    - @functionalinterface
    - @FunctionalInterface
    - @Functional   
- UnaryOperator is a special form of which functional interface?[Answer](#A)
- UnaryOperator是哪个功能接口的特殊形式？
    - Function
    - Supplier
    - Predicate
    - BinaryOperator
    - Consumer    
- Which two could be considered equivalent lambda expressions of the method reference, Buffer::position?[Answer](#BC)
- 哪两个可以视为方法引用 Buffer::position 的等效lambda表达式？
    - n -> Buffer.position(n)
    - (Buffer b, Integer n) -> b.position(n)
    - b -> b.position()
    - (Buffer b, long n) -> b.position(n)    
- In order to reference a variable from the surrounding scope in a Lambda expression, the variable must be:[Answer](#B)
- 为了在Lambda表达式中引用周围范围的变量，该变量必须为：
    - Definitely final
    - Effectively final
    - Possibly final
    - None of the above
- What functional interface type does the removeIf method of the Collections interface take as a parameter?[Answer](#D)
- Collections接口的removeIf方法将哪种功能接口类型作为参数?
    - Supplier
    - Consumer
    - BiPredicate
    - Predicate
- To convert all the Integers in a List, l, to their signum values, which two of the following Lambda expressions would work?[Answer](#AC)
- 要将列表l中的所有整数转换为它们的符号值，以下两个Lambda表达式中的哪两个有效?
    - l.replaceAll(n -> Integer.signum(n))
    - l.replace(n -> Integer.signum(n))
    - l.replaceAll(Integer::signum)
    - l.replaceAll(Number::signum)
    - l.replace(Integer::signum)
- The potential efficiency of the Logger class methods has been improved by adding methods that use which functional interface?[Answer](#C)
- 通过添加使用哪个功能接口的方法，可以提高Logger类方法的潜在效率。
    - Consumer
    - Function
    - Supplier
    - UnaryOperator


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

在第2课中，您将学习如何使用新的Streams API在Java中应用函数式编程技术。 您将学习：

     使用函数式编程概念。
     在Java中定义流和流管道。
     创建对象流和原始流。
     使用Java类创建流。
     在流管道中使用中间操作。
     在流管道中使用终端操作。
     使用Optional类处理空值。
 
 
- Lesson 2-1: Introduction to Functional Programming Concepts (14:48) [note](#jdk8mooc_lesson_2-1)
- Lesson 2-2: Elements of a Stream (10:27) [note](#jdk8mooc_lesson_2-2)
- Lesson 2-3: Streams of Objects and Primitive Types (6:21) [note](#jdk8mooc_lesson_2-3)
- Lesson 2-4: Stream Sources in JDK8 (11:23) [note](#jdk8mooc_lesson_2-4)
- Lesson 2-5: Stream Interface: Intermediate Operations (13:17) [note](#jdk8mooc_lesson_2-5)
- Lesson 2-6: Stream Interface: Terminal Operations (11:43) [note](#jdk8mooc_lesson_2-6)
- Lesson 2-7: The Optional Class (14:28) [note](#jdk8mooc_lesson_2-7)


### Quiz

- In functional programming, names may be associated with different values, true or false?[Answer](#False)
- 在函数式编程中，名称可能与不同的值关联，是对还是错？
    - True
    - False
- What is the minimum number of intermediate operations that can be used in a stream?[Answer](#A)
- stream 中可以使用的最小中间操作数是多少？
    - 0
    - 1
    - 2
    - 3
- Which three of the following are NOT interfaces of the stream package representing sequences of primitive values?[Answer](#ABE)
- 以下哪三个不是表示原始值序列的stream包的NOT接口?
    - ByteStream
    - ShortStream
    - IntStream
    - LongStream
    - FloatStream
- Which is the only interface that directly contains a parallelStream() method?[Answer](#D)
- 哪个是直接包含 parallelStream() 方法的唯一接口?
    - List
    - Set
    - Map
    - Collections
- Which two classes have a lines() method that returns a Stream<String>?[Answer](#BD)
- 哪两个类具有返回 Stream<String> 的 lines() 方法？
    - FileReader
    - BufferedReader
    - StringReader
    - Files
    - FileHandler
- The flatMap method of the Stream interface takes a stream as input and produces multiple streams as output, true or false?[Answer](#False)
- Stream接口的flatMap方法将一个流作为输入，并产生多个流作为输出，对还是错?
    - True
    - False
- The peek() method must not be used to alter the elements of a steam, true or false?[Answer](#True)
- 不能使用 peek() 方法来更改steam的元素，对还是错?
    - True
    - False    
- To get a deterministic result within a parallel stream when finding the first element, which method should you use?[Answer](#C)
- 要在找到第一个元素时在并行流中获得确定性结果，应使用哪种方法?
    - findParallelAny
    - findAny
    - findFirst
    - findAll
    - findParallelFirst
- When using an Optional and a Function that returns an Optional, you should use which method?[Answer](#C)
- 当使用Optional和Function返回Optional时，应该使用哪种方法?
    - map
    - optionalMap
    - flatMap
    - optionalFltMap
- The Optional class helps to reduce which type of exception?[Answer](#B)
- Optional类有助于减少哪种类型的异常?
    - IOException
    - NullPointerException
    - NumberFormatException
    - Exception    

参考:
[differences-between-imperative-and-functional](https://sookocheff.com/post/fp/differences-between-imperative-and-functional/ )
  


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

- Lesson 3-1: Understanding and Using Reductions (18:41) [note](#jdk8mooc_lesson_3-1)
- Lesson 3-2: Finite and Infinite Streams (6:34) [note](#jdk8mooc_lesson_3-2)
- Lesson 3-3: Avoiding the Use of forEach (5:13) [note](#jdk8mooc_lesson_3-3)
- Lesson 3-4: Using Collectors (13:48) [note](#jdk8mooc_lesson_3-4)
- Lesson 3-5: Parallel Streams (And When Not To Use Them) (11:01) [note](#jdk8mooc_lesson_3-5)
- Lesson 3-6: Debugging Lambdas and Streams (6:17) [note](#jdk8mooc_lesson_3-6)
- Lesson 3-7: Course Conclusions (5:43) [note](#jdk8mooc_lesson_3-7)

### Quiz

- What is the method signature of the reduce() method in the Stream interface?[Answer](#B)
- Stream 接口中的 reduce() 方法的方法签名是什么？
    - Stream reduce(BinaryOperator accumulator)
    - Optional reduce(BinaryOperator accumulator)
    - Optional reduce(UnaryOperatr accumulator)
    - Optional reduce(BiFunction accumulator)
- The accumulator of a reduction takes what as the first parameter?[Answer](#D) TODO
- 减少量的累加器将第一个参数作为参数?
    - The next element of the input stream
    - A full result
    - The first element of the input stream
    - A partial result
    - An Optional   
- An infinite stream can never be terminated, true or false?
- 无限流永远不会被终止，对还是错?[Answer](#B)
    - True
    - False
- To continue using an infinite stream, which terminal method should be used?[Answer](#C)
- 要继续使用无限流，应使用哪种终端方法？
    - forEver()
    - forAll()
    - forEach()
    - for()
- It is best-practice in functional programming to use the forEach() method as a terminal operation to modify state, true or false?[Answer](#B) TODO
- 在函数式编程中，最佳实践是将 forEach() 方法用作修改状态(真还是假)的终端操作?
    - True
    - False
- Which of the following is NOT a static method of the Collectors class?[Answer](#B) 
- 以下哪项不是Collectors类的静态方法?
    - toList()
    - toArray()
    - toSet()
    - toMap()
- The groupingBy() method of the Collectors class returns an object of what type? [Answer](#A) TODO
- Collectors类的 groupingBy() 方法返回什么类型的对象？
    - Map
    - Set
    - List
    - Collection   
- What method of the Stream interface should be used to convert a sequential stream to parallel? [Answer](#C)
- 应该使用哪种Stream接口方法将顺序流转换为并行流?
    - parallelise()
    - makeParallel()
    - parallel()
    - parallelStream()     
- Which is a useful method in the Stream interface to help debugging? [Answer](#D)
- Stream接口中哪个有用的方法可帮助调试?
    - poke()
    - print()
    - breakpoint()
    - peek()
- Which static method of the Collectors class will provide a Collector that will create a comma separated value (CSV) string of results from a stream?[Answer](#C)
- Collectors类的哪个静态方法将提供一个Collector，该Collector将从流中创建一个逗号分隔值(CSV)的结果字符串?
    - toString(“,”)
    - setSeparator(“,”)
    - joining(“,”)
    - connecting(“,”)
 
###### wxtvhtgdv9g
###### jdk8mooc_lesson_1-1
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

### Internal Iteration With Lambda Expressions 
Lambda表达式的内部迭代

- More readable 更具可读性
- More abstract 更抽象
- Less error-prone 少出错

### Section 1 Summary

- Need changes to Java to simplify parallel coding
- Lambda expressions simplify how to pass behaviour as a parameter

- 需要对Java进行更改以简化并行编码
- Lambda表达式简化了如何将行为作为参数传递


###### dd5ikxx4zpk
###### jdk8mooc_lesson_1-2
## Lesson 1-2:Lambda Expression Syntax


### Lambda Expressions Are Anonymous Functions
- Body of the Lambda may throw exceptions
- Single line Lambdas
- Do not need braces
- Do not need an explicit return statement
- Lambdas with a single parameter do not need brackets
- Lambdas with no parameters must have empty brackets

Lambda表达式是匿名函数
- Lambda的身体可能会引发异常
- 单行Lambdas
- 不需要大括号
- 不需要明确的return语句
- 具有单个参数的Lambda不需要括号
- 没有参数的Lambda必须带有空括号

Lambda Expression Syntax
```java
    () -> System.out.println("Hello Lambda")
    x -> x + 10
    (int x, int y) -> { return x + y; }
    (String x, String y) -> x.length() – y.length()
    (String x) -> {
        listA.add(x);
        listB.remove(x);
        return listB.size();
    }
```

Type Inference 
- Example method definition
    ```java
     static <T> T process(List<T> l, Comparator<T> c)
    ```
- Use the method
    ```java
    List<String> list = getList();
    process(list, (String x, String y) -> x.length() – y.length());
    ```
- Compiler is now smarter  编译器现在更智能 
    ```java
    String r = process(list, (x, y) -> x.length() – y.length())
    ```
- More typing with less typing 更少代码更多类型

### Section 2 Summary
- Syntax for Lambda expressions is simple
    - Brackets and braces are optional for certain situations
- Type inference means types often do not need to be explicitly stated
    - Java remains strongly, statically typed
 
- Lambda表达式的语法很简单
     - 在某些情况下，括号和括号是可选的
- 类型推断意味着通常不需要明确声明类型
     - Java保持强力，静态类型

###### ov6nnr6im6o
###### jdk8mooc_lesson_1-3
## Lesson 1-3:Functional Interfaces And Their Definition
函数式接口及其定义

### Lambda Expression Types
- A Lambda expression is an anonymous function
    - It is not associated with a class
- But Java is a strongly typed language
    - So what is the type of a Lambda expression?
- A Lambda expression can be used wherever the type is a functional interface
- This is a single abstract method type
- The Lambda expression provides the implementation of the abstract  method

- Lambda表达式是匿名函数
    - 与类无关
- 但是Java是一种强类型语言
    - 那么Lambda表达式的类型是什么？
- 只要类型是函数式接口，就可以使用Lambda表达式
- 这是一个抽象方法类型
- Lambda表达式提供了抽象方法的实现


### Functional Interface Definition
- An interface
- Has only one abstract method
- Before JDK 8 this was obvious
    - Only one method
- JDK 8 introduces default methods
    - Multiple inheritance of behaviour for Java
- JDK 8 also now allows static methods in interfaces
- @FunctionalInterface annotation

- 接口
- 只有一种抽象方法
- 在JDK 8之前，这很明显
    - 仅一种方法
- JDK 8引入了默认方法
    - Java行为的多重继承
- JDK 8现在还允许接口中使用静态方法
- @FunctionalInterface注解


### Functional Interfaces Examples

```java
interface FileFilter { boolean accept(File x); }
interface ActionListener { void actionPerformed(…); }
interface Callable<T> { T call(); }
```

### Section 3
- Lambda expressions can be used anywhere the type is a functional interface
    - A functional interface has only one abstract method
- The Lambda expression provides the implementation of the single abstract method of the functional interface

- Lambda表达式可以在类型是功能接口的任何地方使用
    - 功能接口只有一种抽象方法
- Lambda表达式提供功能接口的单一抽象方法的实现

###### kkfd9fwcmtk
###### jdk8mooc_lesson_1-4
## Lesson 1-4:Functional Interfaces in the java.util.function Package

Well defined set of general purpose functional interfaces
- All have only one abstract method
- Lambda expressions can be used wherever these types are referenced
- Used extensively in the Java class libraries
- Especially with the Stream API
- This section covers the generic interfaces
    - There are numerous type specific versions
    - Double, Int, Long and Obj forms
    - Review the package for more detail

定义明确的通用函数式接口集
- 全部只有一种抽象方法
- 在引用这些类型的任何地方都可以使用Lambda表达式
- 在Java类库中广泛使用
- 特别是使用Stream API
- 本节介绍了通用接口
    - 有许多类型特定的版本
    - Double，Int，Long和Obj形式
    - 查看package以获取更多详细信息


### Consumer<T>
Operation That Takes a Single Value And Returns No Result

- Also, BiConsumer<T,U> that takes two values and returns no result
- Default method available for composing functions
    - andThen(Consumer after)
```java
String s -> System.out.println(s)
(k, v) -> System.out.println("key:" + k + ", value:" + v)
```

### Supplier
A Supplier Of Results 结果供应商
- The opposite of a Consumer 消费者的反面  
```java
    () -> createLogMessage()
```

### Function<T,R>
A Function That Accepts One Argument And Returns A Result   
最一般的函数 f(x)=y
- Type of argument and result may be different
- Also, BiFunction<T,U,R> that accepts two arguments and returns a result
- Useful default methods for composing
    - compose, andThen
```java
Student s -> s.getName()
(String name, Student s) -> new Teacher(name, s)
```

### UnaryOperator<T>

unary adj. [数] 一元的 
Operator n. 经营者；操作员；话务员；行家

同类型特殊形式
- Specialised form of Function 
- Single argument and result of the same type
    - T apply(T a)
```java
String s -> s.toLowerCase()
```

### BinaryOperator<T>
- Specialised form of BiFunction
- Two arguments and a result, all of the same type
    - T apply(T a, T b)
```java
(String x, String y) -> {
 if (x.length() > y.length())
 return x;
 return y;
}
```

### Predicate
A Boolean Valued Function Of One Argument
- Also, BiPredicate, that takes two arguments
- Has useful default and static methods for combination
    - and(), or(), negate(), isEqual()
```java
Student s -> s.graduationYear() == 2011
Files.find(start, maxDepth,
 (path, attr) -> String.valueOf(path).endsWith(".js") &&
 attr.size() > 1024,
 FileVisitOption.FOLLOW_LINKS);
```

### Section 4 Summary

- The function package provides a range of functional interfaces
- Used extensively in Streams
    - But also used in many other places
- Unlikely you will need to define your own extensions to the function package

- 该函数包提供了一系列函数式接口
- 在流中广泛使用
    - 但也用于许多其他地方
- 不太可能需要为函数包定义自己的扩展

###### curwqa7kwdk
###### jdk8mooc_lesson_1-5   
## Lesson 1-5:Method and Constructor References
方法与构造方法引用

### Method References 方法引用

Method references let us reuse a method as a lambda expression  
方法引用使我们可以将方法重用为lambda表达式
```java
FileFilter x = (File f) -> f.canRead();
FileFilter x = File::canRead;
```
- Format: target_reference::method_name
    - Three kinds of method reference
- Static method
- Instance method of an arbitary type
- Instance method of an existing object

- 格式: target_reference::method_name
    - 三种方法引用
- 静态方法
- 任意类型的实例方法
- 现有对象的实例方法
 
Rules For Construction 规则解释

    Lambda: (args) -> ClassName.staticMethod(args)    
    Method Ref: ClassName::staticMethod    
    Lambda: (arg0, rest) -> arg0.instanceMethod(rest)    
    Method Ref: ClassName::instanceMethod    
    Lambda: (args) -> expr.instanceMethod(args)   
    Method Ref: expr::instanceMethod   

Examples

    Lambda: (String s) -> Integer.parseInt(s);
    Method Ref: Integer::parseInt
    Lambda: (String s, int i) -> s.substring(i)
    Method Ref: Axis a -> getLength(a)
    Lambda: String::substring
    Method Ref: this::getLength


### Constructor References 构造函数引用

Same concept as a method reference  
与方法参考相同的概念
- For the constructor
 
```java
Factory<List<String>> f = () -> new ArrayList<String>();
Factory<List<String>> f = ArrayList<String>::new;
```

### Section 5 Summary
- Method references provide a shorthand notation for simple Lambdas
- Three types depending on how they are used
- Can also be used for constructors
- 方法引用提供了简单Lambda的简写形式
- 三种类型，取决于使用方式
- 也可以用于构造函数


###### scifq_s4cqu
###### jdk8mooc_lesson_1-6
## Lesson 1-6:Referencing External Variables in Lambda Expressions
在Lambda表达式中引用外部变量

### Local Variable Capture
- Lambda expressions can refer to effectively final local variables from the surrounding scope
    - Effectively final: A variable that meets the requirements for final variables (i.e., assigned once), even if not explicitly declared final
    - Closures on values, not variables
```java
void expire(File root, long before) {
 root.listFiles(File p -> p.lastModified() <= before);
}
```

- Lambda表达式可以有效地引用来自周边范围
    - 有效最终：满足最终变量要求的变量 (即分配一次)，即使未明确声明为final
- 闭包值，而不是变量

### What Does ‘this’ Mean In A Lambda

- ‘this’ refers to the enclosing object, not the lambda itself
- Think of ‘this’ as a final predefined local
- Remember the Lambda is an anonymous function
    - It is not associated with a class
    - Therefore there can be no ‘this’ for the Lambda

- “ this”是指封闭对象，而不是lambda本身
- 将“ this”视为最终的预定义本地
- 记住Lambda是一个匿名函数
    - 与 class 无关
    - 因此Lambda不可能没有“ this” TODO

### Referencing Instance Variables
**Which are not final, or effectively final**
不是最终的，或者实际上不是最终的 TODO

```java
class DataProcessor {
 private int currentValue;
 public void process() {
 DataSet myData = myFactory.getDataSet();
 dataSet.forEach(d -> d.use(currentValue++));
 }
}   
```
```java
class DataProcessor {
 private int currentValue;
 public void process() {
 DataSet myData = myFactory.getDataSet();
 dataSet.forEach(d -> d.use(this.currentValue++));
 }
}
```
‘this’ (which is effectively final) inserted by the compiler 
编译器插入的“ this”(实际上是最终的) 

### Section 6 Summary
- Variables in the surrounding scope can be used in a Lambda expression
    - But they must be either final, or effectively final
- this in a Lambda refers to the object of the surrounding scope
    - The compiler will insert a reference to this for you where required

- Lambda表达式中可以使用周围范围内的变量
    - 但是它们必须是最终的，或者实际上是最终的
- 在Lambda中，这是指周围范围的对象
    - 编译器将在需要时为您插入对此的引用

###### olkf7vpjmfg
###### jdk8mooc_lesson_1-7

## Lesson 1-7:Useful New Methods In JDK 8 That Can Use Lambdas
JDK 8中可以使用Lambda的有用新方法 

### Iterable Interface 可迭代接口

- Iterable.forEach(Consumer c)

Ps.这不是 流 , 是 Iterable 接口下的 默认方法

```java
List<String> myList = ...
myList.forEach(s -> System.out.println(s));
myList.forEach(System.out::println);
```

### Collection Interface
PS.依旧是 默认方法
- Collection.removeIf(Predicate p)
```java
List<String> myList = ...
myList.removeIf(s -> s.length() == 0);
```

### List Interface
Ps.依然不是流 虽然 Map 一样实现
- List.replaceAll(UnaryOperator o)
```java
List<String> myList = ...
myList.replaceAll(s -> s.toUpperCase());
myList.replaceAll(String::toUpperCase);
```

### List Interface
PS.旧瓶装新酒 你是新方法吗? 还真是,原来工具方法类中的方法移动到接口默认方法中 所以应该是 旧瓶装旧酒 XD 
- List.sort(Comparator c)
- Replaces Collections.sort(List l, Comparator c)
```java
List<String> myList = ...
myList.sort((x, y) -> x.length() – y.length());
```


### Logger Class
- This is a common problem
    - logger.finest(createComplexMessage());
- createComplexMessage() is always called, even when not required
    - Heisenberg’s Uncertainty Principle in software
- New methods in Logger class
    - Takes a Supplier as an argument (which is a functional interface)
- Simple change to code has big impact on performance
    - logger.finest(() -> createComplexMessage());
- We now pass how to create the message, not the actual message

- 这是一个普遍的问题
    - logger.finest(createComplexMessage());
- 即使不需要，也总是调用createComplexMessage()
    - 海森堡的软件不确定性原则
- Logger类中的新方法
    - 将Supplier作为参数(这是一个函数式接口)
- 简单地更改代码会对性能产生重大影响
    - logger.finest(() -> createComplexMessage());
- 现在我们传递如何创建消息，而不是实际消息


### Section 8
- Use the new methods in JDK 8 to eliminate the frequent need for loops
- Remember that a Lambda provides behaviour, not a value
    - Very useful for conditional uses of data

- 使用JDK 8中的新方法来消除对循环的频繁需求
- 请记住，Lambda提供的是行为，而非值
    - 对于有条件地使用数据非常有用

### Summary
- Lambda expressions provide a simple way to pass behaviour as a parameter, or assign to a variable
- They can be used wherever a functional interface type is used
    - The Lambda provides the implementation of the single abstract method
- Method and constructor references can be used as shorthand
- Several useful new methods in JDK 8 that can use Lambdas

- Lambda表达式提供了一种简单的方式来将行为作为参数传递或分配给变量
- 它们可以在使用功能接口类型的任何地方使用
    - Lambda提供单一抽象方法的实现
- 方法和构造方法参考可用作速记
- JDK 8中可以使用Lambda的几种有用的新方法

PS.授人以鱼不如授人以渔

###### igq7yth5ljy
###### jdk8mooc_lesson_2-1
## Lesson 2:Introduction To The Streams API
Streams API简介


### Lesson2 Agenda 课程议程
- Introduction to functional programming concepts
- Elements of a Stream
- Streams of objects and primitive types
- Stream sources in JDK 8
- The Stream interface: Intermediate operations
- The Stream interface: Terminal operations
- The Optional class

- 函数式编程概念简介
- 流元素
- 对象和原始类型的流
- JDK 8中的流源
- Stream接口：中间操作
- Stream接口：终端操作
- Optional 类

## Lesson 2-1:Introduction to Functional Programming Concepts

### Imperative Programming 命令式编程
**Names And Values**
- Use variables as an association between names and values
- Use sequences of commands
    - Each command consists of an assignment
    - Can change a variable’s value
    - Form is <variable_name> = <expression>
    - Expressions may refer to other variables
        - Whose value may have been changed by preceding commands
    - Values can therefore be passed from command to command
    - Commands may be repeated through loops

- 使用变量作为名称和值之间的关联
- 使用命令序列
    - 每个命令都包含一个分配
    - 可以更改变量的值
    - 形式为<变量名称> = <表达式>
    - 表达式可能引用其他变量
        - 先前的命令可能更改了其值
    - 因此可以在命令之间传递值
    - 可以通过循环重复命令

### Functional Programming 函数式编程
**Names And Values**
- Based on structured function calls
- Function call which calls other functions in turn (composition)
    ```
    <function1>(<function2>(<function3> … ) … )
    ```
- Each function receives values from, and passes values back the calling function
- Names are only used as formal parameters
    - Once value is assigned it can not be changed
- No concept of a command, as used in imperative code
    - Therefore no concept of repetition

- 基于结构化的函数调用
- 函数调用，依次调用其他函数(组成)
     ```
     <function1>(<function2>(<function3> … ) … )
     ```
- 每个函数从调用函数接收值并将其传递回调用函数
- 名称仅用作形式参数
    - 分配值后就无法更改
- 没有命令的概念，如命令式代码中使用的
    - 因此没有重复的概念

### Names And Values
- Imperative
    - The same name may be associated with different values
- Functional
    - A name is only ever associated with one value

- 命令式
    - 同一名称可能与不同的值相关联
- 函数式
    - 名称仅与一个值相关联

### Execution Order 执行顺序
- Imperative
    - Values associated with names can be changed
    - The order of execution of commands forms a contract
        - If it is changed, the behaviour of the application may change
- Functional
    - Values associated with names cannot be changed
    - The order of execution does not impact the results
    - There is no fixed execution order

- 命令式
    - 与名称相关的值可以更改
    - 命令的执行顺序形成合同
        - 如果更改，则应用程序的行为可能会更改
- 函数式
    - 与名称关联的值不能更改
    - 执行顺序不影响结果
    - 没有固定的执行顺序

### Repetition 重复
- Imperative
    - Values associated with names may be changed by commands
    - Commands may be repeated leading to repeated changes
    - New values may be associated with the same name through repetition (loops)
- Functional
    - Values associated with names may not be changed
    - Repeated changes are achieved by nested function calls
    - New values may be associated with the same name through recursion

- 命令式
    - 与名称相关的值可以通过命令更改
    - 命令可能会重复，导致重复更改
    - 新值可能通过重复(循环)与相同名称相关联
- 函数式
    - 与名称关联的值不得更改
    - 通过嵌套函数调用实现重复更改
    - 新值可能通过递归与相同名称相关联

### Functions As Values
- Functional programming allows functions to be treated as values
    - This is why Lambda expressions were required in JDK 8
    - To make this much simpler than anonymous inner classes

- 函数式编程允许将函数视为值
    - 这就是为什么在JDK 8中需要Lambda表达式的原因
    - 比匿名内部类要简单得多


### Section 1 Summary
- Imperative and functional approaches are very different
- Imperative
    - Values associated with names can be changed
    - Order of execution is defined as a contract
    - Repetition is explicit and external
- Functional
    - Values associated with names are set once and cannot be changed
    - Order of execution is not defined
    - Repetition is through the use of recursion

- 命令式和函数式性方法截然不同
- 命令式
    - 与名称相关的值可以更改
    - 执行顺序定义为合同
    - 重复是明确的和外部的
- 函数式
    - 与名称关联的值仅设置一次，不能更改
    - 执行顺序未定义
    - 重复是通过使用递归

###### j4clzago_im
###### jdk8mooc_lesson_2-2
## Lesson 2-2:Elements of a Stream
流元素

### Stream Overview
**At The High Level**
- Abstraction for specifying aggregate computations
    - Not a data structure
    - Can be infinite
- Simplifies the description of aggregate computations
    - Exposes opportunities for optimisation
    - Fusing, laziness and parallelism

- 用于指定聚合计算的抽象
    - 不是数据结构
    - 可以无限
- 简化了汇总计算的描述
    - 展示优化机会
    - 融合，懒惰和并行

 
- A stream pipeline consists of three types of things
    - A source
    - Zero or more intermediate operations
    - A terminal operation
        - Producing a result or a side-effect

- 流管道包括三种类型的事物
    - 来源
    - 零个或多个中间操作
    - 终端操作
        - 产生结果或产生副作用


>Source -> Intermediate Operation -> Intermediate Operation -> Terminal Operation  -> Result
```java
int total = transactions.stream()
 .filter(t -> t.getBuyer().getCity().equals("London"))
 .mapToInt(Transaction::getPrice)
 .sum();
```

### Stream Terminal Operations
- The pipeline is only evaluated when the terminal operation is called
    - All operations can execute sequentially or in parallel
    - Intermediate operations can be merged
        - Avoiding multiple redundant passes on data
        - Short-circuit operations (e.g. findFirst)
        - Lazy evaluation
    - Stream characteristics help identify optimisations
        - DISTINT stream passed to distinct() is a no-op

- 仅在调用终端操作时评估管道
    - 所有操作均可顺序执行或并行执行
    - 中间操作可以合并
        - 避免多次重复传递数据
        - 短路操作(例如findFirst)
        - 懒惰的评价
    - 流特征有助于确定优化
        - 传递给 distinct() 的DISTINT流是无操作的

### Section 2 Summary
- Think of a Stream as like a pipeline
- Processes data from the source
    - No explicit loop used
    - Which means a Stream can easily be made parallel

- 将流视为管道
- 处理源中的数据
    - 不使用显式循环
    - 这意味着可以轻松地将Stream并行化

###### o9tajxdd9iu
###### jdk8mooc_lesson_2-3
## Lesson 2-3:Streams of Objects and Primitive Types

对象和原始类型流

### Objects And Primitives
对象与原始类型

- The Java language is not truly object oriented
- Primitive types are included
    - byte, short, int, long, double, float, char
- For some situations these are wrapped as objects
    - E.g. storage in collections
    - Byte, Short, Integer, etc.
- Conversion between primitive and object representation is often handled by auto-boxing and unboxing


- Java语言不是真正的面向对象
- 包括原始类型
    - byte, short, int, long, double, float, char
- 在某些情况下，这些被包装为对象
    - 例如 存储在集合中
    - Byte, Short, Integer,等
- 基本和对象表示之间的转换通常通过自动装箱和拆箱来处理


### Object Streams

- By default, a stream produces elements that are objects
- Sometimes, this is not the best solution

```java
    int highScore = students.stream()
        .filter(s -> s.graduationYear() == 2015)
        .map(s -> s.getScore())
        .max(Integer::compare);
```

    The stream from map has to auto-box ints to objects  
    getScore()returns a primitive int  
    max() must unbox each Integer object to get the value  
    
    map出来的stream必须 自动装箱 int转换为对象
    getScore()返回的是原始类型
    max() 必须要争对每一个  Integer 拆箱以得到值


### Primitive Streams
原始流

- To avoid a lot of unnecessary object creation and work we have three primitive stream types
    - IntStream, DoubleStream, LongStream
- These can be used with certain stream operations

- 为避免大量不必要的对象创建和工作，我们提供了三种原始流类型
    - IntStream，DoubleStream，LongStream
- 这些可以与某些流操作一起使用

```java
    int highScore = students.stream()
        .filter(s -> s.graduationYear() == 2015)
        .mapToInt(s -> s.getScore())
        .max();
```
The stream from mapToIntisa stream of int values, so noboxing or unboxing   
来自mapToIntisa流的int值流，因此不进行装箱或拆箱 

### Section 3 
Summary
- Java has primitive values as well as object types
- To improve stream efficiency we have three primitive stream types
    - IntStream, DoubleStream, LongStream
- Use methods like mapToInt(), mapToDouble(), mapToLong()

- Java具有原始值和对象类型
- 为了提高流效率，我们提供了三种原始流类型
    - IntStream，DoubleStream，LongStream
- 使用诸如 mapToInt(), mapToDouble(), mapToLong() 之类的方法

###### pbtfl7t_hlw
###### jdk8mooc_lesson_2-4
## Lesson 2-4:Stream Sources in JDK 8

### JDK 8 Libraries
- There are 95 methods in 23 classes that return a Stream
    - Many of them, though are intermediate operations in the Stream interface
- 71 methods in 15 classes can be used as practical Streamsources

- 23个类中有95个方法返回一个Stream
    - 尽管其中许多是Stream接口中的中间操作
- 15类中的71种方法可用作实用的Stream源

### Collection Interface
- stream()
    - Provides a sequential stream of elements in the collection
- parallelStream()
    - Provides a parallel stream of elements in the collection
    - Uses the fork-join framework for implementation

- stream()
    - 在集合中提供顺序的元素流
- parallelStream()
    - 在集合中提供并行的元素流
    - 使用fork-join框架进行实施

### Arrays Class

- stream()
    - An array is a collection of data, so logical to be able to create a stream
    - Provides a sequential stream
    - overloaded methods for different types
        - double, int, long, Object

- stream()
    - 数组是数据的集合，因此逻辑上能够创建流
    - 提供顺序流
    - 不同类型的重载方法
        - double，int，long，Object

### Files Class

- find(Path, BiPredicate, FileVisitOption)
    - A stream of Filereferences that match a given BiPredicate
    - 匹配给定BiPredicate的文件引用流
- list(Path)
    - A stream of entries from a given directory
    - 给定目录中的条目流
- lines(Path)
    - A stream of strings that are the lines read from a given file
    - 字符串流，即从给定文件中读取的行
- walk(Path, FileVisitOption)
    - A stream of file references walking from a given Path
    - 从给定路径走来的文件引用流

### Random Numbers
Generating Infinite Streams  
产生无限流

- Three random related classes
    - Random, ThreadLocalRandom, SplittableRandom
- Methods to produce finite or infinite streams of random numbers
    - ints(), doubles(), longs()
    - Four versions of each
        - Finite or infinite
        - With and without seed

- 三个随机相关的类
    - Random, ThreadLocalRandom, SplittableRandom
- 产生有限或无限随机数流的方法
    - ints(), doubles(), longs()
    - 每个都有四个版本
        - 有限或无限
        - 有无种子

### Miscellaneous Classes And Methods
杂类和方法

- JarFile/ZipFile: stream()
    - Returns a Filestream of the contents of the compressed archive
    - 返回压缩档案内容的Filestream
- BufferedReader: lines()
    - Returns a stream of strings that are the lines read from the input
    - 返回字符串流，该字符串流是从输入中读取的行
- Pattern: splitAsStream()
    - Returns a stream of strings of matches of a pattern
    - 返回模式匹配字符串流
    - Like split(), but returns a stream rather than an array
    - 类似于 split(), 但返回流而不是数组
- CharSequence
    - chars(): Char values as ints for the sequence
    - chars(): Char 值作为序列的整数
    - codePoints():Code point values for this sequence
    - codePoints():此序列的代码点值
- BitSet
    - stream(): Indices of bits that are set
    - stream(): 设置的位的索引

### Stream Static Methods

IntStream, DoubleStream, LongStream

- These interfaces are primitive specialisations of the Streaminterface
- 这些接口是Stream接口的原始专业化
- concat(Stream, Stream), empty()
    - Concatenates two specified streams, returns an empty stream
    - 连接两个指定的流，返回空流
- of(T... values)
    - A stream that consists of the specified values
    - 由指定值组成的流
- range(int, int), rangeClosed(int, int)
    - A stream from a start to an end value (exclusive or inclusive)
    - 从开始到结束值(独占或包含)的流
- generate(IntSupplier), iterate(int, IntUnaryOperator)
    - An infinite stream created by a given Supplier
    - 给定供应商创建的无限流
    - iterate()uses a seed to start the stream
    - iterate() 使用种子启动流

### Section 4

Summary

- Numerous places to get stream sources
    - Useful methods for retrieving lines from files, files from archives, etc.
- Only Collectioncan provide a parallel stream directly

- 许多获得流源的地方
    - 从文件中检索行，从归档中检索文件的有用方法等。
- 只有Collection可以直接提供并行流



###### 2eir0u78_ga
###### jdk8mooc_lesson_2-5   
## Lesson 2-5:Stream Interface:Intermediate Operations
流接口:中间操作

### Stream Interface
Overview

- A stream provides a sequence of elements
    - Supporting either sequential or parallel aggregate operations
- Most operations take a parameter that describes its behaviour
    - Typically using a Lambda expression
    - Must be non-interfering (does not modify the stream)
    - Typically stateless
- Streams may be changed from sequential to parallel (and vice-versa)
- All processing is done either sequentially or in parallel
    - Last call wins

- 流提供一系列元素
    - 支持顺序或并行聚合操作
- 大多数操作都采用描述其行为的参数
    - 通常使用Lambda表达式
    - 必须是无干扰的(不修改流)
    - 通常为无状态
- 流可以从顺序更改为并行(反之亦然)
- 所有处理顺序执行或并行执行
    - 最后一次调用获胜

### Filtering And Mapping    

- distinct()
    - Returns a stream with no duplicate elements
    - 返回没有重复元素的流
- filter(Predicate p)
    - Returns a stream with only those elements that return true for the Predicate
    - 返回仅包含为谓词返回true的那些元素的流
- map(Function f)
    - Return a stream where the given Functionis applied to each element on the input stream
    - 返回将给定Function应用于输入流中每个元素的流
- mapToInt(), mapToDouble(), mapToLong()
    - Like map(), but producing streams of primitives rather than objects
    - 与 map() 类似，但生成原始流而不是对象流

### Maps and FlatMaps
Map Values in a Stream

    Map --> Input Stream --> 1-to-1 mapping --> Output Stream
    FlatMap --> Input Stream --> 1-to-many mapping --> Output Stream

### FlatMapExample

Words in a File

```java
    List<String> output = reader
        .lines()
        .flatMap(line -> Stream.of(line.split(REGEXP)))
        .filter(word -> word.length() > 0)
        .collect(Collectors.toList());
```

### Restricting The Size Of A Stream

限制流的大小

- skip(long n)
    - Returns a stream that skips the first nelements of the input stream
    - 返回一个跳过输入流前几个元素的流
- limit(long n)
    - Returns a stream that only contains the first nelements of the input stream
    - 返回仅包含输入流的前元素的流
    
```java    
    String output = bufferedReader
        .lines()
        .skip(2)
        .limit(2)
        .collect(Collectors.joining());
```

### Sorting and Unsorting
排序和取消排序

- sorted(Comparator c)
    - Returns a stream that is sorted with the order determined by the Comparator
    - sorted()with no arguments sorts by natural order
- unordered()
    - Inherited from BaseStream
    - Returns a stream that is unordered (used internally)
    - Can improve efficiency of operations like distinct()and groupingBy()

- sorted(Comparator c)
    - 返回按比较器确定的顺序排序的流
    - sorted()，不带参数，按自然顺序排序
- unordered()
    - 继承自BaseStream
    - 返回无序的流(内部使用)
    - 可以提高诸如distinct()和groupingBy()之类的操作效率 ?why?


### Observing Stream Elements

As They Go Past

观察流元素 , 当他们过去时

- peek(Consumer c)
    - Returns an output stream that is identical to the input stream
    - Each element is passed to the accept()method of the Consumer
    - The Consumermust not modify the elements of the stream
    - Useful for debugging and doing more than one thing with a stream

- peek(Consumer c)
    - 返回与输入流相同的输出流
    - 每个元素都传递给使用者的 accept()方法
    - 消费者不得修改流中的元素
    - 对于调试和对流执行多项操作很有用

### Section 5
Summary

- Stream interface represents aggregate operations on elements
- Most methods can use Lambda expressions to define behaviour
- Powerful range of intermediate operations allow streams to be manipulated as required
    - Build up complex processing from simple building blocks

- 流接口表示对元素的聚合操作
- 大多数方法可以使用Lambda表达式定义行为
- 强大的中间操作范围允许根据需要对流进行操作
    - 从简单的构建块构建复杂的处理

###### 4jjxu8a6cuy
###### jdk8mooc_lesson_2-6
## Lesson 2-6:Stream Interface:Terminal Operations
流接口：终端操作 

### Terminal Operations
终端操作 

- Terminates the pipeline of operations on the stream
- Only at this point is any processing performed
    - This allows for optimisation of the pipeline
        - Lazy evaluation
        - Merged/fused operations
        - Elimination of redundant operations
        - Parallel execution
- Generates an explicit result or a side effect

- 终止流上的操作流水线
- 仅在此时执行任何处理
    - 这样可以优化管道
        - 懒惰的评价
        - 合并/合并操作
        - 消除多余的操作
        - 并行执行
- 产生明确的结果或副作用

### Matching Elements
 
- findFirst()
    - The first element that matches
    - 第一个匹配的元素
- findAny()
    - Works the same way as findFirst(), but for a parallel stream
    - 与findFirst()相同，但用于并行流
- boolean allMatch(Predicate p)
    - Whether all the elements of the stream match using the Predicate
    - 是否使用 Predicate 匹配流中的所有元素
- boolean anyMatch(Predicate p)
    - Whether any of the elements of the stream match using the Predicate
    - 是否使用Predicate匹配流中的任何元素
- boolean noneMatch(Predicate p)
    - Whether no elements match using the Predicate 
    - 使用Predicate是否没有元素匹配

 ### Collecting Results

 - collect(Collector c)
    - Performs a mutable reduction on the stream 
    - 对流执行可变还原 ?
 - toArray() 
    - Returns an array containing the elements of the stream 
    - 返回包含流元素的数组 

### Numerical Results

Object Stream

数值结果

- count()
    - Returns how many elements are in the stream
- max(Comparator c)
    - The maximum value element of the stream using the Comparator
    - Returns an Optional, since the stream may be empty
- min(Comparator c)
    - The minimum value element of the stream using the Comparator
    - Returns an Optional, since the stream may be empty

- count()
    - 返回流中有多少个元素
- max(Comparator c)
    - 使用比较器的流的最大值元素
    - 返回Optional，因为流可能为空
- min(Comparator c)
    - 使用比较器的流的最小值元素
    - 返回Optional，因为流可能为空 


Primitive Type Streams (IntStream, DoubleStream, LongStream)    
基本类型流 (IntStream, DoubleStream, LongStream)


- average()
    - Return the arithmetic mean of the stream
    - Returns an Optional, as the stream may be empty
- sum()
    - Returns the sum of the stream elements

- average()
    - 返回流的算术平均值
    - 返回Optional，因为流可能为空
- sum()
    - 返回流元素的总和


### Iteration
迭代

- forEach(Consumer c)
    - Performs an action for each element of this stream
    - 为此流的每个元素执行一个动作
- forEachOrdered(Consumer c)
    - Like forEach, but ensures that the order of the elements (if one exists) is respected when used for a parallel stream
    - 与forEach类似，但确保在用于并行流时尊重元素的顺序(如果存在)
- Use with caution!
    - 请谨慎使用！
    - Encourages non-functional (imperative) programming style
    - 鼓励非功能性(命令式)编程风格
    - More detail in week 3
    - 第3周有更多详情



### Folding A Stream

折叠流

Creating A Single Result From Multiple Input Elements

从多个输入元素创建单个结果

- reduce(BinaryOperator accumulator)
    - Performs a reduction on the stream using the BinaryOperator
    - The accumulatortakes a partial result and the next element, and returns a new partial result
    - Returns an Optional
    - Two other versions
        - One that takes an initial value (does not return an Optional)
        - One that takes an initial value and BiFunction(equivalent to a fused map and reduce)


- reduce(BinaryOperator accumulator)
    - 使用BinaryOperator对流进行归约
    - 累加器获取部分结果和下一个元素，并返回新的部分结果
    - 返回可选
    - 其他两个版本
        - 一个带有初始值的(不返回Optional)
        - 带有初始值和BiFunction的值(等效于融合 map 和 reduce)

### Section 6

- Terminal operations provide results or side effects
- Many types of operation available
- Ones like reduceand collectneed to be looked at in more detail
    - We’ll do this in week 3

- 终端操作可提供结果或副作用
- 提供多种操作
- 需要更详细地查看诸如reduce和collect之类的内容
    - 我们将在第3周进行

###### hwxfhhsgneo
###### jdk8mooc_lesson_2-7
## Lesson 2-7:The Optional Class


### The Problems Of null

- Certain situations in Java return a result which is a null
    - Reference to an object that is not initialised

- Java中的某些情况返回的结果为null 
    - 引用未初始化的对象

### Avoiding NullPointerExceptions

```java
    String direction = gpsData.getPosition().getLatitude().getDirection();
 
    String direction = “UNKNOWN”;
    if (gpsData!= null) {
        Position p = gpsData.getPosition();
        if (p != null) {
            Latitude latitude = p.getLatitude();
            if (latitude != null)
            direction = latitude.getDirection();
        }
    }
```    


### Optional Class

Helping To Eliminate the NullPointerException
  
- Terminal operations like min(), max(), may not return a direct result
    - Suppose the input stream is empty?
- Optional<T>
    - Container for an object reference (null, or real object)
    - Think of it like a stream of 0 or 1 elements
    - Guaranteed that the Optionalreference returned will not be null

帮助消除NullPointerException
  
- 终端操作min(), max(),可能不会返回直接结果
    - 假设输入流为空？
- Optional<T>
    - 对象引用的容器(空或真实对象)
    - 将其视为0或1个元素的流
    - 保证返回的Optionalreference不会为空

### Optional ifPresent()

Do something when set   
设置时做些事

    if (x != null) {
        print(x);
    }
    opt.ifPresent(x -> print(x));
    opt.ifPresent(this::print);

### Optional filter()

Reject certain values of the Optional    
拒绝Optional的某些值

    if (x != null && x.contains("a")) {
        print(x);
    }

    opt.filter(x -> x.contains("a"))
        .ifPresent(this::print);

### Optional map()
Transform value if present    
转换值(如果存在)


    if (x != null) {
      String t = x.trim();
        if (t.length() > 0)
        print(t);
    }
    opt.map(String::trim)
        .filter(t -> t.length() > 0)
        .ifPresent(this::print);

### Optional flatMap()

Going deeper    
更深入


    public String findSimilar(String s)
    Optional<String> tryFindSimilar(String s)
    Optional<Optional<String>> bad = opt.map(this::tryFindSimilar);
    Optional<String> similar = opt.flatMap(this::tryFindSimilar);


### Update Our GPS Code


    class GPSData{
        public Optional<Position> getPosition() { ... }
    }
    class Position {
        public Optional<Latitude> getLatitude() { ... }
    }
    class Latitude {
        public String getDirection() { ... }
    }


    String direction = Optional
        .ofNullable(gpsData)
        .flatMap(GPSData::getPosition)
        .flatMap(Position::getLatitude)
        .map(Latitude::getDirection)
        .orElse(“None”)

- Create new Optional with a reference that could be null
- getPosition andgetLatitude returnan Optional
- getDirectionreturns a String
- If getDirection returns a nullreturn "None", otherwise theactual direction

- 使用可能为空的引用创建新的Optional  
- getPosition和getLatitude返回值可选  这里为什么要 flatMap 而不是 Map?
- getDirection返回一个字符串
- 如果getDirection返回null，则返回“ None”，否则返回实际方向

### Section 7
Summary

- Optional class eliminates problems of NullPointerException
- Can be used in powerful ways to provide complex conditional handling

- 可选类消除了NullPointerException问题
- 可以强大的方式用于提供复杂的条件处理

### Lesson 2: Summary
### Lesson 2
Introduction To Streams

- Streams provides a straight forward way for functional style programming in Java
- Streams can either be objects or primitive types
- A stream consists of a source, possible intermediate operations and a terminal operation
    - Certain terminal operations return an Optionalto avoid possible NullPointerExceptionproblems

- Streams为Java中的函数样式编程提供了一种直接的方法
- 流可以是对象或原始类型
- 流由源，可能的中间操作和终端操作组成
    - 某些终端操作返回Optional以避免可能的NullPointerException问题


###### ttii_ibmpcm
###### jdk8mooc_lesson_3-1
## Lesson 3:Advanced Lambda and Stream Concepts
### Lesson Agenda

课程议程

- Understanding and using reductions
- Finite and infinite streams
- Avoiding the use of the forEachmethod
- Using collectors
- Parallel streams (and when not to use them)
- Debugging streams and lambdas
- Course conclusions


- 了解和使用减少量
- 无限和无限的流
- 避免使用forEach方法
- 使用收藏家
- 并行流(以及何时不使用它们)
- 调试流和lambda
- 课程结论

### Lesson 3-1:Understanding and Using Reductions
了解和使用归约

### A Simple Problem

- Find the length of the longest line in a file

    Path input = Paths.get("lines.txt");
    int longestLineLength = Files.lines(input)
            .mapToInt(String::length)
            .max()
            .getAsInt();

### Another Simple Problem

- Find the length of the / longest line in a file
查找最大/长行

### Naïve Stream Solution

天真/原生流解决方案   
 

    String longest = Files.lines(input)
        .sort((x, y) -> y.length() -x.length())
        .findFirst()
        .get();

- This solves the problem
- Not really. Big files will take a long time and a lot of resources
- Must be a better approach


- 这解决了问题
- 并不是的。 大文件将花费很长时间和大量资源
- 必须是更好的方法

Ps。看起来优雅 但是 杀鸡牛刀。没必要全排序

### External Iteration Solution 
外部迭代解决方案

    String longest = "";
    String s;
    while ((s = reader.readLine()) != null)
        if (s.length() > longest.length())
            longest = s;


- Simple, but inherently serial
- Not thread safe due to mutable state
- Not functional

- 简单，但本质上是串行的
- 由于状态可变，线程不安全
- 非函数式

### Recursive Approach: The Method
递归方法：方法
```java
	String findLongestString(String s, int index, List<String> l) {
		if (index >= l.size())
			return s;
		if (index == l.size() - 1) {
			if (s.length() > l.get(index).length())
				return s;
			return l.get(index);
		}


		String s2 = findLongestString(l.get(index), index + 1, l);


		if (s.length() > s2.length())
			return s;
		return s2;
	}
```
Ps.写递归太蠢且不好理解了吧。

### Recursive Approach: Solving The Problem
递归方法：解决问题

```java
List<String> lines = new ArrayList<>();
		String s;
		while ((s = reader.readLine()) != null)
			lines.add(s);
		String longest = findLongestString("", 0, lines);
```        

- No explicit loop, no mutable state, so we now have a functional solution
- Unfortunately not a usable one
    - larger data sets will generate an OOM exception

- 没有显式循环，没有可变状态，所以我们现在有了一个函数式性的解决方案
- 不幸的是不是可用的
    - 较大的数据集将生成OOM异常

不幸的是(这)不是一个适用的(方案)

Ps.递归 栈的问题

### A Better Stream Solution
更好的流解决方案

- The stream API uses the well known filter-map-reduce pattern
- For this problem we do not need to filter()or map(), just reduce()
- Recall the reduce method definition
    Optional<T> reduce(BinaryOperator<T> accumulator)
- The key is to find the right accumulator
    - Again, recall the accumulator takes a partial result and the next element, and returns a new partial result
    - In essence it does the same as our recursive solution
    - Without all the stack frame

- 流API使用众所周知的filter-map-reduce模式
- 对于这个问题，我们不需要filter()或map()，只需要reduce()
- 调用reduce方法的定义    
    Optional<T> reduce(BinaryOperator<T> accumulator)
- 关键是找到合适的accumulator
    - 再次，调用累加器获取部分结果和下一个元素，并返回新的部分结果
    - 本质上，它与我们的递归解决方案相同
    - 没有所有的堆叠框架

- Use the recursive approach as an accumulator for a reduction
- 使用递归方法作为减少量的累加器

```java
    String longestLine = Files.lines(input)
        .reduce((x, y) -> {
			if (x.length() > y.length())
				return x;
			return y;
		}).get();
```

x in effect maintains state for us, by always holding the longest string found so far    
x始终持有迄今为止找到的最长的字符串，实际上为我们保持了状态

### The Simplest Stream Solution
最简单的流解决方案

- Use a specialised form of max()
- 使用特殊形式的max()
- One that takes a Comparatoras a parameter
- 以比较器为参数的

    Files.lines(input)
        .max(comparingInt(String::length))
        .get();

- comparingInt()is a static method on Comparator
- comparingInt() 是Comparator上的静态方法
    - Comparator<T> comparingInt(ToIntFunction<? extends T> keyExtractor)

Ps. max 参数是一个比较器。为什么比较器要这么奇怪? 因为不是函数式接口吗?
 [Comparator (Java Platform SE 8 )](https://docs.oracle.com/javase/8/docs/api/java/util/Comparator.html#comparingInt-java.util.function.ToIntFunction-)
Comparator。也可以手写比较器lamada。但是不如利用现有的组合。各种

(Comparator<T> & Serializable) 这是啥语法

The returned comparator is serializable if the specified function is also serializable.    
如果指定的函数也可序列化，则返回的比较器可序列化。   

这意味着结果值将被强制转换为Comparator 和 Serializable(即可序列化的比较器)


[Chapter 4. Types, Values, and Variables](https://docs.oracle.com/javase/specs/jls/se8/html/jls-4.html#jls-4.4)
[Chapter 5. Conversions and Contexts](https://docs.oracle.com/javase/specs/jls/se8/html/jls-5.html)
[Chapter 15. Expressions](https://docs.oracle.com/javase/specs/jls/se8/html/jls-15.html#jls-15.16)
强制转换可用于显式“标记”具有特定目标类型的lambda表达式或方法引用表达式。为了提供适当的灵活性，目标类型可以是表示交叉点类型的类型的列表，前提是该交叉点会引发功能接口(第9.8节)。




### Section 1
Summary


- Reduction take a stream and reduces it to a single value
- The way the reduction works is defined by the accumulator
    - Which is a BinaryOperator
    - The accumulator is applied successively to the stream elements
    - The reduce()method maintains a partial result state
    - Like a recursive approach, but without the resource overhead
- Requires you to think differently to an imperative, loop based approach


- 减少流量，并将其减少到单个值
- 减少工作的方式由累加器定义
    - 这是BinaryOperator
    - 累加器相继应用于流元素
    - reduce()方法保持部分结果状态
    - 类似于递归方法，但没有资源开销
- 要求您与基于循环的命令式方法有所不同

Ps. 解决了 【Naïve Stream Solution】的问题吗? 性能测试一下。

###### bt5mikrygzm
###### jdk8mooc_lesson_3-2
## Lesson 3-2:Finite and Infinite Streams

有限和无限流

### Dealing With The Indeterminate
Imperative Java

处理不确定性,命令式Java

- How to continue processing when we can't predict for how long?
- 当我们无法预测多长时间时，如何继续处理？
```java
    while (true) {
        doSomeProcessing();
        if (someCriteriaIsTrue())
        break;
        // Loop repeats indefinitely
    }
```

### Using Infinite Streams
Making The Stream Finite  
使流有限  


- Terminate the stream when an element is read from the input stream
    - findFirst()
    - findAny()


    OptionalIntr = Random.ints()
        .filter(i-> i> 256)
        .findFirst();


- Infinite stream of random integers
- stream terminates when a number greater than 256 is encountered 
- 无限的随机整数流
- 当遇到大于256的数字时流终止

Keeping It Infinite  
保持无限  

- Sometimes we need to continue to use a stream indefinitely
- What terminal operation should we use for this?
    - Use forEach()
    - This consumes the element from the stream
    - But does not terminate it


- 有时我们需要无限期地继续使用流
- 为此，我们应该使用哪种终端操作？
     - 使用forEach()
     - 这会消耗流中的元素
     - 但不终止它

Infinite Example    

- Reading temperature from a serial sensor
    - Converting from farenheit to celcius, removing F
    - Notifying a listener of changes if registered

- 从串行传感器读取温度
     - 从 华氏度 转换为 摄氏度 ，删除F
     - 如果注册，通知更改者

```java
    thermalReader.lines()
        .mapToDouble(s -> Double.parseDouble(s.substring(0, s.length() -1)))
        .map(t -> ((t –32) * 5 / 9)
        .filter(t -> !currentTemperature.equals(t))
        .peek(t -> listener.ifPresent(l -> l.temperatureChanged(t)))
        .forEach(t -> currentTemperature.set(t));
```

Ps.
100°C×9/5+32 = 212°F  后面几个变量没有看懂

### Section 2

Summary


- Streams can be infinite as well as finite
- There is no concept of 'breaking' out of a stream
- Use the appropriate terminal operation to stop processing
- Or use the infinite stream infinitely

- 流可以是无限的，也可以是有限的
- 没有 'breaking' 的概念
- 使用适当的终端操作停止处理
- 或无限使用无限流


###### widwt5tjy4e
###### jdk8mooc_lesson_3-3
## Lesson 3-3:Avoiding The Use of forEach
避免使用forEach

### Using Streams Effectively
Stop Thinking Imperatively

有效使用流  停止命令式思考


- Imperative programming uses loops for repetitive behaviour
- It also uses variables to hold state
- We can continue to do that in some ways with streams
- THIS IS WRONG

- 命令式编程使用循环来重复行为
- 它还使用变量来保持状态
- 我们可以继续以某些方式使用流
- 这是错误的

### Stream Example
Still Thinking Imperatively 
依旧命令式思考

```java
    List<Transactions> transactions = ...
    LongAdder transactionTotal = new LongAdder();
    transactions.stream()
        .forEach(t -> transactionTotal.add(t.getValue()));
    long total = transactionTotal.sum();
```

We are modifying  state which is wrong for a functional approach    
我们正在修改状态，这对于函数式方法是错误的   


Now Using Correct Functional Approach
现在使用正确的函数式方法

```java
    List<Transactions> transactions = ...
    long total = transactions.stream()
        .mapToLong(t -> t.getValue())
        .sum();
```
Create a stream of long values that is passed to the next function   
Use a reduction to createa single result   
创建long值流并传递给下一个函数    
使用归约法创建单个结果    


### Legitimate Use of forEach

合理使用forEach    
No State Being Modified    
没有状态被修改  


- Simplified iteration
- May be made parallel if order is not importantNo State Being Modified
- 简化迭代
- 如果顺序不重要，则可以并行进行-没有修改状态

    List<Transactions> transactions = ...
    transactions.stream()
    .forEach(t -> t.printClientName());

### Section 3

Summary


- If you are thinking of using forEach(), stop
- Can it be replaced with a combination of mapping and reduction?
- If so, it is unlikely to be the right approach to be functional
- Certain situations are valid for using forEach()
- E.g. printing values from the stream


- 如果您正在考虑使用forEach()，请停止
- 是否可以通过映射和归约的组合来代替？
- 如果是这样，则不太可能是正确的方法来发挥作用
- 某些情况对于使用forEach()有效
- 例如 从流中打印值

###### 1xwuimh_rh0
###### jdk8mooc_lesson_3-4
## Lesson 3-4:Using Collectors

### Collector Basics


- A Collectorperforms a mutable reduction on a stream
    - Accumulates input elements into a mutable result container
    - Results container can be a List, Map, String, etc
- Use the collect()method to terminate the stream
- Collectorsutility class has many methods that can create a Collector

- 收集器对流执行可变的减少
    - 将输入元素累积到可变结果容器中
    - 结果容器可以是列表，地图，字符串等
- 使用collect()方法终止流
- Collectorsutility类具有许多可以创建收集器的方法

### Composing Collectors


- Several Collectorsmethods have versions with a downstream collector
- 一些收集器方法的版本带有下游收集器
- Allows a second collector to be used
- 允许使用第二个收集器
    - collectingAndThen()
    - groupingBy()/groupingByConcurrent()
    - mapping()
    - partitioningBy()

 ### Collecting Into A Collection

- toCollection(Supplier factory)
    - Adds the elements of the stream to a Collection(created using factory)
    - 将流的元素添加到Collection(使用工厂创建)
    - Uses encounter order
    - 使用遭遇顺序
- toList()
    - Adds the elements of the stream to a List
    - 将流的元素添加到列表
- toSet()
    - Adds the elements of the stream to a Set
    - 将流的元素添加到集合中
    - Eliminates duplicates
    - 消除重复


 
 ### Collecting To A Map
 - toMap(Function keyMapper, Function valueMapper)
    - Creates a Mapfrom the elements of the stream
    - 从流的元素创建一个Map
    - key and value produced using provided functions
    - 使用提供的功能产生的 key 和 value
    - Use Functions.identity()to get the stream element
    - 使用Functions.identity()获取流元素
 
 

    Map<Student, Double> studentToScore = students.stream()
        .collect(toMap(Functions.identity(),
            student -> getScore(student)));


Handling Duplicate Keys  
处理重复的keys      


toMap(Function keyMapper, Function valueMapper, BinaryOperator merge)

- The same process as first toMap()method
    - But uses the BinaryOperatorto merge values for duplicate keys

```java
    Map<String, String> occupants = people.stream()
        .collect(toMap(Person::getAddress,
                    Person::getName,
                    (x, y) -> x + "," + y));
```

People at the same address are merged into a CSV string   
位于同一地址的人将合并为CSV字符串

### Grouping Results
- groupingBy(Function)
    - Groups stream elements using the Functioninto a Map
    - Result is Map<K, List<V>>

    Map m = words.stream()
        .collect(Collectors.groupingBy(String::length));

- groupingBy(Function, Collector)
    - Groups stream elements using the Function
    - 使用功能对流元素进行分组
    - A reduction is performed on each group using the downstream Collector
    - 使用下游收集器对每个组执行减少操作

    Map m = words.stream()
        .collect(Collectors.groupingBy(String::length, counting()));

### Joining String Results
- joining()
    - Collector concatenates input strings
    - 收集器连接输入字符串
- joining(delimiter)
    - Collector concatenates stream strings using CharSequence delimiter
    - 收集器使用CharSequence分隔符连接流字符串

    collect(Collectors.joining(",")); // Create CSV

- joining(delimiter, prefix, suffix)
    - Collector concatenates the prefix, stream strings separated by delimiter and suffix
    - 收集器将前缀，流字符串连接在一起，并用定界符和后缀分隔

### Numeric Collectors
Also Available In Double And Long Forms    
也有Double和Long形式  


- averagingInt(ToIntFunction)
    - Averages the results generated by the supplied function
    - 平均提供的函数产生的结果
- summarizingInt(ToIntFunction)
    - Summarises (count, sum, min, max, average) results generated by supplied function 
    - 汇总(计数，总和，最小值，最大值，平均值)由提供的函数生成的结果
- summingInt(ToIntFunction)
    - equivalent to a map()then sum()
    - 等同于map()然后sum()
- maxBy(Comparator), minBy(Comparator)
    - Maximum or minimum value based on Comparator
    - 基于比较器的最大值或最小值

### Other Collectors



- reducing(BinaryOperator)
    - Equivalent Collector to reduce() terminal operation
    - 等效的Collector来 reduce() 终端操作
    - Only use for multi-level reductions, or downstream collectors
    - 仅用于多级还原或下游收集器
- partitioningBy(Predicate)
    - Creates a Map<Boolean, List>containing two groups based on Predicate
    -根据Predicate创建一个包含两个组的 Map<Boolean, List>
- mapping(Function, Collector)
    - Adapts a Collector to accept different type elements mapped by the Function
    - 使收集器适应接受函数映射的不同类型的元素
 

```java
    Map<City, Set<String>> lastNamesByCity = people.stream()
        .collect(groupingBy(Person::getCity,
            mapping(Person::getLastName, toSet())))
```

### Section 4
Summary


- Collectors provide powerful ways to gather elements of an input stream
    - Into collections
    - In numerical ways like totals and averages
- Collectors can be composed to build more complex ones
- You can also create your own Collector

- Collector提供了强大的方法来收集输入流的元素
    - 进入collections
    - 以总计和平均值之类的数字方式
- 可以组成收集器以构建更复杂的Collector
- 您也可以创建自己的Collector

###### lfnnpfmbice
###### jdk8mooc_lesson_3-5   
## Lesson 3-5:Parallel Streams(And When Not To Use Them)
 并行流(以及何时不使用它们)

### Serial And Parallel Streams

串行和并行流

- Collection stream sources
    - stream()
    - parallelStream()
- Stream can be made parallel or sequential at any point
    - parallel()
    - sequential()
- The last call wins
    - Whole stream is either sequential or parallel
- Calling concat()with a sequential and parallel stream will produce a parallel stream

- 集合流源
    - stream()
    - parallelStream()
- 可以在任何点将流设为并行或顺序
    - parallel()
    - sequential()
- 最后一次调用获胜
    - 整个流是顺序的或并行的
- 使用顺序和并行流调用 concat()将产生并行流

### Parallel Streams

- Implemented internally using the fork-join framework
- Will default to as many threads for the pool as the OS reports processors
    - Which may not be what you want
    
    System.setProperty("java.util.concurrent.ForkJoinPool.common.parallelism", "32767");

- Remember, parallel streams always need more work to process
    - But they might finish it more quickly



- 使用fork-join框架在内部实现
- 默认情况下，池中的线程数将与操作系统报告处理器的数量相同
    - 可能不是您想要的
    
    System.setProperty("java.util.concurrent.ForkJoinPool.common.parallelism", "32767");

- 请记住，并行流始终需要处理更多工作
    - 但是他们可能会更快完成


### Parallel Stream Considerations
并行流注意事项

- findFirst()and findAny()
    - findAny()is non-deterministic, so better for parallel stream performance
    - Use findFirst()if a deterministic result is required
- forEach()and forEachOrdered()
    - forEach()is non-deterministic for a parallel stream and ordered data
    - Use forEachOrdered()if a deterministic result is required
 

- findFirst()和findAny()
    - findAny()是不确定的，因此对并行流性能更好
    - 如果需要确定性结果，请使用findFirst()
- forEach()和forEachOrdered()
    - forEach()对于并行流和有序数据是不确定的
    - 如果需要确定性结果，请使用forEachOrdered()

### When To Use Parallel Streams

没有简单的答案

- Data set size is important, as is the type of data structure
    - ArrayList: GOOD
    - HashSet, TreeSet: OK
    - LinkedList: BAD
- Operations are also important
    - Certain operations decompose to parallel tasks better than others
    - filter()and map()are excellent
    - sorted()and distinct()do not decompose well

- 数据集的大小以及数据结构的类型都很重要
    - ArrayList：良好
    - HashSet，TreeSet：可以
    - LinkedList：不良
- 操作也很重要
    - 某些操作比其他操作更好地分解为并行任务
    - filter()和map()非常好
    - sorted()和distinct()分解不好


### When To Use Parallel Streams

定量考虑

- N = size of the data set
- Q = Cost per element through the Stream pipeline
- N x Q = Total cost of pipeline operations
- The bigger N x Q is the better a parallel stream will perform
- It is easier to know N than Q, but Q can be estimated
- If in doubt, profile

- N =数据集的大小
- Q =通过Stream管道的每元素成本
- N x Q =管道运营总成本
- N x Q越大，并行流的性能越好
- 知道N比Q容易，但是可以估计Q
- 如有疑问，profile


### Section 5
Summary

- Streams can be processed sequentially or in parallel
    - The whole stream is processed in sequentially or in parallel
    - In most cases how the stream is defined will not affect the result
    - findFirst(), findAny(), forEach(), forEachOrdered()do
- Don’t assume that a parallel stream will return a result faster
    - Many factors affect performance

- 流可以顺序或并行处理
    - 整个流按顺序或并行处理
    - 在大多数情况下，流的定义方式不会影响结果
    - findFirst(), findAny(), forEach(), forEachOrdered()do
- 不要以为并行流会更快地返回结果
    - 许多因素都会影响效果


###### krltmsteyoo
###### jdk8mooc_lesson_3-6
## Lesson 3-6:Debugging Lambdas and Streams
### Problems With Debugging Streams

- Streams provide a high level abstraction
    - This is good for making code clear and easy to understand
    - This is bad for debugging
        - A lot happens internally in the library code
        - Setting breakpoints is not simple
        - Stream operations are merged to improve efficiency

- 流提供高级抽象
    - 这有助于使代码清晰易懂
    - 这对调试不利
        - 库代码内部发生了很多事情
        - 设置断点并不简单
        - 合并流操作以提高效率

### Simple Debugging
Finding What Is Happening Between Methods    
查找方法之间发生的事情   
- Use peek()
    - Like the use of print statements
```java
List<String> sortedWords = reader.lines()           // Lines from file
    .flatMap(line -> Stream.of(line.split(REGEXP))  // Words from file
    .map(String::toLowerCase)                       // In lower case
    .distinct()                                     // Remove duplicates
    .sort((x, y) -> x.length() –y.length())         // Sort by length
    .collect(Collectors.toList());                  // Collect to list
  
List<String> sortedWords = reader.lines()           // Lines from file
    .peek(System.out::println)                      // Print lines from file
    .flatMap(line -> Stream.of(line.split(REGEXP))  // Words from file
    .map(String::toLowerCase)                       // In lower case
    .distinct()                                     // Remove duplicates
    .sort((x, y) -> x.length() –y.length())         // Sort by length
    .collect(Collectors.toList());                  // Collect to list


List<String> sortedWords = reader.lines()           // Lines from file
    .flatMap(line -> Stream.of(line.split(REGEXP))  // Words from file
    .peek(System.out::println)                      // Print words
    .map(String::toLowerCase)                       // In lower case
    .distinct()                                     // Remove duplicates
    .sort((x, y) -> x.length() –y.length())         // Sort by length
    .collect(Collectors.toList());                  // Collect to list

```

### Setting A Breakpoint
Using peek()


- Add a peek()method call between stream operations
- Use a Consumerthat does nothing if required
    - Some debugging tools don’t like empty bodies

- 在流操作之间添加peek()方法调用
- 使用不需要的消费者
    - 一些调试工具不喜欢空体

```java
    list<String> sortedWords = reader.lines()
        .flatMap(line -> Stream.of(line.split(REGEXP))
        .peek(s -> s)//Set breakpoint here//No-op Lambda
        .map(String::toLowerCase)
        .distinct()
        .sort((x, y) -> x.length() –y.length())
        .collect(Collectors.toList());
```

Using A Method Reference


- Lambda expressions do not compile to equivalent inner class
    - Compiled to invokedynamic call
    - Implementation decided at runtime
    - Better chance of optimisation, makes debugging harder
- Solution:
    - Extract the code from a Lambda expression into a separate method
    - Replace the Lambda with a method reference for the new method
    - Set breakpoints on the statements in the new method
    - Examine program state using debugger

- Lambda表达式无法编译为等效的内部类
    - 编译为调用动态调用
    - 在运行时决定实现
    - 更好的优化机会，使调试更加困难
- 解决方案：
    - 将Lambda表达式中的代码提取到单独的方法中
    - 将Lambda替换为新方法的方法引用
    - 在新方法中的语句上设置断点
    - 使用调试器检查程序状态


### Section 6
Summary


- Debugging is harder with Lambdas and streams
    - Stream methods get merged
    - Lambdas are converted to invokedynamic bytecodes and implementation is decided at runtime
    - Harder to set breakpoints
- peek()and method references can simplify things

- 使用Lambda和流进行调试更加困难
    - 流方法合并
    - 将Lambda转换为invokedynamic字节码，并在运行时确定实现
    - 难以设置断点
- peek()和方法引用可以简化操作


###### qnnysqvzs
###### jdk8mooc_lesson_3-7
## Lesson 3-7:Course Conclusions
课程总结

### Lambda Expressions


- Lambda expressions give us a simple way to define behaviour
    - Can be assigned to a variable or passed as a parameter
- Can be used wherever the type is a functional interface
    - One that has only one abstract method
    - The lambda expression provides an implementation of the abstract method

- Lambda表达式为我们提供了一种定义行为的简单方法
    - 可以分配给变量或作为参数传递
- 可以在类型为功能接口的任何地方使用
    - 一种只有一种抽象方法
    - lambda表达式提供了abstract方法的实现

### Stream API

- Pipeline of operations to process collections of data
    - Multiple sources, not just from the Collections API
    - Can be processed sequentially or in parallel
- Sources, intermediate and terminal operations
- Behaviour of intermediate and terminal operations often defined using Lambda expressions
- Terminal operations often return an Optional
- We can now use a functional style of programming in Java

- 处理数据收集的操作流水线
    - 多种来源，而不仅仅是来自Collections API
    - 可以顺序或并行处理
- 源，中间和终端操作
- 通常使用Lambda表达式定义的中间操作和最终操作的行为
- 终端操作通常返回Optional
- 现在我们可以使用Java中的函数式编程

### Lambdas And Streams: Think Differently


- Need to think functional rather than imperative
    - Try to stop thinking in loops and using mutable state
- Think of how to approach problems using recursion
    - Rather than an explicit loop
    - Avoid forEach(except for special cases)
- Infinite streams don't need to be infinite
- Remember, parallel streams always involve more work
    - Sometimes they complete the work quicker

- 需要思考功能而非命令
    - 尝试停止循环思考并使用可变状态
- 考虑如何使用递归来解决问题
    - 而不是显式循环
    - 避免forEach(特殊情况除外)
- 限流不必无限
- 请记住，并行流始终涉及更多工作
    - 有时他们可以更快地完成工作

Thank You!This Is The End OfThe Course


