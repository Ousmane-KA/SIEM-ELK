


# SIEM-ELK

![image](https://github.com/user-attachments/assets/f9ea056e-0719-458f-aff0-3d7630c1a4ec)




Un **SIEM Elastic (Security Information and Event Management)** est une solution intégrée d'Elastic Stack qui permet de détecter, enquêter et répondre aux menaces en temps réel.

Elle collecte des journaux et événements de multiples sources (serveurs, applications, réseaux) via Elasticsearch, les enrichit et les analyse avec des règles de détection configurables. Kibana fournit des interfaces intuitives pour la visualisation, la corrélation des incidents et l'orchestration des réponses.

**Beats** : Collecte et envoie des données brutes (journaux, métriques) depuis les sources vers Logstash ou Elasticsearch.

**Logstash** : Traite, transforme et enrichit les données entrantes avant de les envoyer à Elasticsearch pour stockage et indexation.

**Elasticsearch** : Stocke et indexe les données, tandis que **Kibana** fournit une interface pour visualiser, analyser et interagir avec ces données.
