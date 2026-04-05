# TP4 - Architecture Orientée Services (SOA)

## Objectifs
- Comprendre les principes de l’architecture SOA.
- Créer des microservices indépendants avec Spring Boot.
- Implémenter la communication inter-services via REST et Feign.
- Utiliser Eureka pour la découverte des services.
- Tester l’API avec Postman.

## Technologies utilisées
- Java 17
- Spring Boot (Web, Data JPA, H2, Eureka, Feign, Gateway)
- Maven
- IntelliJ IDEA
- Postman

## Structure du projet
- `eureka-server/` : registre des microservices (port 8761).
- `product-service/` : gestion des produits (port 8081).
- `order-service/` : gestion des commandes (port 8082).
- `api-gateway/` : point d’entrée unique (port 8080, optionnel).
- `TP4_Architecture_SOA.pdf` : compte rendu.

## Lancer le projet
1. Démarrer `eureka-server` :
   ```bash
   mvn spring-boot:run
