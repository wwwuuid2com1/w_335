# w_335
asp.net EF+MVC+Bootstrap通用后台管理系统源码
<br/></br>
[下载地址](https://www.uuid2.com/335.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>asp.net EF+MVC+Bootstrap通用后台管理系统源码，集成轻量级的缓存模块、日志模块、上传缩略图模块、通用配置及服务调用，提供了OA、CRM、CMS的原型实例，适合快速构建中小型互联网及行业Web系统<p>
<p>基于EF+MVC+Bootstrap的通用后台管理系统<p>
<p>Framework 业务无关的底层通用机制及功能
Model基类：提供数据传输和底层的最基本的基类及接口
DAL底层：基于EF code first，提供Repository泛型方法及写历史日志
Untility：通用函数库，基本都全了
Web：复写MVC基类，及通用MVC控件

通用模块Core 核心功能模块，包括缓存管理，配置管理，日志管理，服务管理......
缓存模块：提供对分布式缓存的Provider扩展
配置模块：基于正则的配置管理及CURD机制
日志模块：基于Log4net扩展
服务模块：默认使用引用Bll，可扩张调用Wcf服务，且拦截服务
上传模块：通用upload handler，及缩略图生成方式（按需生成，即时生成，延迟生成）
管道模块：通用HttpModule，用于注入通用功能到各个应用及网站

应用模块三层架构 提供OA,CMS,CRM系统的原型及DAL,IBLL及BLL实现
Account：用户认证，可自己扩张到SSO单点登录
Account: 安全验证码实现
Account: 轻量级权限系统
OA：提供OA里人员，部门管理及分配的场景实例
CRM：客户管理系统原型
CMS：内容发布系统原型

数据层(DAL)：
采用Code first POCO方式
提供实体设计：一对一，一对多，多对多，自引用的各种使用场景

业务逻辑层(BLL)：
实现CURD方法
提供复杂查询场景
提供业务异常抛出
对后端异常进行拦截写日志
对写操作进行写历史，用于追踪
IBLL：
服务接口，可扩展用WCF发布BLL作为服务

前端框架及实现 MVC,Bootstrap..........
基于Bootstrap：基于“Metronic Bootstrap Theme”模板
MVC 4.0：CURD操作基于MVC Model Binder
Silverlight 5：OA里组织图OrgChart拖拽操作
封装Context：封装ConfigContext,CacheContext,UserContext,CookieContext..
上传控件：Uploadify使用实例
Jquery：除Metronic模板在Assets文件夹，Content文件夹加入需要的Jquery插件
提供富文本编辑器，标签，JS曲线图等实例

源码其部署
平台：VS2010+，Sql Server, MVC4，Silverlight5_Tools(可选)
脚本部署：新建右图5个库，并执行源码里的Deploy.sql初始化表和数据
配置更改：更改GMS.Web.Admin\Config\DaoConfig.xml下的数据库连接字符串
启动：VS IIS Express或建立IIS对应网站（主网站项目GMS.Web.Admin）<p>
<p>登录：初始化用户名：admin 密码：111111<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202105/23dc660279.jpg" alt="asp.net EF+MVC+Bootstrap通用后台管理系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/2ee8f1d673.jpg" alt="asp.net EF+MVC+Bootstrap通用后台管理系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/13897ca578.jpg" alt="asp.net EF+MVC+Bootstrap通用后台管理系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/27977c9568.jpg" alt="asp.net EF+MVC+Bootstrap通用后台管理系统源码">
