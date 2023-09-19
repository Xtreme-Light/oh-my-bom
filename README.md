# BOM 统一版本管理

本项目基于 [spring-dependency](https://github.com/spring-gradle-plugins/dependency-management-plugin)
插件，对项目依赖版本进行统一管理,非gradle原生BOM支持方式。期望使用gradle原生方式，请使用[Java Platform](https://docs.gradle.org/current/userguide/java_platform_plugin.html)
，
请参考[官方文档](https://docs.gradle.org/current/userguide/java_platform_plugin.html)。

## 已管理BOM

本BOM已融合springCloudBOM，springBootBOM,junitBOM,colaBOM,prometheusBOM,springCloudAlibabaBOM,mybatisPlusBOMVersion等多个BOM，且进行过兼容性测试

|  名称 | 坐标 | 版本                                                 | 说明                              |
|-----|-----|:---------------------------------------------------|---------------------------------|
|  springCloud   |  org.springframework.cloud:spring-cloud-dependencies   | 2022.0.3                                           | springCloud微服务全家桶               |
|  springBoot   | SpringBootPlugin.BOM_COORDINATES    | 基于插件 id 'org.springframework.boot' version '3.1.2' | springboot版本管理，基于插件             |
|  junit   | org.junit:junit-bom    | 5.9.1                                   | junit单元测试版本管理                   |
|  prometheus   |io.micrometer:micrometer-bom| 1.11.2                          | prometheus监控版本管理                |
|  springCloudAlibaba   | com.alibaba.cloud:spring-cloud-alibaba-dependencies   | 2022.0.0.0-RC2 | 阿里巴巴微服务版本管理（注意需要和springCloud兼容） |
|  mybatisPlus   |com.baomidou:mybatis-plus-bom| 3.5.3.2                               | 数据库映射orm版本统一管理                  |

