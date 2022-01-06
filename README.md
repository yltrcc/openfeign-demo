该项目的资料文件夹，包含sql文件以及疑问解决方案等。

# 微服务端口说明
cloud-api-commons 公共模块
cloud-provider-payment01 - 8001
cloud-provider-payment02 - 8002

cloud-consumer-feign-order - 80

cloud-eureka-server01 - 7001
cloud-eureka-server02 - 7002

# 启动服务

cloud-provider-payment01
cloud-provider-payment02 

cloud-consumer-feign-order 

cloud-eureka-server01 
cloud-eureka-server02 

依次启动上述服务，访问测试地址：http://localhost/consumer/payment/get/1