### Sentinel 使用 Nacos 的存储规则

### 注意：
1.本项目版本：

Spring Cloud Version| Spring Cloud Alibaba Version | Spring Boot Version
--- | --- | ---
Spring Cloud Greenwich | 2.1.1.RELEASE | 2.1.X.RELEASE

2.pom.xml中需要先引入依赖：spring-cloud-alibaba-dependencies，再引入依赖：spring-cloud-starter-alibaba-sentinel、sentinel-datasource-nacos

3.启动 Sentinel Dashboard：https://www.cnblogs.com/cag2050/p/11970999.html ，启动 Nacos：https://www.cnblogs.com/cag2050/p/11918293.html

### 参考资料

参考资料 | 网址
--- | ---
Spring Cloud Alibaba基础教程：Sentinel使用Nacos存储规则 | http://blog.didispace.com/spring-cloud-alibaba-sentinel-2-1/
使用 Sentinel Dashboard 的 Docker 镜像 | https://www.cnblogs.com/cag2050/p/11970999.html
使用 Nacos 的 Docker 镜像，启动 Nacos 服务 | https://www.cnblogs.com/cag2050/p/11918293.html
组件版本关系 | https://github.com/alibaba/spring-cloud-alibaba/wiki/%E7%89%88%E6%9C%AC%E8%AF%B4%E6%98%8E