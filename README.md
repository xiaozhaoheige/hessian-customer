# hessian-customer
SpringBoot整合Hessian 客户端

客户端同样需要服务端的jar。除了jar依赖，客户端还需要两个东西，第一个是和业务端一样的接口代码，还有一个就是Hessian的连接对象。
客户端可以做成spring管理的模式，一个接口配置一个，也可以做成我下面写的这种，一个工具类，每次调用 HessianProxyFactoryUtil 

