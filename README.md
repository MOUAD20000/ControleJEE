# ControleJEE

# 1-Objectif :

Créer une application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client.
Micro-service customer-service qui permet de gérer les client
Micro-service inventory-service qui permet de gérer les produits
Gateway Spring cloud Gateway avec une Configuration statique du système de routage
Annuaire Eureka Discrovery Service
Configuration dynamique des routes de la gateway
Service de facturation Billing-Service en utilisant Open Feign
Client Web Angular (Clients, Produits, Factures)
Déployer le serveur keycloak :
- Créer un Realm
- Créer un client à sécuriser
- Créer des utilisateurs
- Créer des rôles
- Affecter les rôles aux utilisateurs
- Tester les différents modes d'authentification avec Postman en montrant les contenus de Access-Token, Refresh Token
Sécuriser les micro-services et le frontend angular en déployant les adaptateurs Keycloak

# 2-Architecture de l'activité pratique :

![image](https://user-images.githubusercontent.com/82736657/209477287-32c6014d-fefa-43c5-88b4-8c45b7c202f1.png)

# 3-Simulation :

Eureka
![eureka](https://user-images.githubusercontent.com/82736657/209446684-c1958ae9-4616-4ff1-8691-d593b8de59ff.png)

liste des produits 

![Capture1](https://user-images.githubusercontent.com/82736657/209446706-c211ed06-9d53-4235-8ac9-4e399cc958f1.PNG)

liste des clients

![Capture2](https://user-images.githubusercontent.com/82736657/209446715-4e8aa204-780b-4eac-a7f5-3fe19a2908cb.PNG)

Liste des factures d'un client 

![image](https://user-images.githubusercontent.com/82736657/209477340-f9bade7f-5583-4610-a547-08546ce235b9.png)

# Keycloak :

![image](https://user-images.githubusercontent.com/82736657/209477403-286f4981-5937-4b25-a3cc-f96e05f6dcb8.png)

Authentication with client secret

![image](https://user-images.githubusercontent.com/82736657/209477419-b07f9042-5a32-4106-8716-3ddb3662ceb1.png)

authentication with password

![image](https://user-images.githubusercontent.com/82736657/209477441-9e6abd17-3f89-4ff5-af59-3d1179b78afe.png)

authentication with refresh token

![image](https://user-images.githubusercontent.com/82736657/209477452-44fac8d0-11a6-4747-b06e-e9a0df25f15a.png)



