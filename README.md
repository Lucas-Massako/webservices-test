# webservices-test
# 🚀 Dashboard d'Initiation aux Web Services (API)

![Status](https://img.shields.io/badge/Status-Completed-success)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

Ce projet est une application web interactive regroupant 3 mini-projets. L'objectif principal était d'apprendre à interagir avec des **API REST (Web Services)**, manipuler des données **JSON** et gérer l'asynchronisme en JavaScript.


---

## 📋 Fonctionnalités

Le dashboard est divisé en trois cartes distinctes, chacune explorant une facette différente des Web Services :

### 1. 🐶 Générateur de Chiens (API Simple)
* **Concept :** Affiche une photo de chien aléatoire à chaque clic.
* **Technique :** Appel `GET` simple sans paramètres.
* **API utilisée :** [Dog CEO API](https://dog.ceo/dog-api/)

### 2. 🔮 Le Devin d'Âge (API avec Paramètres Utilisateur)
* **Concept :** L'utilisateur entre un prénom, et l'API estime son âge moyen en France.
* **Technique :** Construction dynamique de l'URL avec injection de variables (Template Literals) et paramètres de requête (`?name=...&country_id=FR`).
* **API utilisée :** [Agify.io](https://agify.io/)

### 3. ✈️ Radar Vols Paris (Données complexes en temps réel)
* **Concept :** Affiche la liste des avions survolant actuellement la région parisienne.
* **Technique :** Utilisation de coordonnées géographiques (Latitude/Longitude) pour filtrer les résultats et manipulation d'un tableau de données (Arrays) complexe.
* **API utilisée :** [OpenSky Network](https://opensky-network.org/)

---

## 🧠 Concepts Appris

Ce projet m'a permis de comprendre et de mettre en pratique les concepts suivants :

* **Fetch API :** Utilisation de la méthode native `fetch()` pour effectuer des requêtes HTTP.
* **Async / Await :** Gestion de l'asynchronisme pour attendre la réponse du serveur sans bloquer l'interface.
* **DOM Manipulation :** Mise à jour dynamique du HTML (images, listes, textes) avec les données reçues.
* **Gestion des Erreurs :** Utilisation de `try...catch` pour gérer les cas où l'API ne répond pas ou si l'utilisateur est hors ligne.
* **JSON :** Conversion des réponses brutes en objets JavaScript exploitables (`response.json()`).


---

## 🚧 Améliorations possibles

Voici quelques idées pour faire évoluer ce projet dans le futur :
* [ ] Ajouter une carte météo (OpenWeatherMap) nécessitant une clé API.
* [ ] Permettre à l'utilisateur de choisir ses propres coordonnées GPS pour le radar avion.
* [ ] Améliorer le design avec un framework CSS comme Bootstrap ou Tailwind.

---

*Projet réalisé dans le cadre d'un auto-apprentissage sur le développement Web.*
