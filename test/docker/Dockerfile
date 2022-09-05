FROM openjdk:11
WORKDIR /var/app
ADD test-1-0.0.1-SNAPSHOT.jar /var/app/zkui.jar
#开放8000端口
EXPOSE 9091
#配置容器启动后执行的命令
ENTRYPOINT ["java","-jar","/var/app/zkui.jar"]