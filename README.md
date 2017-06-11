# Pet Store for DDD Kata

一个使用`领域驱动设计`和`微服务架构`的概念验证项目。

- [为何又是PetStore！](https://github.com/tw-ms-kata/petstore-materials/blob/master/WhyAnotherPetstore.md)
- [微服务该如何做？](https://github.com/tw-ms-kata/petstore-materials/blob/master/HowToDoItRight.md)
- [这个项目想要做什么(图)](https://github.com/microservices-kata/petstore-materials/blob/master/image/Goals.png)

## 练习材料
- [原始需求清单](https://github.com/tw-ms-kata/petstore-materials/blob/master/EpicStory.md)
- [API设计模板](https://github.com/tw-ms-kata/petstore-materials/blob/master/ApiDesignTemplate.md)
- [基础设施准备](https://github.com/tw-ms-kata/petstore-infrastructure/blob/master/ManualSetup.md)

## 练习步骤
- 熟悉原始需求材料
- 识别业务实体
- 识别聚合和界定上下文
- 设计Restful API
- 实现API功能

## 领域模型
![Model](https://github.com/tw-ms-kata/petstore-materials/raw/master/image/Model.png)
参考：[事件风暴后的模型原型](https://github.com/microservices-kata/petstore-materials/blob/master/image/DraftModel.png)

## 架构分层
![Layer](https://github.com/tw-ms-kata/petstore-materials/raw/master/image/Layer.png)

代码仓库:

- [Web BFF (Jave)](https://github.com/tw-ms-kata/petstore-web-bff)
- [Order Service (Kotlin + MongoDB)](https://github.com/tw-ms-kata/petstore-order-service)
- [Account Service (Scala + MongoDB)](https://github.com/tw-ms-kata/petstore-account-service)
- [Inventory Service (Groovy + MySQL)](https://github.com/tw-ms-kata/petstore-inventory-service)
