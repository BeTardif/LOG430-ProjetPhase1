# Objectif d'appretissage #

1. Exposer une API RESTful conforme aux bonnes pratiques, documentée (OpenAPI/Swagger), sécurisée (CORS, auth de base/JWT)
2. Mettre en place l'observabilité (logs structurés, métriques Prometheus, dashboards Grafana) et mesurer les 4 Golden Signals sous charge réaliste (k6/JMeter)
3. Optimiser la performance par load balancing (NGinx/HAProxy/Traefik) et caching(memoire/Redis) sur endpoints critiques.
4. Migrer vers des microservices et publier via une API Gateway (Kong/KrakenD/Spring Cloud Gateway), avec routage, sécurité et comparaisons A/B (direct vs gateway).
5. Respecter le cahier de charge: domaines (Comptes & Clients, Ordres & Appariement, Données de marché, Portefeuilles), NFR (latence P95, throughput, dosponibilité) et exigences de conformité/audit.
6. Maintenir la documentation architecturale (Arc42 et 4+1) et consigner les décisions (ADRs).