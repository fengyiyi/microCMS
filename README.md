# microCMS(开发中...暂时不可商用)
MicroCMS提供一个轻量级企业网站解决方案，基于 PHP + [MySQL/Sqlite] 的技术开发，整个系统压缩为单个PHP文件，全部源码开放，数据库结构完全兼容ECMS，适用于普通企业官网、企业商城类型网站搭建。

ECMS采用的是后台与站点分离方式建站，但是企业网站开发中，部分客户需要在自己的服务器或FTP空间里部署网站程序，因此开发microCMS满足广大客户需求。

# 后台登录
默认帐号：admin  默认密码：123456

# 待完成工作
1、API初始化流程
---
用户从GIT获取项目到站点目录；
访问microCMS系统初始化入口，根据界面设定填写数据库信息，程序开始自动根据sql文件创建数据库；

2、模板仓库对接  
---
获取从ecms云系统获取模板列表，对接到microCMS，供用户快速安装更多模板；