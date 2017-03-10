# 项目说明
自建`SSM`脚手架(Maven),`借鉴github,oschina社区热门框架`,集成最优秀的`mybatis工具(Mapper,PageHelper)`
框架简单目标是使用当下流行优秀的套件组合,适合新项目的快速开发,精小稳定。
另一面,适应`前后端分离`的服务端框架.

# 技术组成
- 核心框架：Spring Framework 4.1
- 安全框架：Apache Shiro 1.2
- 视图框架：Spring MVC 4.1
- 服务端验证：Hibernate Validator 5.2
- 布局框架：SiteMesh 2.4
- 工作流引擎：Activiti 5.21
- 任务调度：Spring Task 4.1
- 持久层框架：MyBatis 3.2
- 数据库连接池：Alibaba Druid 1.0
- 缓存框架：Ehcache 2.6、Redis
- 日志管理：SLF4J 1.7、Log4j
- 工具类：Apache Commons、Jackson 2.2、Xstream 1.4、Dozer 5.3、POI 3.9

- Mybatis工具
    - Mapper
    - Mybatis_PageHelper
    - MyBatis Generator

- 前端(从此项目中分离出来)`前后端分离`
    - angular / Vue / React /jquery + Bootstrap
    
# 搭建初始,使用
- Maven pom.xml初始化`dependencies`
- tomcat部署`bright:war exploded`
- 首页预览
    - 数据访问demo
    - 一.webService接口访问(返回json)
    - 二.动静态访问各位置页面差异

![](http://7xnbs3.com1.z0.glb.clouddn.com/17-3-10/7456180-file_1489145685391_18024.png)
![](http://7xnbs3.com1.z0.glb.clouddn.com/17-3-10/54366383-file_1489145789988_15fb7.png)

# 框架借鉴
- [`ThinkGem / JeeSite`](https://git.oschina.net/thinkgem/jeesite)
- [` 人人开源 / renren-security`](https://git.oschina.net/babaio/renren-security)
- [`abel533/Mybatis-Spring`](https://github.com/abel533/Mybatis-Spring)
    - [`abel533/Mapper`](https://github.com/abel533/Mapper)
    - [`abel533 / Mybatis_PageHelper`](http://git.oschina.net/free/Mybatis_PageHelper)

- 其它
    - [`iBase4J / iBase4J`](https://git.oschina.net/iBase4J/iBase4J)
    - [`青苗 / SpringWind`](https://git.oschina.net/juapk/SpringWind)
    
# 查阅
- MyBatis Generator相关
    - [MyBatis Geneator详解 abel533 / Mybatis_Utils](http://git.oschina.net/free/Mybatis_Utils/blob/master/MybatisGeneator/MybatisGeneator.md)
    - [使用Mapper专用的MyBatis Generator插件](http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/7.UseMBG.md)
    - [在Spring4中使用通用Mapper](http://git.oschina.net/free/Mapper2/blob/master/wiki/mapper/4.Spring4.md)
    - [mybatis-generator界面工具 astarring/mybatis-generator-gui](https://github.com/astarring/mybatis-generator-gui)

# 作者信息
- 作者博客：http://liuxiang.github.io