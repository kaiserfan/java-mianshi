# java面试汇总

苏宁、华泰证券部分面试题，仅供参考

# 一、Spring
1、谈谈自己对SpringAOP和IOC的理解，核心机制、原理及项目中的运用。

2、Spring上下文的加载方式有哪些？

3、以往项目中是如何对事务进行管理的？

4、Autowired和resource的区别？

5、使用SpringBoot和以往的SSM有什么不同，为什么要选用SpringBoot？

6、谈谈SpringCloud和Dubbo？


7、描述一下SpringMVC的工作流程。其包含哪4个主要组件？

8、描述一下bean的生命周期和加载过程。

9、在什么情况下事务会进行回滚？

10、描述一下AOP的代码实现？

# 二、Mybatis
1、例举Mybatis里的常用标签。

2、Mybatis二级缓存？

3、#和$有什么不同，两者分别在什么场景下使用？

4、#底层是如何实现防止SQL注入的？如果不用Mybaits你会通过什么方式实现防止SQL注入？


# 三、Java集合类
1、List和Set集合的区别？

2、ArrayList的加载因子，默认容量和扩容增量是多少？是容量不够了还是快不够了进行扩容？

3、谈谈HashMap的元素碰撞？如何解决hash冲突。

4、怎么去删除ArrayList中不符合条件的元素？

5、Java线程安全的集合是通过什么手段实现线程安全的？

6、有什么其他方法可代替synchronized实现线程安全类。

7、HashMap除了使用链表，还使用到了什么数据结构？

答：通过使用comparator或者comparable方法。

9、HashTable和HashMap的区别？

10、常用集合介绍？

11、map下有哪些线程安全的集合？

12、hashmap的get和put原理是什么？

13、有看过concurrentHashMap的源码吗？它是如何保证线程安全的？

# 四、多线程
1、对多线程的理解？多线程的作用是什么？多线程为什么要使用线程池（好处/优点）。在所作项目中什么场景会用到？

2、如何获取线程的返回值？

3、谈谈对乐观锁和悲观锁的理解

4、谈一谈Lock锁，lock和synchronized的区别？

5、线程池的作用。

6、Java线程池有哪几种？各有什么特性？


7、多个线程如何共享变量？

8、wait()和sleep()的区别？

9、如何唤醒一个线程？

10、怎么保证T1执行完后执行T2？

11、有用过CountdownLatch()方法吗？

13、悲观锁除了synchronized还有哪些？

14、乐观锁的缺点？

15、synchronized有哪几种使用方式？

16、Volatile和synchronized的区别？

17、当线程池中的线程最大数为10，并发的请求数是100，那么有效的请求是多少？

18、ThreadLocal和Synchronized的区别？

19、线程的生命周期？

20、实现线程安全的方式有哪些？实现线程同步的方式有哪些？

21、乐观锁是怎么实现的？谈谈CAS

# 五、JVM
1、描述JVM类加载机制（过程）。

2、JVM原理

3、垃圾回收原理

4、谈谈JVM的新生代、老年代、永久代。

5、谈谈JVM运行数据区？

6、stack堆栈的使用？

7、什么叫内存泄漏（memory leak）、内存溢出（out of memory）？

8、JVM有哪几种GC回收器？

# 六、MySQL
1、MySQL常用存储引擎有哪些，都分别有哪些特性。

2、InnoDB是行锁还是页锁？

3、谈一下以往工作中对SQL优化的策略措施。

4、查询出各班成绩前五名的学生（MySQL）。

5、Having的作用和用法?

6、索引的原理

7、为什么有主键索引却还有唯一索引，两者的区别是什么？

8、索引的数据结构了解吗？

10、谈谈联合索引，如何实现？

11、MySQL默认的隔离级别？

12、MySQL怎么实现全文检索查询。

13、事务的四大基本要素是什么？

15、数据库那些地方需要优化

16、Mysql锁有哪些？发生死锁怎么解决？

17、MySQL索引哪些情况下会失效？

18、什么是存储过程？优缺点？和函数比较

19、union和union all的区别？

20、对于MySQL你是怎么去进行SQL优化的？选用什么工具？

# 七、Dubbo
1、Dubbo是怎么进行监控的？

2、描述一下Dubbo的实现原理？


# 八、Tomcat
1、Tomcat启动后，Web项目的加载顺序？

2、Tomcat优化

# 九、其他
1、java常用数据类型有哪些？

2、讲一下java的反射？

3、前后端是通过什么协议通信的？HTTP或Socket

4、有哪些常见的io流？

5、常用设计模式有哪些？

6、谈谈静态代理、JDK动态代理、CGlib代理

7、ibatis和hibernate的区别？

8、抽象类和接口的区别？

9、什么是第三方支付？

10、String、StringBuilder、StringBuffer的区别？

11、冒泡排序算法的实现

14、HTTP和HTTPS的区别？

15、怎么防范redis缓存穿透

16、Redis用过哪些数据结构？

17、数据库的数据存储在哪儿？

17、了解jar包热加载及隔离技术吗？

18、谈谈你对分布式的理解？

19、例举Linux的常用命令及功能？

20、BIO、NIO、AIO的区别？

21、Redis为什么采用单线程？

22、容器是什么结构（如Spring和Tomcat容器）？

23、Linux支持的最大线程数是多少？

24、分布式锁的实现方式有哪几种？如何实现？

25、Redis有几种部署方式？各有什么优缺点？

26、redis同步锁实现原理？

26、redis分片知道吗？

27、Netty与Java NIO的对比？

28、现在正在看的有哪几本书？

29、用过的Java构建工具有哪些？Gradle是什么语言开发的？

30、通过RMI接口作为分布式请求调用转发，用的是什么协议？TCP、UDP、Socket还是HTTP？

31、JDK1.7在JDK1.6基础上有哪些不同？

32、Redis有哪几种持久化方式？各有什么特性，项目中运用到哪种持久化方式？

33、你作为架构师的话，会考虑如何架构设计一个系统？

