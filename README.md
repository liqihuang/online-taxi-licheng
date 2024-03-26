网约车项目

项目描述： 此项目是一款网约车软件，主要功能包括： 乘客端：登录注册，下单，支付，评价，维护个人信息等。 司机端：登录，出车收车，接乘客到订单完成，发起收款等。 boss端：主要负责添加司机，车辆，以及设置计价规则等 地图模块：主要是接入第三方地图实现。车辆同步，车辆调度，里程查询，轨迹点查询，路径规划，距离计 算等。 消息模块：轮寻消息，推送，短信等。 派单引擎：实时单派单，预约单派单，抢单等。 订单系统：订单创建，修改，状态变更等。 计价系统：基础计价，动态调价，分时段计价。 支付系统：接入微信支付，支付宝支付。余额充值，资金冻结，订单退款等。 账号系统：乘客注册登录，乘客信息维护，司机录入，司机登录，司机信息维护等。

技术架构： SpringBoot+SpringCloudAlibaba+RocketMQ+Mysql+Redis

前端：uni-app  
数据库：MySQL  
缓存：Redis  
注册中心：Nacos，Consul，Eureka  
配置中心：Spring Cloud Config  
微服务网关：Spring Cloud Gateway  
熔断设计与实战：Spring Cloud Circuit Breaker、Resilience4J、Spring Cloud Alibaba Sentinel  
限流设计与实战：Spring Cloud Alibaba Sentinel  
服务监控：Spring Cloud Sleuth、Spring Cloud Zipkin  
分布式解决方案：Redisson、Seata  
通信：Server-Sent Events  
