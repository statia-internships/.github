# Statia

Statia rend les données statistiques officielles du Sénégal plus accessibles, compréhensibles et exploitables.

Le projet s’appuie sur les données de l’Agence nationale de la statistique et de la démographie du Sénégal (ANSD) et propose une interface assistée par intelligence artificielle pour explorer les indicateurs, interroger les jeux de données et obtenir des réponses documentées.

## Projets

### [statia-backend](https://github.com/statia-internships/statia-backend)

Backend de Statia, développé en Python.

Il fournit :

- une API web pour l’application Statia ;
- un serveur MCP pour l’intégration avec des assistants comme Claude Desktop et Cursor ;
- l’accès et le traitement des données statistiques de l’ANSD.

### [statia-docs](https://github.com/statia-internships/statia-docs)

Documentation de référence du projet.

Elle regroupe :

- le cadrage fonctionnel ;
- l’architecture technique ;
- les décisions d’architecture ;
- les contrats d’API et de données ;
- les critères d’acceptation ;
- les procédures d’exploitation ;
- les références SDMX de l’ANSD.

## Principes

- Une information doit avoir une source de vérité unique.
- Les contrats et décisions d’architecture sont documentés avant leur implémentation.
- Les données et chiffres dérivés sont calculés par le code, jamais par le modèle de langage.
- La fiabilité, la traçabilité et la clarté priment sur la complexité.
- Les évolutions importantes sont relues et documentées.

## État du projet

Statia est actuellement en phase de conception et de développement. L’architecture, les contrats principaux et les premières décisions techniques sont documentés dans `statia-docs`.

## Documentation

Pour comprendre le projet, commencer par :

1. le périmètre fonctionnel ;
2. les phases de développement ;
3. l’architecture technique ;
4. les décisions d’architecture ;
5. les contrats de données et d’API.

---

Statia — rendre les statistiques officielles plus accessibles.
