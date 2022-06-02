# Puppease

# 1.Présentation
L’application Puppease permettra à tous les maîtres souhaitant faire reproduire son animal (à but non lucratif), de trouver un partenaire à son compagnon canin de manière rapide efficace et adaptée aux critères de recherche.

# 2. Parcours utilisateur
Un utilisateur créé son profil ainsi qu'une page profil pour son chien. Une fois connecté l’utilisateur a accès à la liste de chiens inscrits et peut créer un nouveau profil pour son chien. Il pourra « liker » les autres profils de chien qui correspondent au maitre et envoyer une demande pour que les chiens se rencontrent. Le maître du chien concerné reçoit une notification pour lui indiquer que son chien a été « liké » et/ou qu’il a reçu une proposition de mise en relation.

## 3.1 Base de données
La base de données sera composée des tables Users, Dogs, Rencontres/DogMatches et city

## 3.2 Front
On se servira de Boostrap pour mettre en page et gérer la navbar, les formulaires et création de profil. On envisage Javascript pour donner du dynamisme au site et une meilleure expérience utilisateur.

Le code couleur précis sera à déterminer en équipe.

## 3.3 Backend
On utilisera Ruby on Rails

### API
"Stripe" pour la gestion des abonnements Premium avec plus d'accès
"Mailer" pour l’envoi de notification aux utilisateurs, email de bienvenue et email lorsqu'un utilisateur est interessé par le profil du chien

## 3.4 Besoins techniques
Concernant cette partie, il va falloir des compétences en front c’est à dire HTML, CCS et JS pour créer une interface agréable pour l’utilisateur. Il faudra également être capable de créer un architecture MVC et mettre en place tout ce qui va être fonctionnement production avec gitHub, Heroku et Pipeline. Et enfin faire fonctionner les APIs et autres gem qui seront nécessaires au fonctionnement du projet.

# 4. MVP
Utilisateur : connexion, navigation en tant qu’utilisateur, création de profil pour un chien. L’utilisateur peut se connecter et naviguer en tant qu’utilisateur au travers d’une session et créer des profils de chien, renseigner sa ville
Il y aura un index en homepage qui présentera tous les chiens présents sur le site
Un mailer fonctionnel

# 5. La version de présentation au jury
Mise en place d’un compte utilisateur premium payant par Stripe
Un dashboard utilisateur fonctionnel
Une fonction recherche selon différents critères de recherche par un système de filtre

# 6. Mentor
Ramzi Laifa
