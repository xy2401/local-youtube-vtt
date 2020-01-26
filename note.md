




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
- 函数调用，依次调用其他函数（组成）
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
    - 新值可能通过重复（循环）与相同名称相关联
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
        - 短路操作（例如findFirst）
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
###### pbtfl7t_hlw
###### jdk8mooc_lesson_2-4
###### 2eir0u78_ga
###### jdk8mooc_lesson_2-5   
###### 4jjxu8a6cuy
###### jdk8mooc_lesson_2-6
###### hwxfhhsgneo
###### jdk8mooc_lesson_2-7
###### ttii_ibmpcm
###### jdk8mooc_lesson_3-1
###### bt5mikrygzm
###### jdk8mooc_lesson_3-2
###### widwt5tjy4e
###### jdk8mooc_lesson_3-3
###### 1xwuimh_rh0
###### jdk8mooc_lesson_3-4
###### lfnnpfmbice
###### jdk8mooc_lesson_3-5   
###### krltmsteyoo
###### jdk8mooc_lesson_3-6
###### qnnysqvzs
###### jdk8mooc_lesson_3-7