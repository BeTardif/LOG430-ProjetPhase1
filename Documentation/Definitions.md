# Définitions #
Ce document tient à décrire les définitions des éléments indiqués dans l'énoncé de laboratoire.

### Lexique générale
* **Framework**: Struture logicielle qui dicte la rédaction du code et de sa logique. Peut être composé de librairies.
* **Librairie**: Ensemble de classes et de fonctions pouvant être utilisées lors de l'exécution de tâches et logiques spécifiques.
* **Service**: Instance active de code qui utilise des frameworks et des librairies pour offrir un service.

### Lexique du contexte ### 
* **API**: (Application Programming Interface) Ensemeble de règles et protocoles qui permettent à deux logiciels d'intéragir entre eux. 
* **API Gateway**: *Reverse proxy* L'API Gateway se situe entre un client et une collection de BackEnd. Il permet l'utilisation d'une multitudes d'API par lesquels un utilisateur voit de l'information. (Service based architecture).
* **API RESTful**: Interface qui permet la communication entre différentes application via le WEB.
* **Arc42**: Gabarit pour la documentation d'un logiciel.
* **Basic Auth**: Authentification de base, la paramètres sont envoyés dans le header de la requête.
* **CORS**: Cross-Origin Resource Sharing. Assure la conformité de l'échange des ressources entre les différentes origines d'une application.
* **DDD**: Domain-driven design. Design piloté par le cahier des charges.
* **Grafana**: Permet la représentation des données dans des dashboards.
* **JWT**: (JSON Web Token) Méthode d'authentification par jeton qui premet de transmettre de l'information en formet JSON entre deux entités. Communément utiliser par les APIs et les microservices. 
* **Kong/KrakenD/Spring Cloud Gateway**: Direction vers les microservices. Outils d'APIGateway. 
* **K6/JMeter**: Outils de tests de charge. Cet outil serviront au load balancing. K6 est la version moderne et JMeter est le vétéran.
* **Middelware**: Code entre deux couches d'un logiciel. Par exemple, du code qui s'applique sur toutes les requêtes HTTP de l'application.
* **NFR**: Non-fonctional Requirements, exigence de qualité (Quality attributes) QA Architeture
* **NGINX/HAProxy/Traefik**: outils de load balancing, permet de séparer les charges. Facilite le scaling de l'application.
* **OpenAPI/Swagger**: (Noter que OpenAPI et Swagger sont la même chose) Outil servant à la spécification d'un APIRest. Il s'agit d'un fichier JSON qui décrit les endpoints, les méthodes hTTP, les paramètres d'accès ainsi que les réponses possibles.
* **Prometheus Metric**: Metrique composée de trois éléments qui permettent la création d'un log affichant le nom, les labels et la valeur.
* **REST**: (Representational State Transfer) Style d'architecture permettant des interactions entre des services web.
* **4 Golden Signal**s: Principe par lequel quatre éléments d'un logiciel devrait être observés. Ces éléments sont les suivant: la latence, le trafic, les erreurs et la saturation. 
* **4+1**: Gabarit pour la documentation d'un logiciel qui décrit quatre composantes générales qui forme un ensemble de documentation. 