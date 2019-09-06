# commit-with-gitinfo
测试打包带GIT信息
```shell script
mvn clean package -f pom.xml -DskipTests
java -jar target/your-application-name.jar
http://localhost:8080/actuator/info
``` 
ref:https://rieckpil.de/howto-expose-git-information-with-spring-boots-actuator/

