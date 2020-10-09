# 【项目实践】后端接口统一规范的同时，如何优雅得扩展规范

## 运行项目

本项目基于Maven构建，将项目clone下来后导入到IDE中，点击启动即可运行项目

## 项目讲解

https://juejin.im/post/6844904143912435719



```java

        <!--swagger增强工具依赖包，方便生成接口文档。非必须导入-->
        <dependency>
            <groupId>com.github.xiaoymin</groupId>
            <artifactId>knife4j-spring-boot-starter</artifactId>
            <version>2.0.1</version>
        </dependency>
        <!--lombok依赖包，简化类。非必须导入-->
        <dependency>
            <groupId>org.projectlombok</groupId>
            <artifactId>lombok</artifactId>
            <optional>true</optional>
        </dependency>


```

http://localhost:8080/doc.html
