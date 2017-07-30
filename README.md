# Pet Store for DDD Kata

一个使用`领域驱动设计`和`微服务架构`的概念验证项目。

- [为何又是PetStore！](https://github.com/microservices-kata/petstore-materials/blob/master/WhyAnotherPetstore.md)
- [微服务该如何做？](https://github.com/microservices-kata/petstore-materials/blob/master/HowToDoItRight.md)
- [这个项目想要做什么(图)](https://github.com/microservices-kata/petstore-materials/blob/master/image/Goals.png)

此项目计划采用以下实践：

- 使用"最终一致性"取代"分布式事务"
- 微服务分层和统一(Restful)API规范
- 防雪崩机制：超时、重试、断路器
- 测试分层：单元测试、接口测试、契约测试、端到端测试
- 基础设施即代码、流水线即代码
- 基于Docker的容器化部署
- 语言异构&数据库异构
- <s>响应式设计&异步API</s>[1]
- <s>内建安全(build-in security)</s>[2]

> [1] 暂缓，实际采用同步API <br>
> [2] Security is the enemy of simplicity !! It's PoC project.

## 概念验证材料

- [原始需求清单](https://github.com/microservices-kata/petstore-materials/blob/master/EpicStory.md)
- [API设计模板](https://github.com/microservices-kata/petstore-materials/blob/master/ApiDesignTemplate.md)
- [基础设施准备](https://github.com/microservices-kata/petstore-infrastructure/blob/master/ManualSetup.md)

## 概念验证步骤

- 设计原始需求材料 (Done)
- 识别业务实体 (Done)
- 识别聚合和界定上下文 (Done)
- 设计Restful API (Done)
- 实现API功能 (On Going)
- 持续补充需求和演进

## 领域模型

![Model](https://github.com/microservices-kata/petstore-materials/raw/master/image/Model.png)
参考：[事件风暴后的模型原型](https://github.com/microservices-kata/petstore-materials/blob/master/image/DraftModel.png)

## 架构分层

![Layer](https://github.com/microservices-kata/petstore-materials/raw/master/image/Layer.png)

代码仓库:

- [Web BFF (Java)](https://github.com/microservices-kata/petstore-web-bff)
- [Order Service (Kotlin + MongoDB)](https://github.com/microservices-kata/petstore-order-service)
- [Account Service (Scala + MongoDB)](https://github.com/microservices-kata/petstore-account-service)
- [Inventory Service (Groovy + MySQL)](https://github.com/microservices-kata/petstore-inventory-service)
