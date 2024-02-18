# spring-dataflow-server

## Download the Spring Cloud Data Flow Server and shell by using the following commands:
```
wget https://repo.maven.apache.org/maven2/org/springframework/cloud/spring-cloud-dataflow-server/2.11.2/spring-cloud-dataflow-server-2.11.2.jar
wget https://repo.maven.apache.org/maven2/org/springframework/cloud/spring-cloud-dataflow-shell/2.11.2/spring-cloud-dataflow-shell-2.11.2.jar
```

## Download Skipper by running the following command:
```
wget https://repo.maven.apache.org/maven2/org/springframework/cloud/spring-cloud-skipper-server/2.11.2/spring-cloud-skipper-server-2.11.2.jar
```
## Running application
```
java -jar spring-cloud-dataflow-shell-2.11.2.jar
java -jar spring-cloud-dataflow-server-2.11.2.jar --spring.cloud.dataflow.features.schedules-enabled=true --spring.datasource.url=jdbc:postgresql://localhost:5432/dataflow --spring.datasource.username=postgres --spring.datasource.password=postgres --spring.datasource.driverClassName=org.postgresql.Driver
```

## Application:
http://localhost:9393/dashboard

![Screenshot]([https://github.com/OzgurAkinci/spring-boot-kubernetes-and-docker/blob/main/git_resources/pods.png](https://github.com/OzgurAkinci/spring-dataflow-server/blob/main/dataflow.png?raw=true)?raw=true)
