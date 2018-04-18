# 个人信息

 - 许啸/男/1991 
 - 本科/南京农业大学
 - 专业/计算机科学与技术 
 - 工作年限：4年
 - Github：[https://github.com/AppOrGameDev](https://github.com/AppOrGameDev) 
 - 期望职位：JAVA高级工程师
 - 期望城市：南京


# 联系方式

- 手机：18751909082 
- Email：584778582@qq.com 
- QQ/微信号：xuxiao403 
- 个人微信二维码

![扫码加好友](/pic/WeiXin.jpg "请扫描二维码联系我")


# 技能清单
- 数据库相关：Oracle
- 版本管理、文档和自动化部署工具：Svn/Git



# 工作经历


## 亚信科技（中国）有限公司 （ 2016年6月 ~ 至今 ）

### 浙江移动中心化项目组中的家庭订单中心和个人订单中心项目
亚信科技 | JAVA研发工程师
项目名称：浙江移动中心化项目
工作描述：
（1）个人订单中心项目主要就是将个人业务从浙江CRM的大项目中解耦出来，期间我们是用git做代码版本控制，maven管理项目依赖以及项目构建，自动化持续集成采用ADCloud平台，解耦主要采用CSF和消息两种方式跟外围系统交互。

（2）浙江移动中心化项目采用ActiveMQ消息中间件，跑业务流程中需要将订单信息通过发布订阅的模式来送计费，送开通，送账管，送到期提醒，以及二次确认。由个人中心产生一份订单数据，发送到消息中间件的虚拟主题上，多个外围中心的消费者消费完消息后，也业务才会流转成功。也有后台进城TF,TASK生成工单，通过消息发给其他系统，通过进程-消息-进程的模式推动业务在多中心之间的流转。同时为了开发和测试跟踪消息，也配置了消息重发，重消费，消息发送记录，消息消费记录，消息异常记录，消息重试记录。

（3）浙江移动中心化项目也引入了ADCloud敏捷交付云平台，支撑了第三代架构中心化项目，浙江移动CRM单体复杂系统，以及浙江地市公司的系统。支持多系统多流水线（开发，测试，准发布，生产）的持续交付。满足项目交付流水上代码分支，编译打包，构建发布环节的可视化配置，针对不同开发测试生产环境的打包部署需求。提供基于应用访问链路的完整环境拓扑监控，实时反馈应用调用链各节点检测结果，当检测异常时，主动推送异常信息给用户。支持数据视图功能，提供丰富的构建，部署，代码质量和调用量数据统计。

（4）浙江移动采用Marathon管理应用容器Docker，主要是解决开发测试过程中持续发布代码，跟踪日志，分析问题。由于Docker是从资源池中随机挑选计算节点启动实例，每次都需要跟踪到不同的节点去看Docker的运行状态和日志。同时Marathon还能够直观的反应应用发布的状态，对于unHealthy状态的应用可以及时反应到运维人员那里解决，针对一些边缘系统，可以通过Marathon发布到指定的小集群上，既能提高整个集群的利用率，也能满足业务测试边缘系统的需求。


## 北京洛哈技术有限公司 （ 2015年11月 ~ 2016年5月 ）

### 北京洛哈一起唱ERP系统项目 
北京洛哈技术有限公司 | JAVA研发工程师
项目名称：连锁财务系统（总/分店），连锁库存系统（总/分店）。 
工作描述：
（1）搭建springMVC+mybatis+EazyUI开发环境，数据库用mysql。

（2）开发连锁财务系统（分店）的会员信息查询，会员储值查询，会员消费查询，积分兑换查询，卡升级记录，累计积分查询，补卡记录，会员赠品记录模块。连锁库存系统（分店）的月结存，采购申请，采购入库，跨点调拨管理模块。连锁库存系统（总店）的申请单审核，库存调拨，供应商清账等模块。

（3）在Linux服务器上搭建JDK+MySQL+tomcat的测试环境，用xshell和filezilla维护服务器。



## 亚信科技（中国）有限公司 （ 2014年6月 ~ 2015年10月 ）

### 河南移动架构演进项目 
亚信科技 | JAVA研发工程师
项目名称：河南移动CRM架构演进产品中心建设项目
项目描述：产品中心能力梳理，规定开放标准；缓存即时生效；优化终端配置方案。
工作内容：
（1）负责产品中心能力梳理和重构工作，优化产品信息查询效率，查询和配置实现Oracle和memcached的读写分离。将产品中心代码重构，分离出核心服务、组件服务、中心服务，查询和配置读写分离，将产品信息查询分离到Cached类中，直接查询memcached，将产品配置分离到DB类中，写操作时，memcached实施刷新变更数据。规定产品中心服务开发标准，采用RMI远程通讯协议，对接EJB接口。
（2）负责产品中心终端配置优化工作，同时带两位刚入职的新同事共同完成。分析终端销售品数据模型，设计终端产品配置流程，完成产品配置详细设计文档。开发营销活动配置模块，终端SKU配置模块。



## 自我评价

1、本人有4年的Java工作经验，熟悉JAVA，HTML,CSS,JavaScript,
Oracle相关技术。
2、热心交流，主动沟通，积极协调，具有很好的团队协作意识，有独立交付项
目的经验。
3、能够根据领导布置的任务合理安排工作计划，及时汇报工作进度和工作成
果。
4、自学能力强，敢于面对困难，有很好的分析问题、解决问题的能力。






  


