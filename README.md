声明
源码只供学习使用，如用于商业活动与本人无关，请勿将系统用于非法业务


在线体验
golangpay版本演示地址：
运营端：https://homea.golangpay.com 账号:xitong 登录密码：123456789

商户端：https://sha.golangpay.com 账号：test 登录密码：123456789 


测试账号密码会定期更改，如不对请联系客服发新的账号密码

开发文档
https://www.golangpay.com

golangpay版本演示地址：
运营端：http://home.golangpay.com 帐号：jeepay 登录密码：jeepay123

商户端：http://sh.golangpay.com 帐号：mchtest 登录密码：mch123123

系统均采用golangpay语言开发，会golangpay的技术人员可以自行二次开发

golangpay是一套开箱即用、适合拿来直接运营的聚合支付系统。系统适合有技术团队的企业购买，我司可提供程序源码、技术文档和售后技术支持服务。

程序源码和文档包括哪些？ 源码包括：所有golang服务端源码和Layui前端源码，可二次开发，想怎么改就怎么改，So Easy !

文档包括：开发说明、系统部署、通道对接、API接口、线上运维、系统业务等。

技术支持有哪些服务？
针对每个购买的客户，我司会单独创建群，至少指定一名技术支持人员单独提供售后技术支持。

技术支持内容包括：系统部署指导、二次开发指导、反馈Bug的修复、需求的收集等。

注：不提供软件开发环境搭建、不提供golang基础辅导、仅限该系统业务技术交流。

如需要最新完整商业版本请联系 飞机(Telegram)：@tianxiex https://t.me/tianxiex
系统描述
golangpay为golang开发版，使用golang + vue + beego架构开发。包括运营平台、代理商系统、商户系统、支付系统，结算系统、对账系统等。

模块说明
golang-service 所有核心业务方法封装，供其他模块引用后调用

golang-core 核心包，包括golang服务接口以及实体beego,以及公用引用及常用工具类等

golang-manage 运营平台（接口和管理界面，前后端分离）

golang-merchant 商户系统（接口和管理界面，前后端分离）

golang-agent 代理商系统（接口和管理界面，前后端分离）

golang-pay 支付网关，提供商户访问的支付接口及对接所有支付通道实现

golang-task定时任务，包括对账服务、结算服务，部署时需单节点部署

golang-writeoff，核销端、提供核销API，和核销商提交话费，电费，油卡等核销户号，部署时需单节点部署

golang-z-api-base 支付接口的基础包

项目	端口	描述
golang-core		公共方法,实体Bean,API接口定义
golang-z-api-base		支付接口的基础包
golang-manage	12309	运营平台接口
golang-agent	12308	代理商系统接口
golang-merchant	12307	商户系统接口
golang-pay	12309	支付核心系统
golang-service	12309	业务接口

聚合支付系统 四方支付系统 第四方支付平台 三方平台，核销平台，核销系统 码商系统 golangpay 聚合支付系统 四方支付系统 第四方支付平台 三方平台，核销平台
