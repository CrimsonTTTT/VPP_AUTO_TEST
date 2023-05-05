# VPP_AUTO_TEST
概要：一个cd部分的test，用vpp系统做演示

## 测试用
暂时还处于环境搭建中，不急。。。。


#### 如何运行

```
    mvn clean test -DTestNG.xml=src/main/java/suite/TestNG.xml 
    mvn test -DTestNG.xml=TestNG.xml
```

其中：-Dxxxx 代表传入pom.xml的参数，后面是具体路劲
