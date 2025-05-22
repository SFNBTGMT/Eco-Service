# Eco-Service

## Description
Site Ecommerce développé avec Laravel dédiée à la vente de produits zéro déchet.

## L'enonce du projet
[Eco-Services.pdf](https://github.com/user-attachments/files/20301656/Eco-Services.pdf)

## Screencast du projet

![Image](https://github.com/user-attachments/assets/2c48a980-8123-4962-92c9-467a270d16c0)

## Environnement
L'application utilise Docker pour la conteneurisation. Les services sont définis dans un fichier `docker-compose.yml`.

## Langages
- Interface Web : PHP (Laravel, Nginx)
- Paiement : Stripe
- Interface d'Administration : PHP (laravel, Filament)
- Base de données : phpMyAdmin
- Commande PDF : `Example` ([commande_5.pdf](https://github.com/user-attachments/files/20351667/commande_5.pdf))
  

## Installation

1. Clonez le dépôt :
    ```sh
    git clone https://github.com/SFNBTGMT/Eco-Service.git
    ```

2. Créez les fichiers de configuration nécessaires (si nécessaire) :
    - `.env` (pour les variables d'environnement)

## Configuration
Assurez-vous que le fichier `docker-compose.yml` contient les bonnes informations de configuration. Vous pouvez adapter les valeurs selon vos besoins.

## Exécution
1. Démarrez les conteneurs Docker :

```
docker-compose up --build
```
*[**Dépôt origin:** https://github.com/soufianeIT/test3FAP.git]*
