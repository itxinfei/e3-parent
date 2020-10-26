# 宜立方商城
![输入图片说明](https://images.gitee.com/uploads/images/2020/0910/100616_e63ea486_800553.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/0910/100634_d218b49c_800553.png "屏幕截图.png")
开发环境： eclipse+maven+svn+linux+easyui

软件架构： mysql+mybatis+spring+springmvc+redis+solr

项目描述：宜立方商城是一个综合性的B2C平台，类似京东商城、天猫商城。会员可以在商城浏览商品、下订单，以及参加各种活动。宜立方商城采用分布式系统架构，子系统之间都是调用服务来实现系统之间的通信，使用http协议传递json数据方式实现。这样降低了系统之间的耦合度，提高了系统的扩展性。为了提高系统的性能使用redis做系统缓存，并使用redis实现session共享。为了保证redis的性能使用redis的集群。搜索功能使用solrCloud做搜索引擎。

后台管理系统：管理商品、订单、类目、商品规格属性、用户管理以及内容发布等功能。

商城门户：用户可以在前台系统中进行注册、登录、浏览商品、首页、下单等操作。

会员系统：用户可以在该系统中查询已下的订单、收藏的商品、我的优惠券、团购等信息。

订单系统：提供下单、查询订单、修改订单状态、定时处理订单。

搜索系统：提供商品的搜索功能。

单点登录系统：为多个系统之间提供用户登录凭证以及查询登录用户的信息。

相关框架：

1.dubbo:当服务越来越多，容量的评估，小服务资源的浪费等问题逐渐显现，此时需增加一个调度中心基于访问压力实时管理集群容量，提高集群利用率。此时，用			于提高机器利用率的资源调度和治理中心。

2.FastDFS：分布式文件系统，用于搭建一个图片服务器，专门保存图片。存储空间可以横向扩展，可以实现服务器的高可用。支持每个节点有备份机。

3.Redis集群：用于添加缓存，减少查询数据库的压力。

4.SolrCloud：用于实现搜索功能，快速高效。

5.Activemq：使用Activemq发送接收消息，通过消息队列实现商品同步。

6.Freemarker：FreeMarker是一个用Java语言编写的模板引擎，它基于模板来生成文本输出。FreeMarker与Web容器无关，即在Web运行时，它并不知道Servlet或HTTP。它不仅可以用作表现层的实现技术，而且还可以用于生成XML，JSP或Java 等。

7.MyCAT：一个彻底开源的，面向企业应用开发的“大数据库集群”支持事务、ACID、可以替代Mysql的加强版数据库，可以低成本的将现有的单机数据库和应用平滑迁移到“云”端，解决数据存储和业务规模迅速增长情况下的数据瓶颈问题。

### 交流方式：

QQ技术交流群：863662849<a target="_blank" href="https://qm.qq.com/cgi-bin/qm/qr?k=9yLlyD1dRBL97xmBKw43zRt0-6xg8ohb&jump_from=webapi">
<img border="0" src="//pub.idqqimg.com/wpa/images/group.png" alt="Java项目交流+求职面试" title="Java项目交流+求职面试"></a><a target="_blank" href="http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=f0hLSE9OTkdHTT8ODlEcEBI" style="text-decoration:none;"><img src="http://rescdn.qqmail.com/zh_CN/htmledition/images/function/qm_open/ico_mailme_02.png"/></a>

![QQ技术交流群：863662849](https://images.gitee.com/uploads/images/2020/1022/145319_459f7be2_800553.png "QQ技术交流群.png")

### 整理不易，欢迎各位白嫖star
如果可以请各位大佬打赏一下，请我喝杯咖啡，资助一下云服务器，部署一个演示站点，感谢！！！

![输入图片说明](https://images.gitee.com/uploads/images/2020/1022/152637_f80669f5_800553.jpeg "支付宝收钱码.jpg")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1022/152705_964cb145_800553.png "微信收钱码.png")