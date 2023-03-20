**背景**  
&emsp;&emsp;工作流是企业数字化转型中的一项基础核心技术，被广泛用在OA、ERP、各类企业信息管理系统和低代码平台中，开源界也有一些优秀的工作流引擎，不过都是国外的，由于文化差异等原因，国外的Activiti、Flowable、Camunda并不能满足国内企业级工作流需要。彭彭看过不少基于国产商业的、国外开源的、自己简单实现的五花八门的工作流实现源码，写得非常之“感人”。 悟已往之不谏，知来者之可追，于是开始利用休息时间开始自己写了一套开源工作流，如此便有了MoextFlow。  
&emsp;&emsp;你可以把MoextFlow当项目工作流引擎使用，也可以把它当企业工作流中台用，还可以把它当低代码平台使用。  
    
**简介**  
&emsp;&emsp;MoextFlow是基于SpringBoot的国产开源工作流系统，易读易懂、界面简洁美观。 核心技术采用Spring、MyBatis、Flowable没有任何其它重度依赖。直接运行即可用。  
开发语言：Java  
数据库：Mysql5.7及以上版本  
Maven：3.0及以上版本  
JDK版本：JDK1.8及以上版本  

**功能描述：**  
1、架构简单，仅Java应用+Mysql，不依赖任何中间件；  
2、可伸缩性，支持分布式，可通过部署多个实例支撑高并发请求；  
3、符合中国式审批工作流，支持会签、加签、退回等常用符合国内操作习惯的工作流功能；  
4、与业务系统彻底的解耦设计；  
