# ssm知识点总结

## Spring
**Spring** 是一个轻量级的企业级应用开发框架，于2004年由 Rod Johnson 发布了1.0 版本，经过多年的更新迭代，已经逐渐成为 Java 开源世界的第一框架，Spring 框架号称 Java EE 应用的一站式解决方案，与各个优秀的 MVC 框架如 SpringMVC、Struts2、JSF 等可以无缝整合，与各个 ORM 框架如 Hibernate、MyBatis、JPA 等也可以无缝衔接，其他各种技术也因为 Spring 的存在而被很容易地整合进项目开发之中，如 Redis 整合、Log4J 整合、ElasticSearch 整合、RabbitMQ 整合、Quartz 整合、Thymeleaf 整合等等，只要你开发中需要使用到的技术，Spring 都提供了极好的封装和整合体验，这也是为何 Spring 生命力如此强大的原因，暂时还没有能够替代 Spring 的框架出现。

    Spring 框架的优点：
    * Spring 的 IOC 容器将对象之间的依赖关系交由 Spring 控制，提高了组件之间的解耦，简化 Java 开发
    * 避免大量的代码重复，使得代码更加简洁，复用性更强，也帮助开发人员更加关注业务逻辑
    * 非侵入式，代码的污染极低
    * 无与伦比的兼容性，与其他优秀的第三方框架无缝整合
    * Spring 框架的源码是无与伦比的 Java 代码盛宴
    * 高度的开放性
    * 开源社区十分活跃，文档齐全，学习成本不高

## SpringMVC
**SpringMVC** 是 Spring 框架体系中的全功能 MVC 模块，在前面 Spring 结构图中可以看到这一关系，其中的 Web MVC 即 SpringMVC。SpringMVC 是基于 Java 语言实现 MVC 设计模式的请求驱动类型的轻量级 Web 框架，目的是将 Web 开发模块化及代码简化。其提供了 DispatcherServlet 前端控制器分派请求，同时提供灵活的配置处理程序映射、视图解析，并支持文件上传，目前已经是众多 MVC 框架中的佼佼者。

    SpringMVC 框架的优点如下：
    * Spring 和 SpringMVC 无需复杂的操作即可整合，天生契合，灵活度高，非侵入性
    * 配置简单，学习成本低
    * 设计合理，各模块分工明确，功能强大
    * 非常容易与第三方视图技术集成整合
    * 能够进行 Web 层的单元测试
    * 支持灵活的 URL 到页面控制器的映射
    * 灵活且强大的数据验证、格式化和数据绑定机制
    * 开源社区十分活跃，文档齐全

## MyBatis
**MyBatis** 的前身是 Apache 社区的一个开源项目 iBatis，于2010年更名为 MyBatis。MyBatis 是支持定制化 SQL、存储过程以及高级映射的优秀的持久层框架，避免了几乎所有的 JDBC 代码和手动设置参数以及获取结果集，使得开发人员更加关注 SQL 本身和业务逻辑，不用再去花费时间关注整个复杂的 JDBC 操作过程。

    MyBatis 的优点如下：
    * 封装了 JDBC 大部分操作，减少开发人员工作量
    * 相比一些自动化的 ORM 框架，“半自动化”使得开发人员可以自由的编写 SQL 语句，灵活度更高
    * Java 代码与 SQL 语句分离，降低维护难度
    * 自动映射结果集，减少重复的编码工作
    * 开源社区十分活跃，文档齐全，学习成本不高
