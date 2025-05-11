# 📌 Système de Gestion des Tâches

Une application web de gestion des tâches développée avec PHP, MySQL et XAMPP. Elle permet aux administrateurs de gérer les utilisateurs et les tâches, et aux employés de consulter et mettre à jour leurs propres tâches. Elle inclut également un système de notifications, des filtres avancés et un tableau de bord selon le rôle.

## 🚀 Technologies utilisées

- PHP 7.4 ou +
- MySQL 5.7 ou +
- HTML / CSS
- JavaScript
- XAMPP

---

## 🧰 Fonctionnalités principales

- 👥 **Gestion des rôles utilisateurs** : Administrateur et Employé
- ✅ **Gestion des tâches** : Créer, modifier, supprimer et consulter les tâches
- 🔐 **Authentification sécurisée** : Connexion avec contrôle des rôles
- 📋 **Filtrage des tâches** : Par statut, priorité, deadline
- 📆 **Échéances** : Visualisation des tâches en retard ou à venir
- 🔔 **Notifications** : Alertes pour tâches assignées ou mises à jour
- 👤 **Gestion de profil** : Modifier ses informations personnelles

---

## 🔐 Identifiants de connexion par défaut

### 👨‍💼 Administrateur :
- **Nom d'utilisateur :** `admin`
- **Mot de passe :** `123`

### 👷 Employé1:
- **Nom d'utilisateur :** `maguette`
- **Mot de passe :** `1234`

 ### 👷 Employé2:
- **Nom d'utilisateur :** `john`
- **Mot de passe :** `123`

### 👷 Employé3:
- **Nom d'utilisateur :** `oliver`
- **Mot de passe :** `123`

---

## 📂 Structure du projet

GESTIONDESTACHES/
├── app/                                 // Dossier principal de l'application
│   ├── Model/                           // Modèles : représentent les entités de l'application
│   │   ├── Notification.php             // Classe modèle Notification
│   │   ├── Task.php                     // Classe modèle Task
│   │   ├── User.php                     // Classe modèle User
│   │
│   ├── add-task.php                     // Traitement pour ajouter une tâche
│   ├── add-user.php                     // Traitement pour ajouter un utilisateur
│   ├── login.php                        // Traitement de la connexion (vérification)
│   ├── notification-count.php           // Compte des notifications non lues
│   ├── notification-read.php            // Marque les notifications comme lues
│   ├── notification.php                 // Récupération des notifications
│   ├── update-profile.php               // Traitement de mise à jour du profil utilisateur
│   ├── update-task-employee.php         // Traitement de mise à jour de tâche côté employé
│   ├── update-task.php                  // Mise à jour d'une tâche (admin)
│   ├── update-user.php                  // Mise à jour des infos utilisateur
│
├── css/
│   └── style.css                        // Fichier de style global
│
├── img/
│   └── user.png                         // Image utilisée dans le site 
│
├── inc/                                 // Fichiers partagés et réutilisables
│   ├── header.php                       // En-tête HTML commun
│   ├── nav.php                          // Barre de navigation
│
├── add-user.php                         // Formulaire ou page d'ajout utilisateur
├── create_task.php                      // Formulaire ou page de création de tâche
├── DB_connection.php                    // Script de connexion à la base de données
├── DB.sql                               // Script SQL de création de base
├── delete-task.php                      // Suppression d'une tâche
├── delete-user.php                      // Suppression d'un utilisateur
├── edit_profile.php                     // Page de modification de profil
├── edit-task-employee.php              // Page de modification des tâches pour employé
├── edit-task.php                        // Page de modification des tâches pour admin
├── edit-user.php                        // Page de modification des utilisateurs
├── index.php                            // Page d'accueil ou tableau de bord
├── login.php                            // Page de connexion
├── logout.php                           // Script de déconnexion
├── my_task.php                          // Liste des tâches de l’utilisateur connecté
├── notifications.php                    // Page affichant les notifications
├── profile.php                          // Page de profil
├── README.md                            // Fichier de documentation
├── task_management_db.sql              // Base de données du projet
├── tasks.php                            // Liste générale des tâches
├── user.php                             // Liste générale des utilisateurs


## ⚙️  Structure du projet



Cloner le dépôt Git :
git clone https://github.com/Groupe6VNB/gestion-taches.git
Copier le dossier dans htdocs de XAMPP.
Importer le fichier SQL dans phpMyAdmin ( task_management_db.sql).
Modifier les identifiants de connexion dans includes/config.php.
Accéder à l’application via :
http://localhost/gestiondestaches


## 👤 Auteur

Nom : Magatte Seye
Formation : BTS SIO – Option SLAM
Année scolaire : 2024–2025

 
## 🌐 Licence 

Ce projet est open source sous licence MIT.
Il peut être utilisé, modifié et redistribué librement tant que la mention de l’auteur est conservée.



