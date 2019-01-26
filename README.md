## SPRING BOOT ADMIN SERVER

Server for monitoring spring boot applications

### Enabling application as Spring Boot Admin Client

* Add dependency to `build.gradle`

```code
dependencies {
    implementation('de.codecentric:spring-boot-admin-starter-client:2.1.2')
}
```

* Add configuration to `application.yaml`

```code
spring:
  application:
    name: application-name
  boot:
    admin:
      client:
        # spring boot admin server url and port
        url: http://localhost:9999
```

## USEFUL LINKS

* [Spring Boot Admin Server Github](https://github.com/codecentric/spring-boot-admin)