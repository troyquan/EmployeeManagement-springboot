
FROM openjdk:17-jdk-hotspot

# 复制 Spring Boot 应用程序的 JAR 文件到容器中
COPY service-system.jar .

# 定义容器启动命令
CMD ["java", "-jar", "service-system.jar"]
