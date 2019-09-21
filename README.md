# code-parent

[![GitHub release](https://img.shields.io/github/release/flysoloing/code-parent.svg)](https://github.com/flysoloing/code-parent/releases)

通用parent模块，统一管理各Project的依赖项和配置项，定期升级优化，减少各应用的依赖包维护成本。

当前最新正式版本：[1.1](https://github.com/flysoloing/repo/blob/gh-pages/libs/com/flysoloing/code-parent/1.1/code-parent-1.1.pom)

当前最新快照版本：1.1-SNAPSHOT

**Release Notes:**

- 1.1
  
  [升级]
    
    - 日志组件：logback（原版本：1.1.7，升级后版本：1.2.3）；slf4j（原版本：1.7.21，升级后版本：1.7.28）
    
    - 序列化组件：logback（原版本：1.1.7，升级后版本：1.2.3）
    
    - 网络工具组件：netty（原版本：4.1.9.Final，升级后版本：4.1.39.Final）；httpclient（原版本：4.5.3，升级后版本：4.5.9）
    
    - 通用工具组件：logback（原版本：1.1.7，升级后版本：1.2.3）
    
    - Spring Framework：4.3.x（原版本：4.3.20.RELEASE，升级后版本：4.3.25.RELEASE）
    
    - curator（原版本：3.2.1，升级后版本：4.2.0）
    
    - jedis（原版本：2.9.0，升级后版本：3.1.0）
    
    - resteasy（原版本：3.0.19.Final，升级后版本：3.8.1.Final）
    
    - mybatis（原版本：3.4.1，升级后版本：3.5.2）；mybatis-spring（原版本：1.3.0，升级后版本：2.0.2）
    
    - shiro（原版本：1.4.0，升级后版本：1.4.1）
    
    - 模板组件：freemarker（原版本：2.3.23，升级后版本：2.3.29）
    
    - servlet相关组件：servlet（原版本：3.1.0，升级后版本：4.0.1）；taglibs（原版本：1.1.2，升级后版本：1.2.5）
    
    - jackson（原版本：2.9.8，升级后版本：2.9.9）
    
    - aspectj（原版本：1.8.9，升级后版本：1.9.4）
    
    - mysql-connector-java：5.1.x（原版本：5.1.20，升级后版本：5.1.48）
    
    - xstream（原版本：1.4.9，升级后版本：1.4.11.1）
    
    - Alibaba相关组件：druid（原版本：1.0.26，升级后版本：1.1.20）；fastjson（原版本：1.2.38，升级后版本：1.2.59）
    
    - Google相关组件：gson（原版本：2.2.4，升级后版本：2.8.5）；guava（原版本：19.0，升级后版本：28.1-jre）；protobuf-java（原版本：3.2.0，升级后版本：3.9.1）
    
    - new apache commons：commons-dbcp2（原版本：2.1.1，升级后版本：2.7.0）；commons-lang3（原版本：3.4，升级后版本：3.9）；commons-pool2（原版本：2.4.2，升级后版本：2.7.0）；commons-collections4（原版本：4.1，升级后版本：4.4）；commons-compress（原版本：1.18，升级后版本：1.19）
    
    - old apache commons：commons-io（原版本：2.5，升级后版本：2.6）；commons-codec（原版本：1.10，升级后版本：1.13）；commons-beanutils（原版本：1.9.2，升级后版本：1.9.4）；commons-fileupload（原版本：1.3.3，升级后版本：1.4）；commons-validator（原版本：1.5.1，升级后版本：1.6）
    
    - Facebook相关组件：facebook.jcommon（原版本：0.1.29，升级后版本：0.1.32）
    
    - Maven插件：maven-core（原版本：3.3.3，升级后版本：3.6.1）；maven-plugin-api（原版本：3.3.3，升级后版本：3.6.1）；maven-plugin-annotations（原版本：3.4，升级后版本：3.6.0）
    
    - 增强型组件：reflections（原版本：0.9.10，升级后版本：0.9.11）；joda-time（原版本：2.9.7，升级后版本：2.10.3）；quartz（原版本：2.2.1，升级后版本：2.3.1）；hibernate-validator（原版本：5.2.4.Final，升级后版本：6.0.17.Final）；lombok（原版本：1.16.20，升级后版本：1.18.8）
    
    - 核心Maven插件：maven-clean-plugin（原版本：3.0.0，升级后版本：3.1.0）；maven-compiler-plugin（原版本：3.7.0，升级后版本：3.8.1）；maven-deploy-plugin（原版本：2.8.2，升级后版本：3.0.0-M1）；maven-install-plugin（原版本：2.5.2，升级后版本：3.0.0-M1）；maven-resources-plugin（原版本：3.0.2，升级后版本：3.1.0）；maven-site-plugin（原版本：3.6，升级后版本：3.8.2）
    
    - packaging types/tools：maven-jar-plugin（原版本：2.6，升级后版本：3.1.2）；maven-source-plugin（原版本：2.4，升级后版本：3.1.0）；maven-plugin-plugin（原版本：3.4，升级后版本：3.6.1）
    
    - 增强型Maven插件：versions-maven-plugin（原版本：2.5，升级后版本：2.7）
  
  [新增]
    
    - 日志组件：log4j2（版本：2.12.1）
    
    - Spring Framework：5.0.x（当前版本：5.0.15.RELEASE），5.1.x（当前版本：5.1.9.RELEASE）
    
    - 模板组件：thymeleaf（当前版本：3.0.11.RELEASE）
    
    - mysql-connector-java：6.0.x（当前版本：6.0.6），8.0.x（当前版本：8.0.17）
    
    - new apache commons：commons-configuration2（当前版本：2.5）

- 1.0
  
  [初始化]
    
    - 测试和日志组件，如：Junit、log4j、logback等
    
    - 序列化组件，如：fastjson、gson、xstream等
    
    - 网络工具组件，如：netty、httpclient等
    
    - 通用工具组件，如：commons-beanutils、commons-lang等
    
    - 模板工具组件，如：velocity、freemarker等
    
    - 框架组件，如：springframework、resteasy等
    
    - 阿里开源组件，如：druid、fastjson等
    
    - 谷歌开源组件，如：guava、protobuf等
    
    - 增强型组件，如：joda-time、lombok等
    
    - Maven插件，如：maven-source-plugin、jetty-maven-plugin等