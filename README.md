


# SIEM-ELK




## Plan du projet : 

![image](https://github.com/user-attachments/assets/f5ec4433-0711-4cc7-b69a-4bdd1e0e1b64)

### Introduction :

Le SIEM ELK (Elasticsearch, Logstash, Kibana) est une solution open-source de gestion des logs et de surveillance en temps réel. Elasticsearch stocke et indexe les données, Logstash les collecte et les transforme, tandis que Kibana permet leur visualisation et analyse. Il est utilisé pour la cybersécurité, la détection d’anomalies et la conformité.

### Création du dossier projet et les sous dosssiers :

```bash
STACK-ELK
├── docker-compose.yml
├── elasticsearch
│   ├── config
│   │   └── elasticsearch.yml
│   ├── elastic-data
├── kibana
│   ├── config
│   │   └── kibana.yml
├── logstash
│   ├── config
│   │   └── logstash.yml
│   ├── pipeline
│   │   └── logstash.conf
```


On exécute la commandes suivantes dans le terminal :  
```bash
mkdir -p STACK-ELK/{elasticsearch/{config,elastic-data},kibana/config,logstash/{config,pipeline}}
```

---

### On implémente les fichier de configuration ( voir fichier : elasticsearch.yml, kibana.yml, logstash.yml, logstash.conf ) 
```bash
nano STACK-ELK/elasticsearch/config/elasticsearch.yml
nano STACK-ELK/kibana/config/kibana.yml
nano STACK-ELK/logstash/config/logstash.yml
nano STACK-ELK/logstash/pipeline/logstash.conf
touch STACK-ELK/docker-compose.yml
```
### On implémente le docker compose : ( voir fichier docker-compose.yml ) 

```bash
nano STACK-ELK/docker-compose.yml
```

C'est prêt pour la configuration et le déploiement avec Docker Compose 🚀
