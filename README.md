# spring-batch-demo

## Build
```
./mvnw clean package -DskipTests=true
```

## Run
```
java -jar target/spring-batch-demo-0.0.1-SNAPSHOT.jar --job.names=helloFirstJob
java -jar target/spring-batch-demo-0.0.1-SNAPSHOT.jar --job.names=helloSecondJob
java -jar target/spring-batch-demo-0.0.1-SNAPSHOT.jar --job.names=helloSequentialJob
java -jar target/spring-batch-demo-0.0.1-SNAPSHOT.jar --job.names=helloConditionalJob -processorNo=2
java -jar target/spring-batch-demo-0.0.1-SNAPSHOT.jar --job.names=helloFirstJob,helloSecondJob,helloSequentialJob
```