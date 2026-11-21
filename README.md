# Spring Cloud Config Server Repository ⚙️☁️

Centralized Git-backed configuration repository consumed by **Spring Cloud Config Server** to externalize and distribute environment properties across microservices dynamically.

---

## 📁 Managed Configurations

- **`department-service.properties`**: Configuration for `DEPARTMENT-SERVICE` (DataSource, Hibernate, Eureka Client registry).
- **`employee-services.properties`**: Configuration for `EMPLOYEE-SERVICE` (DataSource, Hibernate, Server Port, Eureka Client registry).

---

## 🛠️ Usage with Spring Cloud Config Server

Point your Spring Cloud Config Server `application.properties` to this Git repository:

```properties
spring.cloud.config.server.git.uri=https://github.com/aniketjawanjal/config-server-repo
spring.cloud.config.server.git.default-label=main
```

---

## 👤 Author
- **Aniket Jawanjal** - [GitHub Profile](https://github.com/aniketjawanjal)
