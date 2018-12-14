# sx-services-erp

> 稍息 erp 系统的后端服务组归类。


## 接口需有前缀与版本号

+ 根据后端服务组别前缀数字正序继承

  - 服务: /api

  - 服务2: /api2

  - 服务3: /api3

+ 版本号

  - /v1

  - /v2

  - /v3

+ 接口示例

  - /api/v1/query

  - /api2/v1/query

  - /api3/v1/query

+ 备注

  - 前缀用于 web 服务器匹配转发规则

  - 版本号用于接口版本切换

+ 稍息组占用

  - /api 张金龙

  - /api2 付奥凯

  - /api3 孟佳兴

  - /api4 赵义

+ 模块功能涉及用户鉴权请接入张金龙组登录模块的拦截校验


## 其他

+ 前后端交互文档

  - 后端数据传递

  - 前端数据传递（注意后端可能需按照前端数据格式设计或校验字段）

  - [文档地址]



[文档地址]: ./data-specification.md