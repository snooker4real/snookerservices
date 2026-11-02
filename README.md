# snookerservices

Microservices

**Stack** : Java 17, Maven, Spring Boot

## Démarrage

```bash
mvn clean install   # construire et tester
mvn spring-boot:run   # démarrer l'application
mvn test   # lancer les tests
```

## Docker

```bash
docker compose -f docker-compose.yml up --build
```

## Structure

```
customer/
docker-compose.yml
pom.xml
```
