# Sample project for GCP Storage in Spring Boot

### Reference Documentation

For further reference, please consider the following sections:

* [Cloud Storage client libraries](https://cloud.google.com/storage/docs/reference/libraries#client-libraries-install-java)
* [GCP Storage](https://cloud.spring.io/spring-cloud-gcp/reference/html/#spring-resources)

### Technologies:
* Spring Boot 2.5.5
* Google Cloud 2.0.4

### Guides
* Please follow the guidelines to create a bucket with GOOGLE_APPLICATION_CREDENTIALS credentials [Cloud Storage client libraries](https://cloud.google.com/storage/docs/reference/libraries#client-libraries-install-java)

### How to run?
1. Download dependencies and compile the project with the following command:

   ```./mvnw clean install```


2. The project is a Spring Boot Application, so you can run inside of your IDE or from terminal with the following command:

   ```./mvnw spring-boot:run```

### Rest Endpoint
```
http://localhost:8081/sample-gcp-storage/v1/gcp/storages/send-data
```
