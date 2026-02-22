---
title: "Analyser l’état des données pour mieux les relier"
author: "Cristóbal Fabrizzio Barria Bignotti"
date: "2026"
lang: fr
---

# Résumé

Le développement de plateformes permettant la publication interconnectée de données issues de collections patrimoniales multiples soulève de nombreux défis techniques, politico-administratifs et liés à la gestion des données culturelles. Parmi ceux-ci, la nécessité de comprendre en profondeur l’état des données et les pratiques de curation mises en œuvre par les institutions d’origine apparaît comme un enjeu central. Ces institutions opèrent en effet selon des approches, des cultures organisationnelles et des modèles de gestion hétérogènes.

Si plusieurs instruments ont été développés afin d’accompagner les équipes des institutions GLAM (Galeries, Bibliothèques, Archives et Musées) dans la mise en ligne de leurs collections sous forme de données consultables, ceux-ci se concentrent généralement soit sur les défis internes à une seule institution, soit sur les problématiques propres à l’architecture sémantique et à la modélisation. À ce jour, il n’existe pas d’outil spécifiquement conçu pour collecter et analyser de manière systématique des informations relatives à la gestion et à la curation des données au sein de plusieurs institutions en vue de leur agrégation dans une plateforme fédérée.

Ce projet vise à combler cette lacune par la conception d’un instrument destiné à évaluer l’état, la structure et la gouvernance des données et des métadonnées au sein de différentes institutions GLAM. L’outil proposé prend la forme d’un questionnaire structuré offrant une vision détaillée du cycle de vie des données, de leurs conditions de production et des pratiques de gestion associées.

En prenant comme étude de cas le projet de plateforme fédérée des collections patrimoniales en cours de développement dans la ville de Genève, ce mémoire propose un outil flexible, évolutif et adaptable à différents types d’institutions, permettant à la fois l’analyse comparative de modèles curatoriaux et l’orientation des décisions de modélisation et de priorisation des données à publier.


---

# Table de matiéres

### 1 Introduction

Présentation du problème de recherche, des objectifs du mémoire et des résultats obtenus.
Justification générale du choix du sujet et présentation de la structure du travail.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

### 2 Cadre théorique

#### 2.1 Brève histoire de la publication ouverte des bases de données muséales.

Contextualisation historique du rôle des données dans les musées et de l’évolution des pratiques de publication des données patrimoniales.
Émergence des plateformes de données interopérables dans les institutions muséales. Transformations et défis liés à la gestion des données dans le secteur patrimonial.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: green; border-radius: 50%; margin-right: 5px;"></span>*Prêt, nécessite correction du français*</p>

#### 2.2 Interopérabilité des données muséales : web sémantique, ontologies patrimoniales et Linked Open Data.

Présentation synthétique des fondements techniques de l’interopérabilité des données patrimoniales : web sémantique, ontologies du domaine culturel, standards et principes du Linked Open Data.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: green; border-radius: 50%; margin-right: 5px;"></span>*Prêt, nécessite traduction*</p>

#### 2.3 Agrégation: un espace de négociation sémantique.

Analyse des enjeux conceptuels et techniques de l’agrégation de données provenant d’institutions hétérogènes. Étude de cas d’initiatives d’agrégation
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: orange; border-radius: 50%; margin-right: 5px;"></span>*Nécessite révision et traduction*</p>

#### 2.4 Curation des données patrimoniaux : principes et enjeux.

Brève introduction aux enjeux de la curation numérique face à l’agrégation de données patrimoniales dans des plateformes interconnectées. Analyse des vocabulaires, principes et standards.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: orange; border-radius: 50%; margin-right: 5px;"></span>*Partiellement rédigé*</p>

#### 2.5 Instruments existants

Analyse critique des checklists, maturity models, frameworks de data readiness et autres outils existants
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

#### 2.6 Présentation du projet de plateforme fédérée de la Ville de Genève

Brève introduction au projet de plateforme de la Ville de Genève. Contexte, objectifs et état de l’art.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

### 3 Objetifs

#### 3.1 Description du problème.

Dans le cadre d’une plateforme fédérée, une grande quantité d’informations circule entre les experts du domaine (conservateurs, documentalistes, responsables de collections) et les experts en modélisation et en architecture sémantique.
Cependant, il n’existe pas d’outil structuré permettant de collecter de manière systématique des informations sur l’état des bases de données de différentes institutions en vue de leur intégration dans une plateforme en Linked Open Data.
Ce manque complique l’évaluation de la viabilité des jeux de données, la planification du travail préparatoire et la prise de décisions en matière de modélisation.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: orange; border-radius: 50%; margin-right: 5px;"></span>*Partiellement rédigé*</p>

#### 3.2 Objectif principal.

Concevoir un outil facilitant la collecte, la structuration et l’analyse d’informations relatives aux bases de données muséales, afin :
– d’évaluer leur viabilité pour une plateforme interconnectée ;  
– d’identifier le travail préparatoire nécessaire ;  
– d’apporter des éléments structurés au processus de modélisation.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: orange; border-radius: 50%; margin-right: 5px;"></span>*Partiellement rédigé*</p>

#### 3.3 Objectifs secondaires.


– Offrir un instrument d’analyse comparative de l’état des données dans différentes institutions.
– Permettre l’analyse des politiques de curation et de gestion des données.
– Constituer une photographie de l’état des données à un moment donné, servant de base à une évaluation ultérieure de l’impact de la plateforme sur les pratiques de gestion.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

### 4. Méthodologie

#### 4.1 Méthodologie de conception du questionnaire.

Le questionnaire est élaboré à partir :
– d’une analyse de la littérature scientifique et professionnelle ;
– de l’étude d’instruments comparables ;
– d’un examen préliminaire de plusieurs bases de données d’institutions patrimoniales de la ville de Genève.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

#### 4.2 Phase de test.

Le questionnaire sera testé sur la base de données du Musée d’art et d’histoire de Genève, qui constitue le plus important jeu de données patrimonial de la ville.
Des experts en gestion de données issus des différentes institutions participantes seront consultés afin d’évaluer la pertinence, la clarté et l’utilité des questions.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

### 5 Présentation du questionnaire

#### 5.1 Conception méthodologique.
##### 5.1.1 Description des aspects analysés

L’outil analyse huit aspects de l’ensemble de données: l’identification des entités et des attributs ; le volume de doublons ; l’état de normalisation des expressions ; la gestion des incertitudes et des ambiguïtés ; le cycle de vie de l’information ; les droits associés ; ainsi que les recommandations de mise en ligne formulées par les spécialistes du domaine
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: orange; border-radius: 50%; margin-right: 5px;"></span>*Partiellement rédigé*</p>

##### 5.1.2 Format
Justification du choix d’un questionnaire structuré plutôt que d’autres formats (entretiens libres, audits techniques, etc.).
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: orange; border-radius: 50%; margin-right: 5px;"></span>*Partiellement rédigé*</p>

##### 5.1.3 Définition de l’unité d’analyse
L’unité d’analyse a été définie au niveau du dataset. Définition conceptuelle du dataset.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: orange; border-radius: 50%; margin-right: 5px;"></span>*Partiellement rédigé*</p>

##### 5.1.4 Critères de sélection des types de questions
Justification du recours à des questions ouvertes, fermées ou à choix multiples pour chaque section.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

##### 5.1.5 Méthodologie de remplissage
Description du processus de complétion du questionnaire.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: orange; border-radius: 50%; margin-right: 5px;"></span>*Partiellement rédigé*</p>

#### 5.2 Conception détaillée
##### 5.2.1 Présentation des questions

Présentation des questions par section thématique.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: green; border-radius: 50%; margin-right: 5px;"></span>*Une première version est prête*</p>

##### 5.2.2 Résultats attendus

Description des résultats attendus pour chaque section et de leur utilité.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: orange; border-radius: 50%; margin-right: 5px;"></span>*Partiellement rédigé*</p>

### 6 Présentation du questionnaire
#### 6.1 Application pilote
Analyse du cas test réalisé au Musée d’art et d’histoire de Genève.
Présentation des ajustements apportés à la suite de cette application.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

#### 6.2 Retour des experts
Analyse des commentaires recueillis auprès des spécialistes.
Modifications introduites dans l’outil à partir de ces retours.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

### 7 Conclusions
Évaluation de l’utilité du questionnaire. Limites de l’instrument. Conditions réelles de scalabilité. Perspectives d’application.
<p align="right"><span style="display: inline-block; width: 10px; height: 10px; background-color: red; border-radius: 50%; margin-right: 5px;"></span>*Non commencé*</p>

### 8 Bibliographie

### 9 Annexes
Versiones antérieurs du questionnaire