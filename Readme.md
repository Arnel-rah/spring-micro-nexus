# Spring Raw Postgres API 🚀

[![Tech Stack](https://skillicons.dev/icons?i=java,spring,postgres,docker)](https://skillicons.dev)

Projet d'apprentissage visant à maîtriser **Spring Boot** et la gestion native de **PostgreSQL** sans ORM (JPA) ni JdbcTemplate.

## 🎯 Objectifs
- Gestion manuelle du cycle de vie des connexions JDBC.
- Implémentation du pattern DAO avec SQL brut.
- Gestion des transactions et des exceptions via `RuntimeException`.

## 🛠️ Installation
1. Cloner le repo.
2. Configurer le fichier `.env` (voir `.env.example`).
3. Lancer la base de données :
   ```bash
   docker-compose up -d