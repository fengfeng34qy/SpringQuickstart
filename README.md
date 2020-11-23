# 一.需要准备的东西
1. JDK
2. Eclipse
3. Maven程序包

# 二.安装mvn
1. 前往[https://spring.io/quickstart](https://spring.io/quickstart)下载
2. 设置环境变量 变量名(MAVEN_HOME); 变量值(maven的安装路径,如D:\sff\installs\apache-maven-3.5.4)
3. 编辑环境变量Path，追加%MAVEN_HOME%\bin\;
4.检查maven是否安装成功,
```bash
mvn -v
```

# 运行
```bash
mvn spring-boot:run
```
打开网页[http://localhost:8080/hello](http://localhost:8080/hello)查看效果

[Spring快速入门指南](https://spring.io/quickstart)

