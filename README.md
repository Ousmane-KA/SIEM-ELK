


# SIEM-ELK

![image](https://github.com/user-attachments/assets/f9ea056e-0719-458f-aff0-3d7630c1a4ec)




Un **SIEM Elastic (Security Information and Event Management)** est une solution intégrée d'Elastic Stack qui permet de détecter, enquêter et répondre aux menaces en temps réel.

Elle collecte des journaux et événements de multiples sources (serveurs, applications, réseaux) via Elasticsearch, les enrichit et les analyse avec des règles de détection configurables. Kibana fournit des interfaces intuitives pour la visualisation, la corrélation des incidents et l'orchestration des réponses.

**Beats** : Collecte et envoie des données brutes (journaux, métriques) depuis les sources vers Logstash ou Elasticsearch.

**Logstash** : Traite, transforme et enrichit les données entrantes avant de les envoyer à Elasticsearch pour stockage et indexation.

**Elasticsearch** : Stocke et indexe les données, tandis que **Kibana** fournit une interface pour visualiser, analyser et interagir avec ces données.

## A) Mise en place du Stack ELK : 

- Il faudra installer docker et docker compose :
suivre la documentation : https://docs.docker.com/engine/install/debian/

- On va créer un dossier projet avec la commande :
  > mkdir -p PROJET-ELK
  > cd PROJET-ELK
- On va créer les volumes pour nos conteneurs docker :

**Volume pour elasticsearch :**
>mkdir -p elastic
****
>chmod 777 elastic
****

**Volume pour logstash :**
>mkdir -p logstash
****
>chmod 777 logstash

****

### a) Configuration de elasticsearch:

On va créer un fichier de configuration qu'on va nommer logstash.conf
****
>cd logstash
>nano logstash.yml
*****
- On copie le contenu du fichier logstash.conf et on enregistre.

### b) Configuration de logstash:

On va créer un fichier de configuration qu'on va nommer logstash.conf
****
>cd logstash
>nano logstash.conf
****
On copie le contenu du fichier logstash.conf et on enregistre.


### c) Conguiration de kibana : 
### d) Implémentation du docker compose : 
> Au niveau de la racine du projet on va créer un fichier docker-compose.yml
> Voir le fichier de docker compose : 

