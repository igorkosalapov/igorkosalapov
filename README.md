### Java Backend Developer

Java 17/21 · Spring Boot · PostgreSQL · Apache Kafka · Docker

## About me

I develop backend services with Java and Spring Boot, focusing on REST API design, transactional business logic, data consistency, application security, event-driven integrations and automated testing.

I work with PostgreSQL, Spring Data JPA, Hibernate, Spring Security, Apache Kafka, Liquibase, Docker and Testcontainers.

Alongside backend development, I have more than 7 years of experience in industrial production and currently lead a shift team of 5 employees. This experience has taught me to take responsibility for results, distribute tasks, coordinate with other teams and make decisions in non-standard situations.

I am open to remote Java Backend Developer opportunities.

## Tech stack

- **Java:** Java 17/21, Java Core, Collections Framework, Stream API
- **Spring:** Spring Boot, Spring Web, Spring Data JPA, Spring Security
- **Persistence:** PostgreSQL, SQL, Hibernate, Liquibase
- **Messaging:** Apache Kafka
- **Testing:** JUnit 5, Mockito, MockMvc, Testcontainers
- **Tools:** Maven, Git, Docker, Docker Compose, OpenAPI / Swagger

## Selected projects

### [Bank Cards Service](https://github.com/igorkosalapov/bank_rest)

Backend service for managing users, bank cards and transfers.

**Key features:**

- authentication and authorization with Spring Security and JWT;
- role-based access for `USER` and `ADMIN`;
- transactional transfers with balance, ownership and card status validation;
- pessimistic locking and deterministic record-locking order for concurrent operations;
- AES-GCM encryption and masking of card numbers;
- database migrations with Liquibase;
- API documentation with OpenAPI;
- local environment with Docker Compose.

**Stack:** Java 17, Spring Boot, Spring Security, Spring Data JPA, PostgreSQL, Liquibase, JWT, Docker Compose, OpenAPI, JUnit, Mockito.

---

### [Task Management Service](https://github.com/igorkosalapov/task-management-service)

Backend service for managing tasks, assignees and task statuses.

**Key features:**

- REST API for creating, retrieving and updating tasks;
- task assignment, status management and pagination;
- PostgreSQL persistence with Spring Data JPA;
- Apache Kafka events for task creation and assignment;
- unit and web-layer tests with JUnit, Mockito and MockMvc;
- end-to-end integration scenario: `HTTP → PostgreSQL → Kafka`;
- isolated PostgreSQL and Kafka environments with Testcontainers;
- local environment with Docker Compose.

**Stack:** Java 21, Spring Boot, Spring Data JPA, PostgreSQL, Apache Kafka, Testcontainers, Docker Compose, JUnit, Mockito, MockMvc, Maven.

---

### [Explore With Me](https://github.com/igorkosalapov/java-explore-with-me)

Multi-module platform for publishing, moderating and discovering events.

**Key features:**

- separate main application and statistics service;
- two PostgreSQL databases;
- REST APIs for public users, registered users and administrators;
- event moderation and participation request management;
- inter-service communication over HTTP;
- dynamic event filtering with JPA Specifications;
- geographical event search within a specified area;
- integration tests and Docker Compose environment.

**Stack:** Java 21, Spring Boot, Spring Data JPA, Hibernate, PostgreSQL, REST API, Docker Compose, Maven, JUnit.

## Contact

- **Telegram:** [@blackscreen777](https://t.me/blackscreen777)
- **Email:** [ikosalapov@yandex.ru](mailto:ikosalapov@yandex.ru)