# TP3 - Architecture Distribuée Commandes

## Objectifs
- Déployer une architecture distribuée avec plusieurs composants : Node.js, MongoDB, Redis, RabbitMQ, Nginx.
- Implémenter un flux complet : POST commande -> stockage MongoDB -> cache Redis -> notification RabbitMQ.
- Tester le load balancing et le cache avec Postman.

## Technologies utilisées
- Node.js v18+
- Express.js
- MongoDB
- Redis
- RabbitMQ
- Nginx
- Docker / Docker Compose
- Postman

## Structure du projet
- `app/` : code Node.js (server, routes, services, consumer)
- `nginx/` : configuration du load balancer
- `docker-compose.yml` : orchestration des conteneurs
- `TP3_Archi_Distribuee_Commandes.pdf` : compte rendu

## Lancer le projet
1. Installer Docker Desktop.
2. Depuis la racine du projet, exécuter :
   ```bash
   docker-compose up --build
