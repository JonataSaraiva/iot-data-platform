# iot-data-platform
Scalable cloud platform to ingest data from iot devices 

**Note: It was the architecture that I've chosen to this scenario as a MVP and the second draw (V1) could be a first version to take to production.**  

  ![](https://github.com/JonataSaraiva/iot-data-platform/blob/main/architecture.jpeg)


### Tools/frameworks:

- **Localstack** - A local AWS cloud stack to emulate a cloud environment locally using a docker container.

- **Serverless framework** - A command-line tool that uses easy and approachable YAML to deploy both your serverless functions and cloud infrastructure

- **Docker-compose** - To manage the containers ( localstack and elasticsearch )

- **Spring-boot** - Tool that makes developing web application and microservices with Spring Framework faster and easier

- **ElasticSearch** - Distributed and scalable search and analytics engine for processing, storing, and retrieving large volumes of data in near real-time

### Apps 

#### API-Gateway
- [devices-api-gateway](https://github.com/JonataSaraiva/devices-api-gateway)

#### Microservices
- [api-collector-app](https://github.com/JonataSaraiva/api-collector-app)

- [api-query-app](https://github.com/JonataSaraiva/api-query-app)

- [consumer-metrics-app](https://github.com/JonataSaraiva/consumer-metrics-app)

### How to run it
- Instruction about how to get this project running can be found [here](https://github.com/JonataSaraiva/devices-api-gateway#readme)
