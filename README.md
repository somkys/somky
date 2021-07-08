1. 简介一下Spring框架。

答：Spring框架是一个开源的容器性质的轻量级框架。主要有三大特点：容器、IOC（控制反转）、AOP（面向切面编程）。

 

2. Spring框架有哪些优点？谈谈你的看法。

答：Spring框架主要有三大优点：

(1) 容器。Spring框架是一个容器，能够管理项目中的所有对象。

(2) IOC（控制反转）。Spring将创建对象的方式反转了，从程序员自己创建反转给了程序。

(3) AOP（面向切面）。面向切面编程，简而言之，就是将纵向重复的代码横向抽取出来。Spring框架应用了面向切面的思想，主要体现在为容器中管理的对象生成动态代理对象。

 

3. 什么是IOC？

答：IOC：控制反转，指得是将对象的创建权反转给Spring。作用是实现了程序的解耦合。、

 

4. 什么是DI？

答：DI：依赖注入，需要有IOC环境，在Spring创建Bean对象时，动态的将依赖对象注入到Bean对象中去。依赖注入最大的好处就是解耦合。

 

5. 你对Spring框架中的BeanFactory接口和ApplicationContext接口有什么理解？二者有什么区别？

答：BeanFactory接口是Spring框架的顶层接口，是最原始的接口，通过new （BeanFactory的实现类）来启动Spring容器时，并不会创建Spring容器里面的对象，只有在每次通过getBean()获得对象时才会创建。

ApplicationContext接口是用来替代BeanFactory接口的，通过new （ApplicationContext接口的实现类）ClassPathXmlApplicationContext来启动Spring容器时，就会创建容器中配置的所有对象。
