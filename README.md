# CompeticaoJob

**Course Link**: [Optimization of Performance for Spring Batch Jobs](https://www.udemy.com/course/otimizacao-de-desempenho-para-jobs-spring-batch/)

## Project Description
CompeticaoJob is a Spring Batch application designed to optimize job performance. It demonstrates best practices and configurations for building efficient batch processing applications using the Spring Batch framework.

## Features
- Configurable data source setup
- Custom job, step, reader, processor, and writer configurations
- Docker support for containerized deployment
- Unit and integration tests for robust development

## Prerequisites
- Java 21 (LTS)
- Maven 3.8+
- Docker (for containerized deployment)

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd CompeticaoJob
   ```

2. Build the project using Maven:
   ```bash
   ./mvnw clean install
   ```

3. Run the application:
   ```bash
   java -jar target/CompeticaoJob-0.0.1-SNAPSHOT.jar
   ```

## Docker Deployment
1. Build the Docker image:
   ```bash
   docker-compose build
   ```

2. Start the application using Docker Compose:
   ```bash
   docker-compose up
   ```

## Project Structure
```
CompeticaoJob
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.springbatch.competicao
│   │   │       ├── CompeticaoJobApplication.java
│   │   │       ├── config
│   │   │       ├── dominio
│   │   │       ├── job
│   │   │       ├── processor
│   │   │       ├── reader
│   │   │       ├── step
│   │   │       └── writer
│   │   └── resources
│   │       ├── application.properties
│   │       └── docker-compose.yml
│   └── test
│       └── java
│           └── com.springbatch.competicao
├── target
├── pom.xml
└── README.md
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- [Udemy Course: Optimization of Performance for Spring Batch Jobs](https://www.udemy.com/course/otimizacao-de-desempenho-para-jobs-spring-batch/)
