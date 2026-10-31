# PORTFOLIO DATA ENGINEER

**Webactiviti**  
*Élève Data Engineer — Parcours OpenClassrooms (Bac+5 / RNCP Niveau 7)*  


---

## 1. PROFIL & OBJECTIFS

Data Engineer en formation au sein du parcours certifiant **OpenClassrooms**, je me spécialise dans la conception, la modélisation, l'automatisation et l'optimisation des architectures de données complexes. 

Grâce à une série de projets pratiques basés sur des cas d'entreprise réels, j'ai développé une solide maîtrise des pipelines ETL/ELT (batch et streaming), du stockage distribué, du Cloud (AWS / GCP), de l'orchestration de flux (Airflow) et des bonnes pratiques DevOps appliquées aux données (Docker, CI/CD). Mon objectif est de garantir la qualité, la disponibilité et la gouvernance des données pour les équipes Analytics et Data Science.

---


## 2. PROJETS DE LA FORMATION OPENCLASSROOMS

### Projet 1 : Conception d'une base de données relationnelle et modélisation SQL
- **Objectif :** Analyser le besoin métier d'une entreprise, concevoir un modèle conceptuel et logique de données (MCD/MLD) et implémenter la base relationnelle.
- **Réalisations :**
  - Création du schéma d'informations normalisé (3NF) et rédaction des scripts DDL SQL.
  - Implémentation des contraintes d'intégrité, indexations et requêtes complexes d'agrégation.
- **Technologies :** PostgreSQL, MySQL, SQL, draw.io / dbdiagram.io.

### Projet 2 : Création d'un pipeline ETL automatisé en Python
- **Objectif :** Extraire des données depuis diverses sources (APIs REST, fichiers CSV/JSON), les nettoyer et les charger dans un Data Mart.
- **Réalisations :**
  - Développement de scripts Python modularisés et gestion robuste des erreurs/logs.
  - Transformation des données brutes et création de tables de faits et de dimensions (schéma en étoile).
- **Technologies :** Python (Pandas, Requests), PostgreSQL, Docker.

### Projet 3 : Mise en place d'un Data Lake Cloud et traitement Big Data
- **Objectif :** Stocker et traiter de volumineux jeux de données non structurés/semi-structurés dans un environnement Cloud.
- **Réalisations :**
  - Configuration d'un Data Lake multi-couches (*Bronze, Silver, Gold*) sur Amazon S3 / Google Cloud Storage.
  - Écriture de scripts PySpark pour traiter des gigaoctets de données de manière distribuée.
  - Conversion des fichiers en formats optimisés pour les requêtes (Parquet / ORC).
- **Technologies :** AWS (S3, Glue, Athena) ou GCP, Apache Spark (PySpark), Parquet.

### Projet 4 : Orchestration de workflows de données avec Apache Airflow
- **Objectif :** Remplacer des tâches manuelles et scripts cron par une orchestration centralisée et tolérante aux pannes.
- **Réalisations :**
  - Conception de DAGs Airflow complexes intégrant des opérateurs personnalisés et des capteurs (*sensors*).
  - Gestion des dépendances, des retentatives automatiques et des alertes d'échec (Slack / Email).
  - Validation automatique de la qualité des données avant injection (*Great Expectations*).
- **Technologies :** Apache Airflow, Python, Docker, Great Expectations.

### Projet 5 : Traitement de flux de données en Temps Réel (Streaming)
- **Objectif :** Capturer et analyser un flux d'événements en temps réel pour alimenter un tableau de bord analytique.
- **Réalisations :**
  - Déploiement d'un cluster Kafka pour la gestion des événements entrants.
  - Traitement des données en continu via Spark Structured Streaming (agrégation par fenêtres glissantes).
- **Technologies :** Apache Kafka, PySpark Structured Streaming, Docker Compose, Grafana.

### Projet 6 : Industrialisation et MLOps d'un pipeline Data
- **Objectif :** Assurer la conteneurisation, le déploiement continu et la surveillance d'une chaîne de traitement de données.
- **Réalisations :**
  - Écriture des fichiers Dockerfile et orchestration multi-services avec Docker Compose.
  - Implémentation d'un pipeline CI/CD avec GitHub Actions (tests unitaires pytest, linters flake8/black).
- **Technologies :** Docker, GitHub Actions, pytest, Terraform.

---


