# TP1 - Monolithe Simple

## Lancer le projet
1. Installer JDK 17 et Maven.
2. Configurer PostgreSQL avec une base `ecommerce`.
3. Modifier `application.properties` si besoin.
4. Lancer le projet avec :
   mvn spring-boot:run

## Tester avec Postman
- GET /api/products → liste des produits
- POST /api/products → créer un produit
- PUT /api/products/{id} → modifier un produit
- DELETE /api/products/{id} → supprimer un produit
