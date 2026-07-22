Java Backend Developer

I develop backend services with Java and Spring Boot, focusing on REST APIs, transactional business logic, data consistency, security, event-driven integrations and automated testing.

Core stack

- Java: Java 17/21, Collections, Stream API, Multithreading
- Backend: Spring Boot, Spring Web, Spring Data JPA, Spring Security, Hibernate
- Databases: PostgreSQL, SQL, Liquibase
- Messaging: Apache Kafka
- Testing: JUnit, Mockito, MockMvc, Testcontainers
- Tools: Maven, Git, Docker, Docker Compose, OpenAPI

Featured projects

"Bank Cards Service" (https://github.com/igorkosalapov/bank_rest)

Backend service for managing users, bank cards and transfers.

- JWT authentication and role-based access for "USER" and "ADMIN"
- transactional transfers with pessimistic locking
- fixed record-locking order for concurrent operations
- AES-GCM encryption and masking of card numbers
- PostgreSQL migrations with Liquibase
- Docker Compose and OpenAPI documentation

Stack: Java 17, Spring Boot, Spring Security, Spring Data JPA, PostgreSQL, Liquibase, Docker Compose

---

"Task Management Service" (https://github.com/igorkosalapov/task-management-service)

REST service for managing tasks, assignees and statuses.

- task lifecycle management and pagination
- Kafka events for task creation and assignment
- PostgreSQL persistence
- unit, MVC and integration tests
- end-to-end integration scenario: "HTTP → PostgreSQL → Kafka"
- isolated PostgreSQL and Kafka environments with Testcontainers

Stack: Java 21, Spring Boot, Spring Data JPA, PostgreSQL, Apache Kafka, Testcontainers, Docker Compose

---

"Explore With Me" (https://github.com/igorkosalapov/java-explore-with-me)

Multi-module platform for publishing, moderating and searching events.

- separate main and statistics services
- two PostgreSQL databases
- inter-service communication over HTTP
- dynamic event filtering with JPA Specifications
- event search by geographical area
- Docker Compose deployment

Stack: Java 21, Spring Boot, Spring Data JPA, PostgreSQL, Docker Compose, Maven

Contact

- Telegram: "@blackscreen777" (https://t.me/blackscreen777)
- Email: "igor.kosalapov@gmail.com" (mailto:igor.kosalapov@gmail.com)