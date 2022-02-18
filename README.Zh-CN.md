<h1 align="center">Agarwood Cloud</h1>
Agarwood 是一套私域流量的解决方案，基于微信、抖音等主流平台，对粉丝做好即时接待，助力商家做好客户服务和增长

## 当前状态: Alpha

该项目还处于孵化和演进阶段，欢迎大家参与到 Agarwood 项目的建设中来！🎉🎉
通过参与 Agarwood 项目，你可以：

- 🔥 学习最新的 `Micro Services`+`Domain Driven Design` 技术
- 🎁 学习如何设计和开发微服务
- ⭐ 参与到开源社区中来
- 🎊 结识一群热爱学习、热爱开源的朋友

## 模块

### [OAuth.Provider](https://github.com/agarwood-cloud/agarwood.cloud.oauth.provider)

该库提供类似网关的功能，属于Agarwood的其中一部分，包括特性有：

- [x] RBAC (Role-Based Access Control)
- [x] JWT (JSON Web Token)
- [ ] OAuth2.0
- [ ] ABAC (Attribute-Based Access Control)
- [ ] ACL (Access Control List)

### [User.Provider](https://github.com/agarwood-cloud/agarwood.cloud.user.provider)

主要包含的功能有：

- [x] 分配对应的客服(销售)
- [x] 腾讯平台公众账号的用户管理
- [x] 客服管理
- [x] 基于Redis的消息订阅

### [Chat.Provider](https://github.com/agarwood-cloud/agarwood.cloud.chat.provider)

基于Nestjs的消息订阅服务

- [x] 基于Redis的消息订阅聊天室

### [Backend.Subscriber](https://github.com/agarwood-cloud/agarwood.cloud.backend.subscriber)

- [ ] 后台管理系统前端UI界面

### [Chat.Subscriber](https://github.com/agarwood-cloud/agarwood.cloud.chat.subscriber)

- [ ] 客服系统前端UI界面

### [OMS.Provider](https://github.com/agarwood-cloud/agarwood.cloud.oms.provider)

订单管理系统

- [ ] **TODO** OMS(Order Management System)

### [Mall.Provider](https://github.com/agarwood-cloud/agarwood.cloud.mall.provider)

企业商城

- [x] 腾讯平台公众账号管理
- [x] 企业信息设置
- [ ] 店铺装修等

### [PLM.Provider](https://github.com/agarwood-cloud/agarwood.cloud.plm.provider)

产品生命同期管理系统

- [ ] **TODO** PLM(Product Lifecycle Management)

### [CDP.Provider](https://github.com/agarwood-cloud/agarwood.cloud.plm.provider)

- [ ] **TODO** CDP(Customer Data Platform)


## 为何选择 **Agarwood**

- **专注私域**
专注于私域流量的解决方案，每一个功能都都是围绕引流、变现、复购等功能精心打造。
- **扩展灵活**
可以通过简单的方式扩服务，比如可通过json-rpc、grpc(规划中)等方式扩展服务。
- **生产可用**
在我司生产环境中已稳定运行超过一年，经过多次测试，可以满足大部分的需求。
- **高性能**
基于微服务架构，提供高性能的服务，比如高并发、高吞吐量、高可用性等。
- **微服务**
支持多种语言，包括PHP、Go、Java、TypeScript等，支持微服务架构，支持消息队列，支持跨语言调用。
- **领域驱动设计**
通过领域驱动设计思想，把私域的业务模型翻译成系统架构设计

## 规划

- [ ] 整理DDD相关文档
  - [ ] 业务需求文档
  - [ ] 系统架构图
  - [ ] 系统用例图
