# A Spring Cloud Demo

![架构图](https://s1.ax1x.com/2020/07/09/UnRvFO.md.png)


- **网关服务**：使用zuul实现；
- **注册中心**：使用Eureka实现；
- **用户服务**：提供RESTful API的用户服务，使用Spring MVC实现；该服务会调用**产品服务**；
- **产品服务**：提供RESTful API的产品服务，使用Spring MVC实现，使用了一个H2数据库；
- **Web服务**：外部用户通过该服务来访问系统各项服务，这里使用curl命令模拟。
