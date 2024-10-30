# Objectifs journaliers

## Mercredi 30/10/2024 :

### Introduction à PostgreSQL et DCL

- [ ] Découverte de PostgreSQL
  - [ ] Identifier les différences entre MySQL et PostgreSQL
  - [ ] Savoir Expliquer les avantages de PostgreSQL
  - [ ] Savoir Choisir les cas d'usage adaptés à PostgreSQL

- [ ] Installation et Configuration
  - [ ] Installation de PostgreSQL sur la machine
  - [ ] Installation de pgAdmin 4
  - [ ] Installation de pgcli
  - [ ] Configuration initiale
    - [ ] Ports
    - [ ] Mot de passe postgres
    - [ ] Création du premier utilisateur
  - [ ] Test de la connexion

- [ ] Data Control Language (DCL)
  - [ ] Gestion des utilisateurs
    - [ ] Savoir construire des requêtes CREATE USER
    - [ ] Savoir modifier des utilisateurs avec ALTER USER
    - [ ] Savoir supprimer des utilisateurs avec DROP USER
    - [ ] Savoir utiliser les rôles PostgreSQL
  
  - [ ] Gestion des droits
    - [ ] Savoir attribuer des privilèges avec GRANT
      - [ ] Droits sur les bases de données
      - [ ] Droits sur les tables
      - [ ] Droits sur les colonnes
    - [ ] Gérer la révocation avec REVOKE
      - [ ] Comment retirer des droits sur une base de données, une table ou une colonne ?
      - [ ] Quel est l'impact d'une révocation en cascade ?

  - [ ] Les bonnes pratiques de sécurité
    - [ ] Comment appliquer le principe du moindre privilège dans PostgreSQL ?
    - [ ] Quand utiliser des rôles plutôt que des utilisateurs individuels ?
    - [ ] Comment auditer efficacement les droits d'accès ?