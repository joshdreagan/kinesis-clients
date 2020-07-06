# AWS Kinesis Clients

## Producer

__Plain text__

```
env CAMEL_COMPONENT_AWS_KINESIS_ACCESS_KEY="<AWS_ACCESS_KEY>" CAMEL_COMPONENT_AWS_KINESIS_SECRET_KEY="<AWS_SECRET_KEY>" mvn spring-boot:run "-Dspring-boot.run.arguments=--kinesis.stream=<AWS_KINESIS_STREAM_NAME>"
```

## Consumer

__Plain text__

```
env CAMEL_COMPONENT_AWS_KINESIS_ACCESS_KEY="<AWS_ACCESS_KEY>" CAMEL_COMPONENT_AWS_KINESIS_SECRET_KEY="<AWS_SECRET_KEY>" mvn spring-boot:run "-Dspring-boot.run.arguments=--kinesis.stream=<AWS_KINESIS_STREAM_NAME>"
```
