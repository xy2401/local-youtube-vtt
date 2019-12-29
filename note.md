




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