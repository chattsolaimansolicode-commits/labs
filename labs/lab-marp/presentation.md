---
marp: true
theme: default
size: 16:9
paginate: true
---

![Solicode](logo_solicode.png) ![OFPPT](ofppt_logo.png)

# Real Estate Portal

**Réalisé par :** Solaiman Chatt

**Encadré par :** [Nom de l'encadrant]

**Année :** 2026

<!--
Bonjour, aujourd'hui je vais vous présenter mon projet technique : Real Estate Portal.
-->

---

## Plan:

1. **Introduction**
2. **Problématique**
3. **Analyse**
4. **Conception**
5. **Réalisation**
6. **Conclusion**

<!--
Voici les différentes étapes de ma présentation.
-->

---

## Introduction:

Real Estate Portal est une application web destinée à la gestion et à l'affichage des propriétés immobilières.

Elle permet de centraliser les informations des propriétés et de faciliter leur organisation.

Le projet repose sur trois entités principales :

- Agent
- PropertyListing
- PropertyType

<!--
Je vais présenter le concept général de mon application et ses principales entités.
-->

---

## Problématique:

La gestion des informations immobilières peut devenir difficile lorsque les annonces et les données sont dispersées.

### Besoins identifiés:

- Organiser les informations des propriétés.
- Ajouter de nouvelles annonces immobilières.
- Associer les propriétés aux agents.
- Classer les propriétés par type.
- Faciliter la consultation des propriétés.

<!--
Je vais expliquer le problème identifié et les besoins auxquels mon projet cherche à répondre.
-->

---

## Analyse:

### Besoins des utilisateurs:

- Consulter les propriétés disponibles.
- Voir les détails d'une propriété.
- Accéder aux informations des annonces.

### Fonctionnalités prévues:

- Ajouter une propriété.
- Afficher les propriétés.
- Modifier les informations d'une propriété.
- Supprimer une propriété.
- Organiser les propriétés par type.
- Associer les propriétés aux agents.

<!--
Je vais présenter les besoins des utilisateurs et les fonctionnalités prévues dans l'application.
-->

---

## Conception:

### Diagramme de cas d'utilisation:

**Visiteur:**

- Consulter les propriétés.
- Voir les détails d'une propriété.

**Administrateur:**

- Ajouter une propriété.
- Afficher les propriétés.
- Modifier une propriété.
- Supprimer une propriété.
- Gérer les agents et les types de propriétés.

<!--
Je vais expliquer les acteurs du système et leurs différentes interactions avec l'application.
-->

---

## Modèle de données:

### Agent

```text
id, nom, email, téléphone
```

### PropertyListing

```text
id, titre, prix, localisation,
description, agent_id, type_id
```

### PropertyType

```text
id, nom
```

<!--
Voici les trois entités principales qui structurent les données de mon projet.
-->

---

## Réalisation:

### Stack technique:

**Frontend:**

- **HTML** - Structure des pages web.
- **Tailwind CSS** - Mise en forme de l'interface.
- **JavaScript** - Gestion des interactions.

**Backend:**

- **PHP** - Traitement des données.
- **MySQL** - Gestion de la base de données.

<!--
Je vais présenter les technologies utilisées et le rôle de chacune dans mon application.
-->

---

### Prototype:

**Fonctionnalité actuellement réalisée :**

- Ajouter une propriété (Create).

**État du projet :** En cours de développement.

Les autres opérations CRUD restent à développer :

- Read
- Update
- Delete

<!--
Je vais montrer l'état actuel du prototype et la fonctionnalité déjà développée.
-->

---

## Conclusion:

Ce projet me permet de mettre en pratique mes compétences en développement web.

Il constitue une première étape dans la réalisation d'une application de gestion immobilière.

Le développement des autres fonctionnalités permettra de compléter progressivement le projet.

<!--
Pour conclure, je vais résumer le travail réalisé et les prochaines étapes du développement. Merci pour votre attention.
-->