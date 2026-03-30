# TP2 - Monolithe Modulaire

## Objectifs
- Étendre l’application monolithique pour gérer plusieurs entités : Produits, Clients et Commandes.
- Introduire une architecture modulaire avec DTOs, Mappers et Services.
- Tester les différentes API REST avec Postman.

## Technologies utilisées
- Java 17
- Spring Boot (Web, Data JPA, Validation)
- Maven
- PostgreSQL + pgAdmin
- IntelliJ IDEA
- Postman

## Structure du projet
- `product/` : gestion des produits (DTO, Mapper, Service, Controller, Repository, Model)
- `customer/` : gestion des clients
- `order/` : gestion des commandes
- `application.properties` : configuration de la base de données
- `pom.xml` : configuration Maven

## Lancer le projet
1. Installer JDK 17 et Maven.
2. Configurer PostgreSQL avec une base `ecommerce`.
3. Modifier `application.properties` si besoin (URL, username, password).
4. Lancer le projet avec :
   ```bash
   mvn spring-boot:run
