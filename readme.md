# MDS-APIODM-M1-2324

Réalisation d'un API sur Star Wars
- Respect du modèle de Richardson
- Respect des 5 règles du REST
- Choix de la technologie libre par groupe

travail en groupe de 2 ou 3 au choix
Github obligatoire

## Objectif : 

1. réintégrer l'ensemble des données, puis proposer des routes pour les redistribuer.
2. Documenter votre API avec [SWAGGER](https://editor.swagger.io/) 
3. Mettre en place une authentification avec JWT et les routes qui vont avec
4. [AJOUT 23/01/24] Mettre en place un système de journalisation (Sentry) pour la gestion de toutes les erreurs


## Liens utiles

- L'api : https://swapi.dev/
- Richardson : https://guide-api-rest.marmicode.fr/api-rest/le-modele-de-maturite-de-richardson (SWAPI intègre déjà le modèle de richardson !)
- https://editor.swagger.io/
- https://www.postman.com/
- [AJOUT 23/01/24] https://docs.sentry.io/
- [AJOUT 23/01/24] https://fr.agilitest.com/blog/unlocking-the-power-api-testing-comprehensive-guide

## Dates cours : 

- mercredi 25 octobre 2023 - jour entier
- mardi 14 novembre 2023 - jour entier
- mardi 23 janvier 2024 - jour entier
- mardi 13 février 2024 - jour entier
- mardi 05 mars 2024 - jour entier ==> 3h éval l'apres-midi - 30 minutes par groupe (10/15 mins prez + Q/R + notation)

## Barème d'évaluation
- les 5 routes du modèle REST sont implémentées pour la ressource PEOPLE (Create, Read ALL, Read ONE, Update, Delete)
- les 5 routes du modèle REST sont implémentées pour la ressource PLANETS (Create, Read ALL, Read ONE, Update, Delete)
- les 5 routes du modèle REST sont implémentées pour la ressource FILMS (Create, Read ALL, Read ONE, Update, Delete)
- les 5 routes du modèle REST sont implémentées pour la ressource SPECIES (Create, Read ALL, Read ONE, Update, Delete)
- les 5 routes du modèle REST sont implémentées pour la ressource VEHICLES (Create, Read ALL, Read ONE, Update, Delete)
- les 5 routes du modèle REST sont implémentées pour la ressource STARSHIPS (Create, Read ALL, Read ONE, Update, Delete)
- un fichier readme est présent et explique ce qu'est le modèle de richardson et comment vous l'avez respecté
- un fichier swagger.json doit être présent et contenir votre documentation SWAGGER (doit fonctionner sur https://editor.swagger.io/)
- JWT est implémenté et l'ensemble des routes autre que auth sont bloquées (optionnel)

## Groupes 
- 1 : Pierre, Nathan, Léo (https://github.com/PierrePineau/swapi-fastify)
- 2 : Moussa, Houcine, Théo (https://github.com/HC-DevE/swapi-clone)
- 3 : Hugo, Guillaume, Davy (https://github.com/Bryndye/SWAPIBELIKE)
- 4 : Anaelle, Jules (https://github.com/ZeaNa7/api-swapi)
- 5 : Clément, Walid, Bastien (https://github.com/BastiennM/tp_api_rest)
- 6 : Lisa, Yassine (https://github.com/Yassinedevs/API-REST)

## [AJOUT 23/01/24] Travaux de recherches complémentaires (à intégrer dans la présentation)

- Fonctionnement global de POSTMAN (incluant la gestion des routes (dossiers, etc...), la gestion des variables (internes à postman) et la gestion automatique des bearers via l'outil)
- Étudier les tests de montée en charge :
  - Enjeux et facteurs
  - les différents types (résistance, endurance, pointe, performance)
  - identifier et décrire succinctement les outils de monitoring open-source et cloud du marché
  - identifier et décrire succinctement les outils de test de charge open-source et cloud du marché



## Présentation orale par groupe de chaque travaux avec justifications le DERNIER JOUR !
