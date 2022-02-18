<h1 align="center">Agarwood Cloud</h1>
Agarwood is a solution for private domain traffic, based on mainstream platforms such as WeChat and Douyin, providing instant reception to fans and helping merchants to provide customer service and growth.

> **[中文说明](README.Zh-CN.md)**

## Project Status: Alpha

The project is still in the incubation and evolution stage, and everyone is welcome to participate in the construction of the Agarwood project!🎉🎉
By participating in the Agarwood project, you can：

- 🔥 Learn the latest `Micro Services`+`Domain Driven Design` technology
- 🎁 Learn how to design and develop microservices
- ⭐ Participate in the open source community
- 🎊 Meet a group of friends who love learning and open source

## Installation and Getting Started

**TODO**: include multiple services

## Modules

There are several modules in Agarwood. Here is a quick overview:

### [OAuth.Provider](https://github.com/agarwood-cloud/agarwood.cloud.oauth.provider)

The library providing like gateway features that support the other parts of Agarwood. These include:

- [x] RBAC (Role-Based Access Control)
- [x] JWT (JSON Web Token)
- [ ] OAuth2.0
- [ ] ABAC (Attribute-Based Access Control)
- [ ] ACL (Access Control List)

### [User.Provider](https://github.com/agarwood-cloud/agarwood.cloud.user.provider)

The library providing features that support the other parts of Agarwood. These include:

- [x] Assign Customer Service
- [x] Tencent Platform Official Account users
- [x] Customer Service Management
- [x] Chat Room Based On Redis Message Subscription

### [Chat.Provider](https://github.com/agarwood-cloud/agarwood.cloud.chat.provider)

The library providing features that support the other parts of Agarwood. These include:

- [x] Chat Room Based On Redis Message Subscription (NestJS)

### [Backend.Subscriber](https://github.com/agarwood-cloud/agarwood.cloud.backend.subscriber)

- [ ] Background Management UI

### [Chat.Subscriber](https://github.com/agarwood-cloud/agarwood.cloud.chat.subscriber)

- [ ] Chat front end UI

### [OMS.Provider](https://github.com/agarwood-cloud/agarwood.cloud.oms.provider)

The library providing features that support the other parts of Agarwood. These include:

- [ ] **TODO** OMS(Order Management System)

### [Mall.Provider](https://github.com/agarwood-cloud/agarwood.cloud.mall.provider)

The library providing features that support the other parts of Agarwood. These include:

- [x] Tencent Platform Official Account
- [x] Enterprise information
- [ ] Shop information

### [PLM.Provider](https://github.com/agarwood-cloud/agarwood.cloud.plm.provider)

- [ ] **TODO** PLM(Product Lifecycle Management)

### [CDP.Provider](https://github.com/agarwood-cloud/agarwood.cloud.plm.provider)

- [ ] **TODO** CDP(Customer Data Platform)

## Why **Agarwood** ?

- **Agarwood is Focus**
Agarwood is focus on private domain traffic solution, each function is carefully designed to flow, transform, and repurchase.
- **Agarwood is Flexible**
Agarwood is flexible through simple ways to extend service, such as json-rpc, grpc(planned), etc.
- **Agarwood is Available**
Agarwood is available in our production environment for more than one year, and has been tested multiple times, can meet most requirements.
- **Agarwood is High Performance**
Agarwood is based on microservice architecture, provides high performance service, such as high concurrency, high throughput, and high availability.
- **Agarwood is Microservice**
Agarwood supports multiple languages, such as PHP, Go, Java, TypeScript, etc., supports microservice architecture, supports message queue, supports cross-language call.
- **Agarwood is Domain Driven Design**
Agarwood is based on domain-driven design, translates private business models into system architecture design

## License

Agarwood is Open Source software released under the [GPLv3 license](./LICENSE).
