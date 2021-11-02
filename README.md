# TNAxisHospital

#### 介绍
用Web service开发一个简单的就诊预约系统，实现如下基本功能：

1、预约功能：该系统使用户能够预订明后两天的专家号。首先，用户输入就诊日期和预约部门（内科和外科）。若不在两天之内，返回“不在预订日期内”提示框，提示用户重新输入就诊日期。若在两天之内，判断该部门有没有剩余的预约号，如果没有，返回“暂无预约号”；若有剩余的预约号，提示用户输入手机号码，若为11位有效号码并且此号码没有预约过，则提示“预约成功”，服务器端将此号码存起来作为预约信息，否则，提醒用户重新输入手机号码。

2、取消预约功能：提示用户输入手机号，若为11位有效号码并且此号码预约过，则返回“取消预约成功”，并在服务器端将此号码的预约信息删除；否则，返回“无效号码”或者“此号码尚未预约”，提示用户再次输入手机号码。

3、将该系统部署成Web服务；同时编写一个客户端进行调用。
PS：Web服务和客户端可以都在同一本地计算机；客户端可以是应用程序，也可以是Web页面。客户端要求有简单的用户界面。

#### 软件架构
软件架构说明
服务端：WebService+axis+mybatis
服务端开发环境：jdk8，mysql8.0，tomcat9.0，IDEA2021
客户端：基于Springboot来整合axis客户端

#### 安装教程

1.  xxxx
2.  xxxx
3.  xxxx

#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
