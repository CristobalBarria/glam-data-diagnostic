# Formulaire de diagnostic des pratiques de gestion et de curation des données patrimoniales


[Bienvenue](#bienvenue)

[Objectif](#objectif)

[Pourquoi ce formulaire](#pourquoi-ce-formulaire)

[Modalité de réponse recommandée](#modalité-de-réponse-recommandée)

[Durée](#durée)

[Confidentialité](#confidentialité)

[Contact](#contact)

[Glossaire](#glossaire)

[Définition de l’unité d’analyse de cette enquête](#définition-de-lunité-danalyse-de-cette-enquête)

  - [Jeu de données](#jeu-de-données)

  - [Relations entre entités](#relations-entre-entités)

  - [Modèle de métadonnées](#modèle-de-métadonnées)

  - [Couverture de la réponse](#couverture-de-la-réponse)

  - [En résumé](#en-résumé)

[1 Informations sur le répondant](#1-informations-sur-le-répondant)

  - [1.1 Nom de l'institution](#11-nom-de-linstitution)

  - [1.2 Personne de contact](#12-personne-de-contact)

  - [1.3 Adresse e-mail](#13-adresse-e-mail)

[2 Thématiques des collections](#2-thématiques-des-collections)

  - [2.1 Quel(s) est/sont le(s) domaine(s) thématique(s) principal(aux) de vos données ?](#21-quels-estsont-les-domaines-thématiques-principalaux-de-vos-données-)

  - [2.2 Souhaitez-vous décrire brièvement la nature ou la spécialisation de vos collections ?](#22-souhaitez-vous-décrire-brièvement-la-nature-ou-la-spécialisation-de-vos-collections-)

[3 Systèmes et modèles de gestion des données](#3-systèmes-et-modèles-de-gestion-des-données)

  - [3.1 Quel(s) système(s) de gestion utilisez-vous pour organiser les métadonnées de vos objets physiques ?](#31-quels-systèmes-de-gestion-utilisez-vous-pour-organiser-les-métadonnées-de-vos-objets-physiques-)

  - [3.2 Quels modèles, ontologies ou normes de description sont reconnus ou compatibles avec votre jeu de données ?](#32-quels-modèles-ontologies-ou-normes-de-description-sont-reconnus-ou-compatibles-avec-votre-jeu-de-données-)


[4 Recensement des entités](#4-recensement-des-entités)

  - [4.1.- Entités / Tables](#41-entités--tables)

[5 Recensement des attributs](#5-recensement-des-attributs)

  - [5.1 Attributs / Champs](#51-attributs--champs)

[6 Recensement des doublons](#6-recensement-des-doublons)

  - [6.1 Recensement des doublons dans les entités](#61-recensement-des-doublons-dans-les-entités)

[7 Gestion des incertitudes](#7-gestion-des-incertitudes)

  - [7.1 Expression des incertitudes dans les attributs](#71-expression-des-incertitudes-dans-les-attributs)

[8 Gestion des ambiguïtés](#8-gestion-des-ambiguïtés)

  - [8.1 Ambiguïtés dans les valeurs d’attributs à multiples entrées cardinalité multiple](#81-ambiguïtés-dans-les-valeurs-dattributs-à-multiples-entrées-cardinalité-multiple)

  - [8.2 Ambiguïtés entre enregistrements d’un même attribut](#82-ambiguïtés-entre-enregistrements-dun-même-attribut)

  - [8.3 Ambiguïtés entre attributs au sein d’un même groupe](#83-ambiguïtés-entre-attributs-au-sein-dun-même-groupe)

[9 État de normalisation des données](#9-état-de-normalisation-des-données)

  - [9.1 Attributs de type "Date"](#91-attributs-de-type--date-)

  - [9.2 Attributs de type "identifiant interne"](#92-attributs-de-type--identifiant-interne-)

  - [9.3 Attributs de type "Identifiant ou lien externe"](#93-attributs-de-type--identifiant-ou-lien-externe-)

  - [9.4 Attributs de type "Lien vers une ressource numérique (interne)"](#94-attributs-de-type--lien-vers-une-ressource-numérique-interne-)

  - [9.5 Attributs de type "Lien vers une ressource numérique (externe)"](#95-attributs-de-type--lien-vers-une-ressource-numérique-externe-)

  - [9.6 Attributs de type "Lien vers une autre entité/table"](#96-attributs-de-type--lien-vers-une-autre-entitétable-)

  - [9.7 Attributs de type "Texte Libre"](#97-attributs-de-type--texte-libre-)

  - [9.8 Attributs de type "Vocabulaire contrôlé"](#98-attributs-de-type--vocabulaire-contrôlé-)

[10 Cycle de vie](#10-cycle-de-vie)

  - [10.1 Périodicité de mise à jour des attributs](#101-périodicité-de-mise-à-jour-des-attributs)

  - [10.2 Durabilité et stabilité des identifiants et liens](#102-durabilité-et-stabilité-des-identifiants-et-liens)

[11 Droits et licences](#11-droits-et-licences)

  - [11.1 Droits ou licences associés à chaque attribut](#111-droits-ou-licences-associés-à-chaque-attribut)

[12 Évaluation de la publiabilité](#12-évaluation-de-la-publiabilité)

  - [12.1 Publiable et priorité de publication](#121-publiable-et-priorité-de-publication)

[Livraison des résultats de l’enquête](#livraison-des-résultats-de-lenquête)

  - [CSV informations générales](#csv-informations-générales)

  - [CSV Entités](#csv-entités)

  - [CSV Attributs](#csv-attributs)

  - [CSV Groupes d’attributs](#csv-groupes-dattributs)
 
---
### Pag. 1
---

# Bienvenue

Nous vous remercions de prendre le temps de participer à ce questionnaire.

# Objectif

Ce questionnaire vise à établir un diagnostic des pratiques de gestion et de curation des données patrimoniales au sein des institutions GLAM (Bibliothèques, Archives et Musées).

Plus précisément, il vise à recueillir des informations sur :

* Le système de gestion des données  
* Les modèles et la structure des données  
* Les vocabulaires et les thesauri employés  
* L’état de curation des données  
* Les politiques de gouvernance et procédures associées

# Pourquoi ce formulaire

Ce questionnaire a pour objectif de mieux comprendre l’état des données patrimoniales de votre institution. Vos réponses permettront de diagnostiquer et d’analyser ces données, afin de préparer leur intégration dans une plateforme sémantique de recherche interconnectée, qui facilitera le croisement et la mise en relation des informations entre les différentes collections.

Vos retours serviront également à adapter cet outil aux besoins spécifiques de chaque institution et à évaluer, de manière globale, quels jeux de données peuvent être incluses dans la plateforme.

# Modalité de réponse recommandée

Ce questionnaire doit être rempli avec l’assistance d’une personne de référence ou contact, chargée de guider les répondants dans la compréhension des concepts et la complétion des questions.

# Durée

Le temps nécessaire dépend de la complexité de vos données.

# Confidentialité

Toutes vos réponses seront traitées de façon strictement confidentielle.

# Contact

Pour toute question ou précision : [cristobal.barria@geneve.ch](mailto:cristobal.barria@geneve.ch)

---
### Pag. 2
---

# Glossaire

Les termes utilisés dans ce formulaire seront définis dans chaque question correspondante. Cependant, pour la lecture des instructions suivantes sur cette page, il est nécessaire de définir dès à présent certains termes essentiels.

## Entités

Une entité est une unité d’information distincte qui peut être identifiée de manière unique et décrite par des propriétés ou attributs. Une entité représente un objet, une personne, un événement ou un concept pertinent pour la documentation culturelle et patrimoniale.

  - ### Exemple :
    - **Objet** : tableau, manuscrit, amulette, photographie, document d’archives, livre, enregistrement audio, microfilm, etc.  
    - **Personne** : artiste, auteur, conservateur, chercheur, donateur, etc.  
    - **Événement** : exposition, découverte, restauration, acquisition, publication, etc.
    - **Lieu** : musée, site archéologique, réserve, salle de lecture, etc.  
    - **Concept** : technique artistique, style, mouvement artistique, genre littéraire, type documentaire, etc.

## Attributs

Un attribut correspond à une caractéristique ou propriété qui décrit ou qualifie une entité. Il peut s’agir d’une valeur littérale (texte, nombre, date, etc.) ou d’une relation vers une autre entité, permettant de détailler ses caractéristiques ou ses liens.

  - ### Exemple :
    - **Titre** : le nom ou le titre donné à l’objet.
    - **Date** : date de création, d’acquisition ou de réalisation.
    - **ISBN / Identifiant** : numéro unique d’identification.
    - **Auteur / Créateur** : personne ou groupe responsable de la création ou de la conception.
    - **Nombre de pages** : pour caractériser la longueur du livre >**Localisation / Provenance** : musée, site archéologique, réserve ou collection.  

Un attribut peut également faire partie d’un groupe d’attributs, qui réunit plusieurs caractéristiques liées.

  - ### Exemple :
    - Le groupe « autres noms » peut être composé des attributs Type, Nom et Remarque.
    - Les attributs De, À, Lieu, Remarques peuvent constituer le groupe d’attributs « Dates ». Dans ce questionnaire, nous nous référerons par « attribut » uniquement aux attributs simples. Les groupes d’attributs feront l’objet de questions spécifiques à des moments précis.

## Modèle de Métadonnées

Un modèle de métadonnées est un schéma conceptuel qui définit quelles informations sont enregistrées et comment celles-ci sont organisées (champs, relations entre entités, propriétés).

Le modèle peut correspondre à un standard externe reconnu ou à un modèle interne développé par l’institution.

  - ### Exemple :
    - Un standard externe reconnu: Dublin Core, CDWA ou LIDO.
    - Un modèle interne est un schéma utilisé pour cataloguer les items avec des champs et des règles spécifiques à une ou plusieurs institutions. Ce modèle peut être géré au moyen d’outils comme Musinfo, FileMaker ou des classeurs Excel. 
---
### Pag. 3
---
# Définition de l’unité d’analyse de cette enquête

Veuillez remplir ce questionnaire séparément pour chaque ensemble de données cohérent de votre institution —  autrement dit, pour chaque  jeu de données.

Cette approche permettra de distinguer des ensembles de données très différents et sans lien au sein d’une même institution, en tenant compte des spécificités propres à chaque jeu de données (modèle de données, vocabulaire, état de curation, type de ressource, structure de l’information, etc.) et de les analyser en fonction de ces caractéristiques propres.

## Jeu de données

Dans ce questionnaire, un jeu de données est défini comme un ensemble de données qui répond aux deux conditions suivantes :

  - Des attributs permettent de mettre en **relation les diverses entités**. 
  - Les données sont gérées selon un même **modèle de métadonnées (ou la même combinaison de modèles)**.

 À la suite, nous analyserons en détail ces deux conditions:

1. ### Relations entre entités

Dans ce questionnaire, un jeu de données est considéré comme tel lorsqu’il contient au moins un attribut reliant différentes entités, permettant de représenter leurs relations, interactions ou dépendances.

Exemples de relations entre entités à travers les attributs:

  - Un attribut “Auteur” de l’entité Œuvre relie l’œuvre à une entité Personne, représentant une relation “a été créé par”.  
  - Un attribut “Événement associé” de l’entité Document relie le document à une entité Événement, représentant une relation “a eu lieu lors de”.  
  - Un attribut “Domaine” de l’entité Œuvre relie plusieurs œuvres entre elles, représentant une relation “appartiennent au même domaine thématique ou conceptuel”.

Il n’est pas nécessaire que toutes les entités soient reliées directement entre elles ; certaines relations peuvent être établies indirectement via d’autres entités.

2. ### Modèle de métadonnées

Dans ce questionnaire, un jeu de données est également défini par le fait que ses informations sont gérées selon un même modèle de métadonnées (standard reconnu ou développé par l’institution).

Cependant, il est fréquent que les institutions GLAM combinent plusieurs modèles pour documenter un même jeu de données, ou qu’elles complètent un modèle préexistant standard par des règles et des champs spécifiques définis par l’institution.

Pour ce questionnaire, chaque ensemble de données qui combine des modèles sans chevauchement de champs doit être considéré comme faisant partie d’un unique jeu de données et doit être renseigné en conséquence.

Exemple de combinaison de modèles cohérente (jeu de données unique) :

Un musée documente sa collection de peintures en utilisant Dublin Core pour les métadonnées de base (titre, auteur, date) et un modèle interne pour les informations de conservation (emplacement, historique des restaurations). Comme les champs ne se chevauchent pas et se complètent, il s’agit d’un jeu de données unique.

Exemple de chevauchement de champs (jeux de données séparés) :

Une institution documente ses collections en utilisant EAD pour les documents administratifs, où le champ “Titre” correspond au titre officiel du document, et VRA Core pour les photographies, où le champ “Titre” correspond au nom donné à la photographie (souvent descriptif ou inventé). Même si les deux modèles utilisent le champ “Titre”, ils ne réfèrent pas à la même nature de l’information, et ces ensembles de données doivent donc être considérés comme distincts et enregistrés séparément.

Des détails supplémentaires sur le modèle et son application à des parties spécifiques du jeu de données pourront être précisés dans des questions spécifiques plus loin dans le questionnaire.

## Couverture de la réponse

Il est demandé de répondre pour toutes les entités et les attributs qui sont considérés comme publiables dans la plateforme de données interconnectées. En cas de doute, il est préférable de les inclure dans la réponse afin de pouvoir évaluer leur publiabilité de manière comparative, en tenant compte des résultats du questionnaire.

## En résumé

Ce questionnaire doit être rempli pour chaque ensemble d’informations interconnectées suivant les mêmes règles de structure, même si le degré de curatelle et de standardisation peut varier.

>Développement : 
Ce formulaire sera développé avec SurveyJS. Le choix de cet outil tient au fait qu’il permet de programmer chaque question de manière indépendante en JSON, ce qui facilite une structuration claire du questionnaire et la mise en place d’une logique conditionnelle dynamique, où les options de réponse dépendent des réponses précédentes. Par ailleurs, l’exportation directe des résultats en CSV simplifie l’analyse ultérieure des données.


---
### Pag. 4
---

# 1. Informations sur le répondant

## 1.1 Nom de l'institution

Question "type": "text"  
Réponse obligatoire

<input type="text" name="q1_1" id="q1_1" style="width:400px;"></label><br>

## 1.2 Personne de contact

Question "type": "text"  
Réponse obligatoire

<input type="text" name="q1_2" id="q1_2" style="width:400px;"></label><br>

## 1.3 Adresse e-mail

Question "type": "text"  
Réponse obligatoire

<input type="text" name="q1_3" id="q1_3" style="width:400px;"></label><br>


---
### Pag. 5
---

# 2. Thématiques des collections

## 2.1 Quel(s) est/sont le(s) domaine(s) thématique(s) principal(aux) de vos données ?

* Question "type": "checkbox"  
* Facultative

Cochez toutes les options pertinentes :

<form>

  <input type="checkbox" name="q2_1[]" value="Histoire de l'art" id="histoire">
  <label for="histoire">Histoire de l'art</label><br>

  <input type="checkbox" name="q2_1[]" value="Archéologie" id="archeologie">
  <label for="archeologie">Archéologie</label><br>

  <input type="checkbox" name="q2_1[]" value="Ethnographie / Anthropologie" id="ethnographie">
  <label for="ethnographie">Ethnographie / Anthropologie</label><br>

  <input type="checkbox" name="q2_1[]" value="Histoire sociale et politique" id="social">
  <label for="social">Histoire sociale et politique</label><br>

  <input type="checkbox" name="q2_1[]" value="Sciences naturelles" id="sciences_nat">
  <label for="sciences_nat">Sciences naturelles (botanique, zoologie, géologie, etc.)</label><br>

  <input type="checkbox" name="q2_1[]" value="Sciences exactes ou techniques" id="sciences_tech">
  <label for="sciences_tech">Sciences exactes ou techniques</label><br>

  <input type="checkbox" name="q2_1[]" value="Patrimoine industriel" id="patrimoine_ind">
  <label for="patrimoine_ind">Patrimoine industriel</label><br>

  <input type="checkbox" name="q2_1[]" value="Musique / Arts du spectacle" id="musique">
  <label for="musique">Musique / Arts du spectacle</label><br>

  <input type="checkbox" name="q2_1[]" value="Littérature" id="litterature">
  <label for="litterature">Littérature</label><br>

  <input type="checkbox" name="q2_1[]" value="Religion / Histoire ecclésiastique" id="religion">
  <label for="religion">Religion / Histoire ecclésiastique</label><br>

  <input type="checkbox" name="q2_1[]" value="Histoire locale / Patrimoine régional" id="histoire_locale">
  <label for="histoire_locale">Histoire locale / Patrimoine régional</label><br>

  <input type="checkbox" name="q2_1[]" value="Histoire des sciences et de la technologie" id="histoire_sciences">
  <label for="histoire_sciences">Histoire des sciences et de la technologie</label><br>

  <input type="checkbox" name="q2_1[]" value="Patrimoine immatériel" id="patrimoine_immat">
  <label for="patrimoine_immat">Patrimoine immatériel</label><br>

  <input type="checkbox" name="q2_1[]" value="Autre" id="autre">
  <label for="autre">
    Autre (précisez :
    <input type="text" name="q2_1_autre" style="width:200px;">
  </label><br>

</form>


## 2.2 Souhaitez-vous décrire brièvement la nature ou la spécialisation de vos collections ?

* Question "type": "comment"  
* Facultative

<textarea rows="6" cols="80" name="q2_2" style="width:100%; max-width:800px; padding:8px; font-size:1em;" placeholder="Votre texte ici..."></textarea>

---
### Pag.6
---

# 3. Systèmes et modèles de gestion des données

## 3.1 Quel(s) système(s) de gestion utilisez-vous pour organiser les métadonnées de vos objets physiques ?

* Question "type": "checkbox"  
* Facultative

**Instructions**

Cochez toutes les options pertinentes, par exemple si un même jeu de données est géré par plusieurs systèmes de gestion.

<form>

  <input type="checkbox" name="q3_1[]" value="Adlib / Axiell Collections" id="adlib">
  <label for="adlib">Adlib / Axiell Collections</label><br>

  <input type="checkbox" name="q3_1[]" value="Alma (Ex Libris)" id="alma">
  <label for="alma">Alma (Ex Libris)</label><br>

  <input type="checkbox" name="q3_1[]" value="ArchivesSpace" id="archivesspace">
  <label for="archivesspace">ArchivesSpace</label><br>

  <input type="checkbox" name="q3_1[]" value="Art Galleria" id="art_galleria">
  <label for="art_galleria">Art Galleria</label><br>

  <input type="checkbox" name="q3_1[]" value="Aucun actuellement" id="aucun">
  <label for="aucun">Aucun actuellement</label><br>

  <input type="checkbox" name="q3_1[]" value="BiblioMaker" id="bibliomaker">
  <label for="bibliomaker">BiblioMaker</label><br>

  <input type="checkbox" name="q3_1[]" value="Calm" id="calm">
  <label for="calm">Calm</label><br>

  <input type="checkbox" name="q3_1[]" value="CollectionsIndex+" id="collectionsindex">
  <label for="collectionsindex">CollectionsIndex+</label><br>

  <input type="checkbox" name="q3_1[]" value="CollectiveAccess" id="collectiveaccess">
  <label for="collectiveaccess">CollectiveAccess</label><br>

  <input type="checkbox" name="q3_1[]" value="EMu (Electronic Museum)" id="emu">
  <label for="emu">EMu (Electronic Museum)</label><br>

  <input type="checkbox" name="q3_1[]" value="Evergreen" id="evergreen">
  <label for="evergreen">Evergreen</label><br>

  <input type="checkbox" name="q3_1[]" value="Feuilles de calcul" id="feuilles_calcul">
  <label for="feuilles_calcul">Feuilles de calcul (par exemple Excel, Google Sheets)</label><br>

  <input type="checkbox" name="q3_1[]" value="FileMaker" id="filemaker">
  <label for="filemaker">FileMaker</label><br>

  <input type="checkbox" name="q3_1[]" value="Flora" id="flora">
  <label for="flora">Flora</label><br>

  <input type="checkbox" name="q3_1[]" value="Fotoware" id="fotoware">
  <label for="fotoware">Fotoware</label><br>

  <input type="checkbox" name="q3_1[]" value="Koha" id="koha">
  <label for="koha">Koha</label><br>

  <input type="checkbox" name="q3_1[]" value="Ligeo" id="ligeo">
  <label for="ligeo">Ligeo</label><br>

  <input type="checkbox" name="q3_1[]" value="Micromusée" id="micromusee">
  <label for="micromusee">Micromusée</label><br>

  <input type="checkbox" name="q3_1[]" value="MuseumPlus" id="museumplus">
  <label for="museumplus">MuseumPlus</label><br>

  <input type="checkbox" name="q3_1[]" value="Omeka / Omeka S" id="omeka">
  <label for="omeka">Omeka / Omeka S</label><br>

  <input type="checkbox" name="q3_1[]" value="PastPerfect" id="pastperfect">
  <label for="pastperfect">PastPerfect</label><br>

  <input type="checkbox" name="q3_1[]" value="Specify" id="specify">
  <label for="specify">Specify</label><br>

  <input type="checkbox" name="q3_1[]" value="Système interne / développé en interne" id="systeme_interne">
  <label for="systeme_interne">Système interne / développé en interne</label><br>

  <input type="checkbox" name="q3_1[]" value="Tellico" id="tellico">
  <label for="tellico">Tellico</label><br>

  <input type="checkbox" name="q3_1[]" value="TMS (The Museum System)" id="tms">
  <label for="tms">TMS (The Museum System)</label><br>

  <input type="checkbox" name="q3_1[]" value="Viridian" id="viridian">
  <label for="viridian">Viridian</label><br>

  <input type="checkbox" name="q3_1[]" value="Archivematica / AtoM (Access to Memory)" id="archivematica">
  <label for="archivematica">Archivematica / AtoM (Access to Memory)</label><br>

  <input type="checkbox" name="q3_1[]" value="Autre" id="autre_q3_1">
  <label for="autre_q3_1">
    Autre précisez :
    <input type="text" name="q3_1_autre" style="width:200px;">
  </label><br>

</form>

## 3.2 Quels modèles, ontologies ou normes de description sont reconnus ou compatibles avec votre jeu de données ?

* Question "type": "checkbox"  
* Facultative

**Instructions**

Cochez toutes les options que vous reconnaissez ou estimez compatibles avec votre jeu de données. Si différentes compatibilités s’appliquent à différentes entités, vous pourrez le préciser dans les questions suivantes.

<form>

  <input type="checkbox" name="q3_2[]" value="BIBFRAME – ontologie pour les bibliothèques, successeur de MARC" id="bibframe">
  <label for="bibframe">BIBFRAME – ontologie pour les bibliothèques, successeur de MARC</label><br>

  <input type="checkbox" name="q3_2[]" value="CCO – Cataloging Cultural Objects, guide pour décrire objets culturels" id="cco">
  <label for="cco">CCO – Cataloging Cultural Objects, guide pour décrire objets culturels</label><br>

  <input type="checkbox" name="q3_2[]" value="CDWA – œuvres d’art et collections" id="cdwa">
  <label for="cdwa">CDWA (Categories for the Description of Works of Art) – œuvres d’art et collections</label><br>

  <input type="checkbox" name="q3_2[]" value="CIDOC CRM – ontologie formelle..." id="cidoc_crm">
  <label for="cidoc_crm">CIDOC CRM – ontologie formelle définissant classes, relations et axiomes pour modéliser le patrimoine culturel ; sert de base conceptuelle pour créer des modèles de métadonnées implémentables. Extensions (CRMdig, CRMinf, CRMpe, etc.)</label><br>

  <input type="checkbox" name="q3_2[]" value="Dublin Core (DC)" id="dublin_core">
  <label for="dublin_core">Dublin Core (DC) – schéma général pour décrire des ressources numériques et physiques</label><br>

  <input type="checkbox" name="q3_2[]" value="Dublin Core Ontology (DCO)" id="dco">
  <label for="dco">Dublin Core Ontology (DCO) – formalisation en OWL de Dublin Core</label><br>

  <input type="checkbox" name="q3_2[]" value="EAC-CPF" id="eac_cpf">
  <label for="eac_cpf">EAC-CPF (Encoded Archival Context – Corporate Bodies, Persons, Families) – autorités et contextes archivistiques</label><br>

  <input type="checkbox" name="q3_2[]" value="EAD" id="ead">
  <label for="ead">EAD (Encoded Archival Description) – fonds et collections d’archives</label><br>

  <input type="checkbox" name="q3_2[]" value="EBUCore" id="ebucore">
  <label for="ebucore">EBUCore – métadonnées audiovisuelles européennes</label><br>

  <input type="checkbox" name="q3_2[]" value="EDM" id="edm">
  <label for="edm">EDM (Europeana Data Model) – modèle pour partager des données avec Europeana</label><br>

  <input type="checkbox" name="q3_2[]" value="FIAT/IFTA Cataloguing Rules" id="fiat_ifta">
  <label for="fiat_ifta">FIAT/IFTA Cataloguing Rules – règles pour cataloguer médias audiovisuels</label><br>

  <input type="checkbox" name="q3_2[]" value="FRBRoo" id="frbroo">
  <label for="frbroo">FRBRoo – ontologie dérivée de FRBR et du CIDOC CRM ; modèle conceptuel orienté objet pour la bibliographie et le patrimoine</label><br>

  <input type="checkbox" name="q3_2[]" value="ISBD" id="isbd">
  <label for="isbd">ISBD – International Standard Bibliographic Description</label><br>

  <input type="checkbox" name="q3_2[]" value="ISAD(G)" id="isadg">
  <label for="isadg">ISAD(G) – normes internationales pour l’archivage et description des fonds</label><br>

  <input type="checkbox" name="q3_2[]" value="ISAAR(CPF)" id="isaarcpf">
  <label for="isaarcpf">ISAAR(CPF) – norme internationale pour l’archivage des autorités (personnes, familles, organismes)</label><br>

  <input type="checkbox" name="q3_2[]" value="ISDF" id="isdf">
  <label for="isdf">ISDF – norme pour les fonds documentaires et fichiers institutionnels</label><br>

  <input type="checkbox" name="q3_2[]" value="ISDIAH" id="isdiah">
  <label for="isdiah">ISDIAH – norme pour description d’institutions d’archives et de patrimoine</label><br>

  <input type="checkbox" name="q3_2[]" value="LIDO" id="lido">
  <label for="lido">LIDO (Lightweight Information Describing Objects) – pour objets de musée</label><br>

  <input type="checkbox" name="q3_2[]" value="LRMoo" id="lrmoo">
  <label for="lrmoo">LRMoo – ontologie dérivée de LRM et du CIDOC CRM ; modèle conceptuel orienté objet pour les ressources bibliographiques</label><br>

  <input type="checkbox" name="q3_2[]" value="MODS" id="mods">
  <label for="mods">MODS (Metadata Object Description Schema) – bibliographie et objets culturels</label><br>

  <input type="checkbox" name="q3_2[]" value="Object ID" id="object_id">
  <label for="object_id">Object ID – norme pour identifier et documenter objets patrimoniaux</label><br>

  <input type="checkbox" name="q3_2[]" value="PBCore" id="pbcore">
  <label for="pbcore">PBCore – médias audiovisuels</label><br>

  <input type="checkbox" name="q3_2[]" value="PREMIS" id="premis">
  <label for="premis">PREMIS – préservation numérique</label><br>

  <input type="checkbox" name="q3_2[]" value="PROV-O" id="prov_o">
  <label for="prov_o">PROV-O (W3C Provenance Ontology)</label><br>

  <input type="checkbox" name="q3_2[]" value="RADFG" id="radfg">
  <label for="radfg">RADFG – règles pour documents graphiques ou fonds spécifiques</label><br>

  <input type="checkbox" name="q3_2[]" value="RDA" id="rda">
  <label for="rda">RDA – normes pour décrire les ressources bibliographiques (Resource Description and Access)</label><br>

  <input type="checkbox" name="q3_2[]" value="RiC-CM / RiC-O" id="ric">
  <label for="ric">RiC-CM / RiC-O – modèle conceptuel des archives et des contextes archivistiques, complexe et orienté Linked Open Data</label><br>

  <input type="checkbox" name="q3_2[]" value="Schema.org" id="schema_org">
  <label for="schema_org">Schema.org – vocabulaire général pour structurer des données web</label><br>

  <input type="checkbox" name="q3_2[]" value="VRA Core" id="vra_core">
  <label for="vra_core">VRA Core – objets visuels et artistiques</label><br>

  <input type="checkbox" name="q3_2[]" value="Modèle interne non standardisé" id="modele_interne">
  <label for="modele_interne">Modèle interne non standardisé</label><br>

  <input type="checkbox" name="q3_2[]" value="Je ne sais pas / N’existe pas" id="ne_sais_pas">
  <label for="ne_sais_pas">Je ne sais pas / N’existe pas</label><br>

  <input type="checkbox" name="q3_2[]" value="Autre" id="autre_q3_2">
  <label for="autre_q3_2">
    Autre précisez :
    <input type="text" name="q3_2_autre" style="width:200px;">
  </label><br>

</form>

---
### Pag.7
---

# 4. Recensement des entités

## 4.1 Entités / Tables

* Question "type": "matrixdynamic"  
* Obligatoire

Cette question vise à recenser les entités présentes dans votre jeu de données

Par « entité », nous entendons tout concept, objet, événement ou élément individuel pour lequel des propriétés ou attributs sont stockés. Pensez aux principales catégories qui composent votre jeu de données.

  - Exemples d'entités courantes dans les institutions GLAM : Œuvres, Auteurs, Expositions, Collections, Documents, Volumes, Thèmes, Événements historiques, etc.

Dans le cas d’une base de données relationnelle, nous faisons référence aux tables qui composent la base de données, telles que *Œuvres*, *Auteurs*, *Expositions*, *Documents*, etc.

Veuillez répondre à cette question en vous concentrant sur les entités de votre jeu de données, et non sur les attributs qui les décrivent.

**Instructions**

  - **Entité** : indiquez le nom de l’entité ou le titre de la table qui compose le jeu de données.  
  - **Volume** : indiquez le nombre d’enregistrements (ou d'entrées) que contient cette entité. En cas de doublons, indiquez ici le nombre total d’enregistrements actuels ; une question ultérieure précisera les détails concernant les doublons.  
  - **Modèle** : si vous avez indiqué dans la page précédente l’utilisation de plusieurs modèles/ontologies/normes compatibles, identifiez ici ceux que vous considérez compatible avec cette entité.  
  - **Système(s) de gestion** : si vous avez indiqué dans la page précédente l’utilisation de plusieurs systèmes de gestion, identifiez ici le système utilisé pour cette entité.

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Entité</th>
    <th style="border:1px solid #999; padding:8px; width:120px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">Modèle</th>
    <th style="border:1px solid #999; padding:8px;">Système(s) de gestion</th>
  </tr>

  <!-- Ligne exemple pré-remplie -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q4_1[0][entite]" value="Auteurs" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q4_1[0][volume]" value="17500" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q4_1[0][modele]" value="Dublin Core" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q4_1[0][systeme]" value="MuseumPlus" style="width:100%; font-style: italic;">
    </td>
  </tr>

  <!-- Ligne à compléter 1 -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q4_1[1][entite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q4_1[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q4_1[1][modele]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q4_1[1][systeme]" style="width:100%;">
    </td>
  </tr>

  <!-- Ligne à compléter 2 -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q4_1[2][entite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q4_1[2][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q4_1[2][modele]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q4_1[2][systeme]" style="width:100%;">
    </td>
  </tr>

</table>

</form>


  - Les options de la colonne “modèle” dépendent des choix sélectionnés à la question 3.2.  
  - Les options de la colonne “Système(s) de gestion” dépendent des choix sélectionnés à la question 3.1.

---
### Pag.8
---
# 5 Recensement des attributs

## 5.1 Attributs / Champs

* Question "type": "matrixdynamic"  
* Obligatoire

Cette question a pour objectif de dresser un panorama des attributs enregistrés dans votre jeu de données.

Pour chaque entité que vous avez indiquée dans la question précédente, détaillez tous les attributs (champs) enregistrés.

Par « attribut », nous entendons toute information ou propriété qui décrit une entité dans le jeu de données. Par exemple : dans l’entité « Œuvres », les attributs peuvent être “dénomination,”« titre », « auteur », « date de création », « matériau », etc.

**Instructions**

* **Entité** : indiquez à quelle Entité/Table appartient l’attribut (ex. Œuvres, Auteurs, Documents).  
* **Nom de l’attribut/champ** : écrivez le nom utilisé pour identifier l’attribut. Si votre attribut a un nom d’affichage (étiquette / label) et un nom technique (nom interne), indiquez ici le nom d’affichage et précisez le nom technique dans la colonne correspondante.  
* **Nom technique** : Écrivez ici le nom interne du groupe  
* **Obligatoire / optionnel** : indique si l’attribut est requis obligatoirement ou non pour créer l’enregistrement.  
* **Type de données** : classez l’attribut selon le type de données qu’il enregistre.  
  Si un même attribut contient des valeurs de types différents (par exemple, une partie des données est normalisée selon un vocabulaire contrôlé et une autre en texte libre), indiquez toujours le type correspondant à la valeur qui suit la règle curatoriale de votre institution ou, en l’absence d’une telle règle, le type idéal selon vos besoins. Le volume des données correctement normalisées sera demandé ultérieurement.  
  Les possibilités sont :  
    - **Booléen** : valeur de type vrai/faux (oui/non, présent/absent, En ligne/Hors ligne).  
    - **Date** : choisissez cette option uniquement pour les attributs qui expriment une information temporelle sous une forme fixe ou formule. Attention : une date peut également être exprimée comme texte libre, vocabulaire contrôlé, identifiant, etc. Dans ces cas, indiquez le type correspondant.  
    - **Identifiant interne** : code unique ou référence stable, utilisé pour identifier une ressource ou une entité à l’intérieur d' un jeu de données. Les caractéristiques de l’identifiant, comme sa composition ou son unicité, seront examinées dans des questions ultérieures.  
    - **Identifiant ou lien externe** : identifiant ou lien pointant vers des entités ou des attributs situés dans une autre base de données ou un autre jeu de données, généralement gérés par une institution tierce. Contrairement aux liens vers des ressources numériques (images, documents, vidéos), ces liens établissent une relation avec des éléments structurés d’une autre base de données, et non avec des fichiers ou supports multimédias.  
    - **Lien vers une ressource numérique (interne)**: lien pointant vers une ressource en ligne (image, document, vidéo, audio, fiche descriptive, etc.) publiée ou gérée directement par l’institution. Il s’agit d’un lien vers un support numérique associé et non d’un lien vers une entité ou un attribut du jeu de données. La ressource peut être rendue publique ou rester accessible uniquement en interne.  
    - **Lien vers une ressource numérique (externe)** : lien pointant vers une ressource en ligne (image, document, vidéo, audio, fiche descriptive, etc.) publiée ou gérée par une autre institution ou organisation. Là encore, il s’agit d’un lien vers une ressource numérique associée, à distinguer des liens qui connectent une entité à d’autres entités ou attributs dans une base de données.  
    - **Lien vers une autre entité/table** : cet attribut indique une relation directe entre des entités du même jeu de données. La valeur de cet attribut est soit un identifiant unique, soit un lien vers une autre entité du même jeu de données. Exemple : “ID de l’auteur” dans la table Œuvres, qui renvoie à la table Auteurs.   
    - **Texte libre** : champ ouvert dans lequel on peut écrire n’importe quelle valeur, sans restriction ni validation par rapport à une liste.  
    - **Vocabulaire contrôlé** : la valeur de l’attribut est sélectionnée à partir d’une liste prédéfinie. Il peut s’agir d’un vocabulaire interne à l’institution, publié par une autre institution, ou d’un thésaurus/autorité publié et disponible en Linked Open Data. Cette catégorie est différente de « Identifiant externe », qui relie la valeur de l’attribut à une entité spécifique dans une autre base de données ou projet.  
* **Groupe** : un attribut peut appartenir à un groupe d’attributs, c’est-à-dire à un ensemble logique qui réunit plusieurs informations relatives à des entités liées entre elles. Par exemple, le groupe « Autres noms » peut regrouper les attributs *Type*, *Nom* et *Remarque*. Si l’attribut que vous analysez fait partie d’un tel groupe, indiquez-le ici.  
  Privilégiez le nom officiel du groupe ; en l’absence d’un nom officiel, proposez une dénomination descriptive et unique, ou attribuez-lui un numéro.  
* **Langues** : indiquez la ou les langues dans lesquelles ces expressions se trouvent.  
* **Volume** : Indiquez ici le nombre total d’enregistrements. En cas de doublons, des précisions sur ceux-ci seront demandées ultérieurement.  
* **Description** : expliquez brièvement ce que contient l’attribut et comment il est utilisé. Exemple : « Titre » → titre assigné par le créateur de l’œuvre.  
  Il s’agit ici de décrire les valeurs correctement enregistrées, conformes aux règles et au type de valeur attendu pour ce champ. Le cas échéant, les détails sur les valeurs non normalisées ou présentant des ambiguïtés sémantiques par rapport au champ seront précisés ultérieurement. 


<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Entités / Tables</th>
    <th style="border:1px solid #999; padding:8px;">Nom de l’attribut / Champ</th>
    <th style="border:1px solid #999; padding:8px;">Nom interne</th>
    <th style="border:1px solid #999; padding:8px;">Obligatoire / Optionnel</th>
    <th style="border:1px solid #999; padding:8px;">Type de donnée</th>
    <th style="border:1px solid #999; padding:8px;">Groupe</th>
    <th style="border:1px solid #999; padding:8px;">Langue</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">Description</th>
  </tr>

  <!-- Ligne exemple -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q5_1[0][entite]" value="Œuvre" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q5_1[0][attribut]" value="Titre" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q5_1[0][nom_interne]" value="OBJ_TITLE" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q5_1[0][obligation]" value="Obligatoire" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q5_1[0][type_donnee]" value="Texte libre" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q5_1[0][groupe]" value="Nomination" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q5_1[0][langue]" value="Français" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q5_1[0][volume]" value="15222" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q5_1[0][description]" value="Titre attribué à l’œuvre ou transcription du titre original" style="width:100%; font-style: italic;">
    </td>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;"><input type="text" name="q5_1[1][entite]" style="width:100%;"></td>
    <td style="border:1px solid #999; padding:6px;"><input type="text" name="q5_1[1][attribut]" style="width:100%;"></td>
    <td style="border:1px solid #999; padding:6px;"><input type="text" name="q5_1[1][nom_interne]" style="width:100%;"></td>
    <td style="border:1px solid #999; padding:6px;"><input type="text" name="q5_1[1][obligation]" style="width:100%;"></td>
    <td style="border:1px solid #999; padding:6px;"><input type="text" name="q5_1[1][type_donnee]" style="width:100%;"></td>
    <td style="border:1px solid #999; padding:6px;"><input type="text" name="q5_1[1][groupe]" style="width:100%;"></td>
    <td style="border:1px solid #999; padding:6px;"><input type="text" name="q5_1[1][langue]" style="width:100%;"></td>
    <td style="border:1px solid #999; padding:6px;"><input type="number" name="q5_1[1][volume]" style="width:100%;"></td>
    <td style="border:1px solid #999; padding:6px;"><input type="text" name="q5_1[1][description]" style="width:100%;"></td>
  </tr>

</table>

</form>

* Les options de la colonne “Entités/Tables” dépendent des choix sélectionnés dans la colonne « Entité / Table » de la question 4.1.  
* Les options de la colonne « Obligatoire » sont :  
  \[  
  "Oui",  
  "Non"

\]

* Les options de la colonne “Type de donnée ” sont :  
  \[

  "Booléen",  
  "Date",  
  "Identifiant interne",  
  "Identifiant ou lien externe",  
  "Lien interne vers une ressource numérique (interne)",  
  "Lien interne vers une ressource numérique (externe)",  
  "Lien vers une autre entité/table",

  "Texte libre",

  "Vocabulaire contrôlé"

\]
---
### Pag.9
---
# 6 Recensement des doublons

## 6.1 Recensement des doublons dans les entités

* Question "type": "matrixdynamic"  
* Facultative

Cette question vise à identifier la présence de doublons au niveau des entités décrites dans la question 4.1.

Sont considérés comme doublons tous les enregistrements représentant la même entité telle que définie dans la question 4.1, c’est-à-dire des enregistrements correspondant à la même unité conceptuelle ou individuelle dans votre jeu de données. Ces doublons peuvent entraîner des répétitions significatives et affecter la fiabilité et l’exactitude des données.

**Introduction**

* **Entités** : Parmi les entités indiquées dans la question 4.1, sélectionnez uniquement celles qui peuvent contenir des doublons.  
* **Volume :** Indiquez le nombre d’enregistrements dupliqués pour cette entité. Si vous ne connaissez pas le nombre exact, vous pouvez fournir une estimation approximative. Veuillez compter le nombre total d’enregistrements affectés, et non pas le nombre de paires, triplés ou autres regroupements.  
* **Commentaires / détails :** Fournissez toute information supplémentaire utile concernant les doublons identifiés pour cette entité, en particulier si cela permet d’expliquer des motifs ou des tendances de duplication.

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Entités</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">Commentaires / détails</th>
  </tr>

  <!-- Ligne exemple pré-remplie -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q6_1[0][entite]" value="Auteurs" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q6_1[0][volume]" value="200" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q6_1[0][commentaires]" value="Principalement les auteurs du domaine de la numismatique" style="width:100%; font-style: italic;">
    </td>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q6_1[1][entite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q6_1[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q6_1[1][commentaires]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne “Entités/Tables” dépendent des choix sélectionnés dans la colonne « Entité / Table » de la question 4.1.
---
### Pag.10
---
# 7 Gestion des incertitudes

## 7.1 Expression des incertitudes dans les attributs

* Question "type": "matrixdynamic"  
* Facultative

Cette question vise à clarifier les différents modes d’expression des incertitudes dans les attributs décrits dans la question 5.1.

Sont considérées comme exprimant une incertitude toutes les expressions indiquant que la valeur est douteuse, inconnue, incertaine, approximative, alternative ou non définie.

**Introduction**

* **Attributs** : Parmi les attributs indiqués dans la question 5.1, sélectionnez uniquement ceux qui peuvent contenir des valeurs incertaines.  
* **Expression de l’incertitude dans la structure des données**: Identifiez la manière dont l’incertitude doit être exprimée dans la structure des données.  
  Sélectionnez une seule option.  
  Si le ou les modes d’expression de l’incertitude ne sont pas listés, ou si plusieurs modes s’appliquent, ajoutez une brève explication dans la section “Autre”.   
  Les possibilités sont:  
   - **Intégrée**: l’incertitude est exprimée directement avec la valeur à laquelle elle se réfère dans l’enregistrement.  
    Exemples d’expressions : “*Courbet ?*”, “*ca. 1780*”, “*incertain*”, “*Naples ou Rome*”  
  - **Vocabulaire contrôlé** : l’incertitude est représentée par des alternatives prévues dans un vocabulaire contrôlé.  
  - **Attribut d’incertitude** : Cet attribut ne communique que l’incertitude concernant les valeurs d’un autre attribut. Les relations entre attributs seront traitées plus en détail dans des questions ultérieures.  
  - **Autre** : \_\_\_\_\_\_\_\_\_\_\_\_  
* **Expression des incertitudes**: Pour tous les attributs que vous avez sélectionnés comme ayant l’incertitude intégrée, indiquez les modes par lesquels elle peut être exprimée.  
  Sélectionnez toutes les alternatives qui correspondent. Si un mode d’expression n’est pas listé, ajoutez-le dans la section *Autre.*  
  Si une partie expressions des incertitudes intégrées n’est pas normalisée, ajoutez, sélectionnez « Autre » et décrivez la situation.  
* **Volume** : indiquez le nombre d’enregistrements qui comportent des valeurs incertaines.  
* **Exemple** : illustre les expressions des valeurs incertaines.


<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Expression de l’incertitude dans la structure des données</th>
    <th style="border:1px solid #999; padding:8px;">Expression des incertitudes</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">Exemple</th>
  </tr>

  <!-- Ligne exemple pré-remplie -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q7_1[0][attribut]" value="Pays" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q7_1[0][incertitude_structure]" value="Intégrée" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q7_1[0][incertitude_expression]" value="(?)" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q7_1[0][volume]" value="950" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q7_1[0][exemple]" value="Grand-Lancy (?)" style="width:100%; font-style: italic;">
    </td>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q7_1[1][attribut]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q7_1[1][incertitude_structure]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q7_1[1][incertitude_expression]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q7_1[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q7_1[1][exemple]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des valeurs de la colonne « Nom de l’attribut/champ » de la question 5.1. Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Expression de l’incertitude dans la structure des données » sont :  
  \[  
  "Intégrée",  
  "Vocabulaire contrôlé",  
  "Attribut d’incertitude",  
  "Autre : \_\_\_\_\_\_"  
  \]  
* Les options de la colonne « Expression des incertitudes » sont :  
  \[  
  "?",  
  "(?)",  
  "incertain / incertaine",  
  "douteux / douteuse",  
  "inconnu / inconnue",  
  “incertain”,  
  “indéterminé”,  
  "approximatif / approximative",  
  "…",  
  “- (Entre deux valeurs)”,  
  "\~ (Entre deux valeurs)",  
  "ou (Entre deux valeurs)",  
  "probable",  
  "estimé(e)",  
  “ca. (circa)”,  
  “avant”,  
  “après”,  
  “début du”,  
  “fin du”  
  “entre … et …”  
  "présumé(e)",  
  "env. (environ)",  
  "à confirmer",  
  "| (Entre deux valeurs)",  
  "/ (Entre deux valeurs)",  
  "; (Entre deux valeurs)",  
  "Autre : \_\_\_\_\_\_\_\_\_\_\_"  
  \]

---
### Pag.11
---
# 8. Gestion des ambiguïtés

## 8.1 Ambiguïtés dans les valeurs d’attributs à multiples entrées (cardinalité multiple)

* Question "type": "matrixdynamic"  
* Facultative

Cette question vise à identifier et caractériser les ambiguïtés présentes dans le contenu des cellules des attributs à valeurs multiples.

Par « ambiguïté » dans cette question, on entend toute situation où le contenu d’une cellule individuelle peut être interprété de plusieurs manières ou présenter un sens différent.

Cette question concerne donc uniquement les attributs autorisant plusieurs réponses dans un même enregistrement/cellule (Cardinalité supérieure à 1).

En tenant compte des informations déjà fournies à la question 6.1, ne considérez pas comme plusieurs valeurs, au sein d’un même enregistrement ou d’une même cellule, les indications d’incertitude. Par exemple, dans « Genève ? », le symbole « ? » ne doit pas être considéré comme une valeur distincte de « Genève ». En revanche, prenez en compte l’incertitude lorsqu’il existe plusieurs valeurs possibles, contradictoires ou alternatives, par exemple : « Naples ou Rome ».

Dans cette question, nous nous intéressons aux différences de signification ou de relation entre les valeurs permises, et non aux différences liées à la normalisation ou à la manière dont les données ont été exprimées, lesquelles seront abordées plus en détail dans les questions 9\.

**Instructions**

* **Attributs** : Parmi les attributs indiqués dans la question 5.1, sélectionnez uniquement ceux qui peuvent contenir plus d’une valeur dans un même enregistrement/cellule (Cardinalité supérieure à 1).  
  Exemple :  
  - **“Mots-clés”** → plusieurs mots-clés par enregistrement, séparés par des virgules ou un autre séparateur.  
  - **Techniques utilisées** : « *gravure; aquarelle; pastel* »  
  - **Dimensions** : « *hauteur : 50 cm, largeur : 30 cm, profondeur : 20 cm* »  
* **Exemple :** Indiquez un exemple illustrant la relation entre différentes valeurs au sein d’un même attribut.  
  Si, dans un même attribut, les valeurs multiples entretiennent plusieurs types de relations distinctes entre elles, remplissez une nouvelle ligne du tableau pour chaque type de relation observé, en sélectionnant à chaque fois le même attribut dans la colonne “Attribut” et en indiquant un exemple différent. Si les cas sont très nombreux, limitez-vous aux trois types de relation les plus courants.  
* **Relation Logique** : Pour chaque attribut indique ayant plusieurs valeurs, précisez le type de relation logique entre ces valeurs.  
  Sélectionnez une seule option.  
  Les possibilités sont :  
  - **Valides simultanément** : les valeurs peuvent coexister dans le même champ. Exemple : le champ “Mots-clés” \= “peinture, huile, 19ème siècle”.  
  - **Exclusives (une ou l’autre)** : seulement une des alternatives peut être considérée correcte. Exemple : “date de naissance” \= “1984, 1985”.  
  - **Incohérent** : les valeurs n’ont aucune relation logique. Exemple : “Genre” \= “Masculin, rouge”.  
  - **Autre** : toute autre situation non couverte par les options ci-dessus.  
* **Relation sémantique** : Pour chaque attribut indique ayant plusieurs valeurs, précisez le type de relation sémantique entre ces valeurs.  
  Sélectionnez une seule option.  
  Les possibilités sont :  
  - **Équivalentes** : Deux valeurs expriment exactement le même sens et pourraient être considérées interchangeables. Exemple : “huile sur toile” et “peinture à l’huile sur toile”  
  - **Variante ou reformulation** : Une valeur est une forme différente, une reformulation ou une orthographe alternative d’une autre, mais conserve globalement le même sens. Exemple : “Guerre de Sécession” et “Guerre civile américaine”  
  - **Complémentaires** : Les valeurs apportent des informations différentes mais qui se complètent pour comprendre pleinement l’attribut. Exemple : Dans un champ “Dimensions”, “hauteur : 50 cm” et “largeur : 30 cm” sont complémentaires.  
  - **Quantification**: Un valor precisa la cantidad de ocurrencias del otro. Exemple : “Fragments, 3”  
  - **Sans lien sémantique** : les deux attributs sont sans lien. Exemple : “1984” et “Bois”  
  - **Autre** : toute autre situation non couverte par les options ci-dessus.  
* **Relation hiérarchique / structurelle :** Pour chaque attribut indique ayant plusieurs valeurs, précisez le type de relation hiérarchique / structurelle entre ces valeurs.  
  Sélectionnez une seule option.  
  Les possibilités sont :  
  - **Partie-tout** : Une valeur représente une partie du contenu ou du concept de l’autre valeur, ou inversement. Exemple : “sous-collection de sculptures” et “collection de sculptures” : la première est une partie de la seconde.  
  - **Niveau hiérarchique** : un attribut est imbriqué dans un autre à un niveau différent. Exemple: “Sous-collection” est imbriqué dans “Collection”.
  - **Séquentielle** : attributs décrivent des étapes successives d’un processus. Exemple: “Étape de traitement documentaire” : catalogage → indexation → validation.  
  - **Sans lien hiérarchique ou structurelle** : les deux attributs sont sans lien. Exemple : “1984” et “Bois”.
  - **Autre** : toute autre situation non couverte par les options ci-dessus.  
* **Relation de qualification :** Pour chaque attribut indique ayant plusieurs valeurs, précisez le type de relation de qualification entre ces valeurs.  
  Sélectionnez une seule option.  
  Les possibilités sont :  
  - **Certitude / incertitude** : un attribut indique si la valeur de l’autre est certaine, incertaine ou hypothétique. Exemple : “1986 ou 1987”.  
  - **Source / provenance** : un attribut documente l’origine de l’information contenue dans un autre. “Année” \= “1765, selon Berthet”.  
  - **Sans lien de qualification** : les deux attributs sont sans lien. Exemple : “1984” et “Bois”  
  - **Autre** : toute autre situation non couverte par les options ci-dessus.  
* **Volume :** indiquez le nombre d’enregistrements comportant plusieurs valeurs dans ce champ et présentant le même type de relation.

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Exemple</th>
    <th style="border:1px solid #999; padding:8px;">Relation Logique</th>
    <th style="border:1px solid #999; padding:8px;">Relation Sémantique</th>
    <th style="border:1px solid #999; padding:8px;">Relation hiérarchique / structurelle</th>
    <th style="border:1px solid #999; padding:8px;">Relation de qualification</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
  </tr>

  <!-- Ligne exemple pré-remplie -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[0][attribut]" value="Dénomination" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[0][exemple]" value="Amphore, fragments" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[0][relation_logique]" value="Valides simultanément" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[0][relation_semantique]" value="Complémentaires" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[0][relation_hierarchique]" value="Partie-tout" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[0][relation_qualification]" value="Sans lien de qualification" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q8_1[0][volume]" value="12" style="width:100%; font-style: italic;">
    </td>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[1][attribut]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[1][exemple]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[1][relation_logique]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[1][relation_semantique]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[1][relation_hierarchique]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_1[1][relation_qualification]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q8_1[1][volume]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des valeurs de la colonne « Nom de l’attribut/champ » de la question 5.1. Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Relation Logique» sont :  
  \[  
  "Valides simultanément",  
  "Exclusives (une ou l’autre)",  
  "Incohérent",  
  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"  
  \]  
* Les options de la colonne « Relation Sémantique» sont :  
  \[  
  "Équivalentes",  
  "Variante ou reformulation",  
  "Complémentaires",

  “Quantification”,  
  “Sans lien sémantique”,  
  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

  \]  
* Les options de la colonne « Relation hiérarchique / structurelle» sont :  
  \[  
  "Partie-tout",  
  "Niveau hiérarchique",  
  "Séquentielle",

  “Sans lien hiérarchique ou structurelle”,  
  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

  \]  
* Les options de la colonne « Relation de qualification» sont :  
  "Certitude / incertitude",  
  "Source / provenance",  
  “Sans lien de qualification”,

  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

  \]

## 8.2 Ambiguïtés entre enregistrements d’un même attribut

* Question "type": "matrixdynamic"  
* Facultative

Cette question vise à identifier et caractériser les ambiguïtés sémantiques qui peuvent exister entre les valeurs des attributs décrits dans la question 5.1.

Par « ambiguïté » dans cette question, on entend toute situation où les valeurs d’un même attribut peuvent être incohérentes, contradictoires ou ambiguës par rapport au contenu de l’attribut, ou entre elles.

Cette question porte sur la cohérence du contenu entre différents enregistrements pour un même attribut, et non sur les incohérences entre valeurs à l’intérieur d’un même enregistrement, comme cela est traité dans les questions 8.1.

Dans cette question, nous nous intéressons aux différences de signification ou de relation entre les valeurs, et non aux différences liées à la normalisation ou à la manière dont les données ont été exprimées, qui seront abordées plus en détail dans les questions 9\. Par conséquent, ne sélectionnez pas ici des valeurs dont la relation avec l’attribut se limite à être une variante de l’expression du terme attendu, ni celles qui résultent d’erreurs de saisie.

**Instructions**

* **Attributs** : Parmi les attributs indiqués dans la question 5.1, sélectionnez uniquement ceux pour lesquels les valeurs renseignées dans un même attribut désignent des aspects différents ou incohérents.  
  Exemple :  
  - **Date de création** \= “*1850*” dans un enregistrement et Date de création \= “*Genève*” dans un autre (mélange entre donnée chronologique et Lieu pour le même attribut).  
* **Exemple** : Indiquez une valeur illustrant un type de relation incohérente par rapport au contenu de l’attribut.  
  Si, pour un même attribut, plusieurs types de relations incohérentes ou ambiguës apparaissent entre les valeurs, remplissez une nouvelle ligne du tableau pour chaque type de relation observé, en sélectionnant à chaque fois le même attribut dans la colonne “Attribut”. Indiquez le type de relation correspondant dans la colonne “Relation”. Si les cas sont très nombreux, limitez-vous aux trois types de relation les plus courants.   
* **Relation** : sélectionnez l’un des types de relation suivants entre la valeur d’exemple choisie et l’attribut dans lequel elle se trouve.  
  Sélectionnez une seule option.  
  Les possibilités sont :

  - **Incohérent / hors type** : le type de valeur ne correspond pas au champ. Exemple: une date dans un champ “Ville”.  
  - **Spécification / précision** : la valeur apporte un détail ou une sous-catégorie du champ principal. Exemple: “Arrondissement 5” dans un champ “Ville”.  
  - **Niveau hiérarchique** : la valeur correspond à un niveau supérieur ou inférieur par rapport à ce que le champ devrait contenir. Exemple: “Île-de-France” dans un champ “Ville”.  
  - **Autre** : toute autre relation non listée. Exemple: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
* **Volume** : Indiquez le nombre de cas correspondant à ce type de relation


<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attribut</th>
    <th style="border:1px solid #999; padding:8px;">Exemple</th>
    <th style="border:1px solid #999; padding:8px;">Relation</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
  </tr>

  <!-- Ligne exemple pré-remplie -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_2[0][attribut]" value="Fonction" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_2[0][exemple]" value="Polynesie, bracelet coquillage" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_2[0][relation]" value="Incohérent / hors type" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q8_2[0][volume]" value="55" style="width:100%; font-style: italic;">
    </td>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_2[1][attribut]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_2[1][exemple]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_2[1][relation]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q8_2[1][volume]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des valeurs de la colonne « Nom de l’attribut/champ » de la question 5.1. Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Relation » sont :  
  \[  
  "Incohérent / hors type",  
  "Spécification / précision",  
  "Niveau hiérarchique",  
  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]

## 8.3 Ambiguïtés entre attributs au sein d’un même groupe

* Cette question n’apparaît que si la colonne « Groupe » de la question 5.1 a été rempli  
* Question "type": "matrixdynamic"  
* Facultative

Cette question vise à identifier et caractériser les ambiguïtés pouvant exister dans les relations entre les attributs d’un même groupe.

Par « ambiguïté » dans cette question, on entend toute situation où la relation entre les valeurs de différents attributs appartenant au même groupe peut être interprétée de plusieurs manières, être incohérente ou présenter un sens incertain.

Normalement, un seul type de relation devrait exister entre les attributs d’un groupe. Cependant, si les valeurs ne sont pas normalisées, différentes relations peuvent apparaître : dans ce cas, sélectionnez « Autres » et décrivez la situation.

Pour chaque combinaison d’attributs que vous avez indiquée comme faisant partie d’un groupe, veuillez remplir le tableau suivant :

**Instructions**

* **Groupe :** sélectionnez l’un des groupes d’attributs mentionnés à la question 5.1.  
* **Attribut1** : sélectionnez l’un des attributs du groupe.  
* **Attribut2** : sélectionnez l’un des attributs du groupe.  
* **Relation Logique**: indiquez le type de relations entre les valeurs de cet attribut.  
  Les possibilités sont :  
  * Valides simultanément : les valeurs des attributs peuvent coexister. Exemple : Prénom \= “Clairel” et Noms de famille \= “Lefebvre”.  
  * Compatibilité : un attribut doit être cohérent avec l’autre. Exemple: “Date de début d’exposition” \< “Date de fin d’exposition”.  
  * Autre : toute autre situation non couverte par les options ci-dessus.  
* **Relation sémantique**: indiquez le type de relations entre les valeurs de cet attribut.  
  Les possibilités sont :  
  * Équivalence : un attribut exprime la même information que l’autre, mais sous un format différent. Exemple: “Titre complet” \= “Titre abrégé \+ Sous-titre”.  
  * Variante / reformulation : un attribut est une reformulation ou une version alternative de l’autre. Exemple: “Lieu (Fr)” \= “Lieu (De)”.  
  * Complémentarité : un attribut apporte des informations différentes mais complémentaires. Exemple: “Sujet principal” \+ “Sujet secondaire”.  
  * Redondance contrôlée : un attribut double l’information de l’autre pour vérification ou normalisation. Exemple: “Date de création” enregistrée dans deux formats différents pour vérification.  
  * Autre : toute autre situation non couverte par les options ci-dessus.  
* **Relation Hiérarchique / Structurelle** : indiquez le type de relation hiérarchique / structurelle entre les valeurs de cet attribut.  
  Les possibilités sont :  
  * Partie-tout : un attribut représente une partie de l’autre. Exemple: “Chapitre” fait partie de “Livre”.  
  * Niveau hiérarchique : un attribut est imbriqué dans un autre à un niveau différent. Exemple: “Sous-collection” est imbriqué dans “Collection”.  
  * Séquentielle : attributs décrivent des étapes successives d’un processus. Exemple: “Étape de traitement documentaire” : catalogage → indexation → validation.  
  * Autre : toute autre situation non couverte par les options ci-dessus.  
* **Relation Valeur / Contenu** : indiquez le type de relations Valeur / Contenu entre les valeurs de cet attribut.  
  Les possibilités sont :  
  * Contraintes croisées : la valeur d’un attribut limite ou oriente les valeurs possibles de l’autre. Exemple: “Type de support” \= parchemin → “Format” \= feuillet simple ou codex.  
  * Valeurs dérivées : la valeur d’un attribut est calculée à partir de celle de l’autre. Exemple: “Durée de validité” calculée à partir de “Date de début” et “Date de fin”.  
  * Autre : toute autre situation non couverte par les options ci-dessus.  
* **Relation Qualification / Métadonnée** : indiquez le type de relations qualification / métadonnée entre les valeurs de cet attribut.  
  Les possibilités sont :  
  * Certitude / incertitude : un attribut indique si la valeur de l’autre est certaine, incertaine ou hypothétique. *Exemple* : “Certitude de la date” → qualifie l’attribut “Date de création” (certaine / incertaine / hypothétique).  
  * Source / provenance : un attribut documente l’origine de l’information contenue dans un autre. “Source du titre” → qualifie l’attribut “Titre de l’œuvre” (catalogue raisonné, inscription, inventaire).  
  * Autre : toute autre situation non couverte par les options ci-dessus.

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Groupe</th>
    <th style="border:1px solid #999; padding:8px;">Attribut1</th>
    <th style="border:1px solid #999; padding:8px;">Attribut2</th>
    <th style="border:1px solid #999; padding:8px;">Relation Logique</th>
    <th style="border:1px solid #999; padding:8px;">Relation Sémantique</th>
    <th style="border:1px solid #999; padding:8px;">Relation Hiérarchique / Structurelle</th>
    <th style="border:1px solid #999; padding:8px;">Relation Valeur / Contenu</th>
    <th style="border:1px solid #999; padding:8px;">Relation Qualification / Métadonnée</th>
  </tr>

  <!-- Ligne exemple pré-remplie -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[0][groupe]" value="Création" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[0][attribut1]" value="Date de création" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[0][attribut2]" value="Lieu de création" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[0][relation_logique]" value="Valides simultanément" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[0][relation_semantique]" value="Complémentarité" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[0][relation_hierarchique]" value="Sans lien Hiérarchique / Structurelle" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[0][relation_valeur]" value="Sans lien Valeur / Contenu" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[0][relation_qualification]" value="Sans lien Qualification / Métadonnée" style="width:100%; font-style: italic;">
    </td>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[1][groupe]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[1][attribut1]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[1][attribut2]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[1][relation_logique]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[1][relation_semantique]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[1][relation_hierarchique]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[1][relation_valeur]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q8_3[1][relation_qualification]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options affichées dans la colonne « Attribut1 » correspondent aux valeurs de « Nom de l’attribut/champ » de la question 5.1 pour lesquelles la colonne « Groupe » a été renseignée. Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options affichées dans la colonne « Attribut1 » correspondent aux valeurs de « Nom de l’attribut/champ » de la question 5.1 pour lesquelles la colonne « Groupe » a été renseignée. Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Relation Logique » sont :  
  \[  
  "Valides simultanément”,  
  "Compatibilité",  
  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]

* Les options de la colonne « Relation Sémantique » sont :  
  \[  
    
  "Équivalence",  
  "Variante / reformulation",  
  "Complémentarité",  
  "Redondance contrôlée",

  “Sans lien sémantique”,

  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]

* Les options de la colonne « Hiérarchique / Structurelle » sont :  
  \[  
  "Partie-tout",  
  "Niveau hiérarchique",  
  "Séquentielle",

  “Sans lien Hiérarchique / Structurelle”,

  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]

* Les options de la colonne « Relation Valeur / Contenu » sont :  
  \[  
  "Contraintes croisées",  
  "Valeurs dérivées",

  “Sans lien Valeur / Contenu”,

  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]

* Les options de la colonne « Relation Qualification / Métadonnée » sont :  
  "Certitude / incertitude",  
  "Source / provenance",

  “Sans lien Hiérarchique / Structurelle”,

  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]
---
### Pag.12
---
# 9 État de normalisation des données

## 9.1 Attributs de type « Date »

* Cette question n’apparaît que si l’une des lignes du tableau 5.1 a été sélectionnée comme « Date » dans la colonne « Type de donnée »  
* Question "type": "matrixdynamic"  
* Facultative

Cette question vise à connaître l’état de la curation des attributs de date dans votre jeu de données.

Pour chaque attribut que vous avez indiqué comme type « Date », complétez le tableau suivant.

**Instructions**

* **Attributs** : sélectionnez l’un des attributs indiqués à la question 5.1.  
* **Formats de dates** : indiquez le format selon lequel les dates doivent être exprimées pour cet attribut.  
  Sélectionnez une seule option. S’il existe plusieurs formats acceptés pour un même attribut, créez une nouvelle ligne dans le tableau pour chacun.  
  Si une partie des données n’est pas normalisée, ajoutez une nouvelle ligne correspondant à cette partie non normalisée, indiquez *texte libre* ou *autre*, puis décrivez la situation.  
  Dans le cas où aucune des options disponibles ne correspond, décrivez la forme ou la formule utilisée dans la section *Autre*.  
* **Volume** : indiquez le nombre d’entrées normalisées selon la formule indiquée pour chaque ligne, y compris pour les données non normalisées.  
* **Exemple :** illustre le format de la date avec un exemple.

 

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Formats de dates</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">Exemple</th>
  </tr>

  <!-- Ligne exemple pré-remplie -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_1[0][attributs]" value="Date de création" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_1[0][formats_dates]" value="4 chiffres (YYYY)" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_1[0][volume]" value="85200" style="width:100%; font-style: italic;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_1[0][exemple]" value="1755" style="width:100%; font-style: italic;">
    </td>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_1[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_1[1][formats_dates]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_1[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_1[1][exemple]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, qui correspondent à la valeur « Date » de la colonne « Type de donnée ». Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Formats de dates » sont :  
  \[

  « 4 chiffres (YYYY) »,  
  « 3 chiffres (YYY) »,  
  « 2 chiffres (JJ, MM ou YY) »,  
  « 2 et 4 chiffres (YYYY, MM, MM/YYYY, MM-YYYY) »,  
  « 2, 2 et 4 chiffres (JJ/MM/YYYY, MM/JJ/YYYY, YYYY;MM;JJ) »,  
  « Plage de 4 chiffres (YYY \- YYYY, YYYY/YYYY) »,  
  « Texte libre »,  
  « Autre :\_\_\_\_\_\_\_\_\_\_\_\_ »

  \]

## 9.2 Attributs de type « Identifiant interne »

* Cette question n’apparaît que si l’une des lignes du tableau 5.1 a été sélectionnée comme « Identifiant interne » dans la colonne « Type de donnée »  
* Question "type": "matrixdynamic"  
* Facultative

Cette question vise à connaître l’état de la curation des attributs « Identifiant interne » dans votre jeu de données.

Pour chaque attribut que vous avez indiqué comme « Identifiant interne », complétez le tableau suivant. 

**Instructions**

* **Attributs** : sélectionnez l’un des attributs indiqués à la question 5.1.  
* **Format de l’identifiant interne :** décrivez brièvement la structure utilisée pour construire ces identifiants.  
  Exemples :  
  * séquence numérique simple (0001, 0002\) ;  
  * combinaison alphanumérique avec préfixe de collection (COL-12345)  
  * identifiant intégrant une information sémantique sur l’objet, comme une date, une localisation ou une catégorie (ex. : année \+ code).

  Sélectionnez une seule option. S’il existe plusieurs structures acceptées pour un même attribut, créez une nouvelle ligne dans le tableau pour chacune.

  Si une partie des données n’est pas normalisée, ajoutez une nouvelle ligne correspondant à cette partie non normalisée, puis décrivez la situation.

* **Unicité :** sélectionnez si cet identifiant est unique dans l’ensemble du jeu de données ou si des répétitions peuvent exister avec d’autres entités.  
* **Clé composite :** si l’identifiant n’est pas unique et qu’il est utilisé avec un ou plusieurs autres attributs pour identifier de manière exclusive une entité, indiquez avec lequel ou lesquels il se combine.  
* **Volume** : indiquez le nombre d’entrées normalisées selon le format indiqué pour chaque ligne, y compris pour les données non normalisées.  
* **Exemple :** illustre le format de l’identifiant avec un exemple.


<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Format de l’identifiant interne</th>
    <th style="border:1px solid #999; padding:8px;">Unicité</th>
    <th style="border:1px solid #999; padding:8px;">Clé composite</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">Exemple</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[0][format_identifiant]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[0][unicite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[0][cle_composite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_2[0][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[0][exemple]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[1][format_identifiant]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[1][unicite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[1][cle_composite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_2[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_2[1][exemple]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, qui correspondent à la valeur « Identifiant interne » de la colonne « Type de donnée ». Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.)  
* Les options de la colonne « Unicité » sont :  
  \[

  "Oui",  
  "Non"

\]

* Les options de la colonne « Clé composite » correspondent à tous les attributs liés à l’entité dont l’attribut a été sélectionné dans la colonne « Attributs » de cette même table.

## 9.3 Attributs de type « Identifiant ou lien externe »

* Cette question n’apparaît que si l’une des lignes du tableau 5.1 a été sélectionnée comme « Identifiant ou lien externe » dans la colonne « Type de donnée »  
* Question "type": "matrixdynamic"  
* Facultative

Cette question vise à connaître l’état de la curation des attributs « Identifiant ou lien externe » dans votre jeu de données.

Pour chaque attribut indiqué comme type « Identifiant ou lien externe », complétez le tableau suivant.

**Instructions**

* **Attributs** : sélectionnez l’un des attributs indiqués à la question 5.1.  
* **Type de Identifiant ou lien** : indiquez le type de lien ou identifiant.  
  Sélectionnez une seule option. S’il existe plusieurs types acceptés pour un même attribut, créez une nouvelle ligne dans le tableau pour chacun.  
  Si une partie des données n’est pas normalisée, ajoutez une nouvelle ligne correspondant à cette partie non normalisée, indiquez *texte libre* ou *autre*, puis décrivez la situation.  
  Si votre type de lien n’est pas disponible, indiquez-le dans la partie « Autre ».  
* **Volume** : indiquez le nombre d’entrées normalisées selon le type indiqué pour chaque ligne, y compris pour les données non normalisées.  
* **Exemple :** illustre le type d’identifiant avec un exemple.


<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Type de Identifiant ou lien</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">Exemple</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_3[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_3[0][type_identifiant]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_3[0][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_3[0][exemple]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_3[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_3[1][type_identifiant]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_3[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_3[1][exemple]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, qui correspondent à la valeur «  Identifiant ou lien externe » de la colonne « Type de donnée ». Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Type de Identifiant ou lien » sont :  
  \[

  "IIIF",  
  "URL",  
  "URI",  
  "VIAF (Virtual International Authority File)",  
  "GeoNames",  
  "Swisstopo",  
  "Wikidata URI",  
  "WikiCite",  
  "GNA (Global Names Architecture)",  
  "PeriodO",  
  "ISO 639-3",  
  "ISO 8601",  
  "ChronOntology",  
  "ORCID (Open Researcher and Contributor ID)",  
  "ISNI (International Standard Name Identifier)",  
  "ISIL (International Standard Identifier for Libraries and Related Organizations)",  
  "DOI (Digital Object Identifier)",  
  "ARK (Archival Resource Key)",  
  "ISBN (International Standard Book Number)",  
  "ISAN (International Standard Audiovisual Number)",  
  "ISRC (International Standard Recording Code)",  
  "ISSN",  
  "Autre :\_\_\_\_\_\_\_\_\_\_\_\_"

  \]

## 9.4 Attributs de type « Lien vers une ressource numérique (interne) »

* Cette question n’apparaît que si l’une des lignes du tableau 5.1 a été sélectionnée comme « Lien vers une ressource numérique (interne) » dans la colonne « Type de donnée »  
* Question "type": "matrixdynamic"  
* Facultative

Cette question vise à connaître l’état de la curation des attributs « Lien vers une ressource numérique (interne) » dans votre jeu de données.

Pour chaque attribut indiqué comme type « Lien vers une ressource numérique (interne) », complétez le tableau suivant.

**Instructions**

* **Attributs** : sélectionnez l’un des attributs indiqués à la question 5.1.  
* **Lien interne vers une ressource** : indiquez le type de lien.  
  Sélectionnez une seule option. S’il existe plusieurs types acceptés pour un même attribut, créez une nouvelle ligne dans le tableau pour chacun.  
  Si une partie des données n’est pas normalisée, ajoutez une nouvelle ligne correspondant à cette partie non normalisée, indiquez *texte libre* ou *autre*, puis décrivez la situation.  
  Si votre type de lien n’est pas disponible, indiquez-le dans la partie « Autre ».  
* **Ressource** :  indiquez le format du fichier ou du support numérique associé (image, document texte, audio, vidéo, 3D, etc.).  
  Sélectionnez toutes les options pertinentes.  
* **Volume** : indiquez le nombre d’entrées normalisées selon le type indiqué pour chaque ligne, y compris pour les données non normalisées.  
* **Exemple :** illustre le type de lien avec un exemple.

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Type</th>
    <th style="border:1px solid #999; padding:8px;">Ressource</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">Exemple</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_4[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_4[0][type]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_4[0][ressource]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_4[0][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_4[0][exemple]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_4[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_4[1][type]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_4[1][ressource]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_4[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_4[1][exemple]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, qui correspondent à la valeur «  Lien vers une ressource numérique (interne) » de la colonne « Type de donnée ». Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Type » sont :  
  \[

  "URL interne ou externe (résoluble via le web)",  
  "Chemin ou route interne sur le serveur",  
  "Identifiant interne du système / code pointant vers la ressource",  
  "Objet binaire directement associé à l’enregistrement (champ BLOB)",  
  "Lien vers un service interne fournissant la ressource (endpoint de l’application)",  
  "Autre : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]

* Les options de la colonne « Ressource » sont :  
  \[

  "JPEG",  
  "TIFF",  
  "PNG",  
  "RAW",  
  "PDF",  
  "DOCX",  
  "TXT",  
  "RTF",  
  "HTML",  
  "EPUB",  
  "XML (EAD, MODS, METS, TEI)",  
  "RDF",  
  "JSON",  
  "MARCXML",  
  "CSV",  
  "MP3",  
  "WAV",  
  "FLAC",  
  "MKV",  
  "MP4",  
  "MOV",  
  "MKV",  
  "AVI",  
  "OBJ",  
  "STL",  
  "PLY",  
  "GLTF/GLB",  
  "FBX",  
  "HTML",  
  "WARC",  
  "EXE",  
  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]

## 9.5 Attributs de type « Lien vers une ressource numérique (externe) »

* Cette question n’apparaît que si l’une des lignes du tableau 5.1 a été sélectionnée comme « Lien vers une ressource numérique (externe) » dans la colonne « Type de donnée ».  
* Question "type": "matrixdynamic".  
* Facultative.

Cette question vise à connaître les détails des attributs « Lien externe vers une ressource » dans votre jeu de données.

Pour chaque attribut indiqué comme type « Lien vers une ressource numérique (externe) », complétez le tableau suivant.

**Instructions**

* **Attributs** : sélectionnez l’un des attributs indiqués à la question 5.1.  
* **Type** : indiquez le type de lien.  
  Sélectionnez une seule option. S’il existe plusieurs types acceptés pour un même attribut, créez une nouvelle ligne dans le tableau pour chacun.  
  Si une partie des données n’est pas normalisée, ajoutez une nouvelle ligne correspondant à cette partie non normalisée, indiquez *autre*, puis décrivez la situation.  
  Si votre type de lien n’est pas disponible, indiquez-le dans la partie « Autre ».  
* **Ressource** :  indiquez le format du fichier ou du support numérique associé (image, document texte, audio, vidéo, 3D, etc.).  
  Sélectionnez toutes les options correctes.  
* **Volume** : indiquez le nombre d’entrées normalisées selon le type indiqué pour chaque ligne, y compris pour les données non normalisées.  
* **Exemple :** illustre le type de lien avec un exemple.

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Type</th>
    <th style="border:1px solid #999; padding:8px;">Ressource</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">Exemple</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[0][type]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[0][ressource]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_5[0][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[0][exemple]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[1][type]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[1][ressource]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_5[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[1][exemple]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, qui correspondent à la valeur «  Lien vers une ressource numérique (externe) » de la colonne « Type de donnée ». Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Type » sont :  
  \[

  "URL interne ou externe (résoluble via le web)",  
  "Chemin ou route interne sur le serveur",  
  "Identifiant interne du système / code pointant vers la ressource",  
  "Objet binaire directement associé à l’enregistrement (champ BLOB)",  
  "Lien vers un service interne fournissant la ressource (endpoint de l’application)",  
  "Autre : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]

* (Les options de la colonne « Ressource » sont :  
  \[

  "JPEG",  
  "TIFF",  
  "PNG",  
  "RAW",  
  "PDF",  
  "DOCX",  
  "TXT",  
  "RTF",  
  "HTML",  
  "EPUB",  
  "XML (EAD, MODS, METS, TEI)",  
  "RDF",  
  "JSON",  
  "MARCXML",  
  "CSV",  
  "MP3",  
  "WAV",  
  "FLAC",  
  "MKV",  
  "MP4",  
  "MOV",  
  "MKV",  
  "AVI",  
  "OBJ",  
  "STL",  
  "PLY",  
  "GLTF/GLB",  
  "FBX",  
  "HTML",  
  "WARC",  
  "EXE",  
  "Autres : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_"

\]

## 9.6 Attributs de type « Lien vers une autre entité/table »

* Cette question n’apparaît que si l’une des lignes du tableau 5.1 a été sélectionnée comme « Lien vers une autre entité/table » dans la colonne « Type de donnée ».  
* Question "type": "matrixdynamic".  
* Facultative.

Pour chaque attribut indiqué comme type « Lien vers une autre entité/table », indiquez à quel autre attribut ou enregistrement il est lié et à quelle entité il fait référence.

 **Instructions**

* **Attributs1** : sélectionnez l’un des attributs indiqués à la question 5.1.  
* **Attributs2** : sélectionnez l’un des attributs indiqués à la question 5.1.  
* **Volume** : indiquez le nombre de liens établis entre les deux attributs.


<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs1</th>
    <th style="border:1px solid #999; padding:8px;">Attributs2</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[0][attributs1]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[0][attributs2]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_5[0][volume]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[1][attributs1]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_5[1][attributs2]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_5[1][volume]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, qui correspondent à la valeur «  Lien vers une autre entité/table » de la colonne « Type de donnée ». Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, **à l’exception de l’attribut déjà sélectionné dans la colonne « Attributs1 »**. Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.

## 9.7 Attributs de type « Texte Libre »

* Cette question n’apparaît que si l’une des lignes du tableau 5.1 a été sélectionnée comme « Texte Libre » dans la colonne « Type de donnée ».  
* Question "type": "matrixdynamic".  
* Facultative.

Cette question vise à connaître l’état de la curation des attributs classées comme « Texte Libre » dans votre jeu de données.

Pour chaque attribut que vous avez indiqué comme type d'attribut « Texte Libre », complétez le tableau suivant:

**Instructions**

* **Attributs** : sélectionnez l’un des attributs indiqués à la question 5.1.  
* **N° valeurs possibles (Facettes):** indiquez le nombre de valeurs distinctes observées pour cet attribut. Cela se différencie du volume, car il ne s’agit pas du nombre total d’enregistrements, mais du nombre de valeurs uniques différentes présentes dans l’attribut. Remplissez cette colonne si vous pouvez fournir ce nombre, même approximativement.  
* **Exemple (1, 2, 3, 4, 5\)** : Les colonnes « Exemple » ont pour objectif de montrer la plus grande variété possible de valeurs pour les attributs de texte libre. Pour chaque colonne (Exemple 1, 2, 3, 4, 5), remplissez avec les cas les plus divers afin de refléter la diversité des valeurs présentes dans le attribut de texte libre.


<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">N° valeurs possibles (Facettes)</th>
    <th style="border:1px solid #999; padding:8px;">Exemple1</th>
    <th style="border:1px solid #999; padding:8px;">Exemple2</th>
    <th style="border:1px solid #999; padding:8px;">Exemple3</th>
    <th style="border:1px solid #999; padding:8px;">Exemple4</th>
    <th style="border:1px solid #999; padding:8px;">Exemple5</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_7n[0][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_7n[0][nb_valeurs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[0][exemple1]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[0][exemple2]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[0][exemple3]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[0][exemple4]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[0][exemple5]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_7n[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_7n[1][nb_valeurs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[1][exemple1]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[1][exemple2]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[1][exemple3]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[1][exemple4]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_7n[1][exemple5]" style="width:100%;">
    </td>
  </tr>

</table>

</form>


* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, qui correspondent à la valeur « Texte libre » de la colonne « Type de donnée ». Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.

## 9.8 Attributs de type « Vocabulaire contrôlé »

* Cette question n’apparaît que si l’une des lignes du tableau 5.1 a été sélectionnée comme « Vocabulaire contrôlé » dans la colonne « Type de donnée ».  
* Question "type": "matrixdynamic".  
* Facultative.

Cette question vise à connaître l’état de la curation des attributs classées comme Vocabulaire contrôlé dans votre jeu de données.

Pour chaque attribut que vous avez indiqué comme type d'attribut « Vocabulaire contrôlé », complétez le tableau suivant:

**Instructions**

* **Attributs** : sélectionnez l’un des attributs indiqués à la question 5.1.  
* **Type de vocabulaire** : indiquez le type de vocabulaire utilisé pour cet attribut.  
  Sélectionnez une seule option. S’il existe plusieurs types de vocabulaires acceptés pour un même attribut, créez une nouvelle ligne dans le tableau pour chacun.  
  Si une partie des données n’est pas normalisée, ajoutez une nouvelle ligne en indiquant *autre* et décrivez la situation.  
  Indiquez « Interne \- autre » s’il s’agit d’un vocabulaire interne avec une autre organisation hiérarchique.  
  Indiquez « Autre » s’il s’agit d’un vocabulaire publié qui ne figure pas dans la liste.  
* **Volume:** indiquez le nombre d’entrées curées selon la formule indiquée pour chaque ligne, y compris pour les données non normalisées.  
* **N° valeurs du vocabulaire:** Dans le cas d’un vocabulaire interne, indiquez le nombre total de valeurs possibles du vocabulaire. Répondez uniquement à cette colonne si, dans le type de vocabulaire, vous avez indiqué un vocabulaire interne.  
* **Exemple :** illustre le format avec un exemple.  
* **Document interne** :  Téléversez ici le fichier qui présente le vocabulaire interne utilisé pour cet attribut, incluant la liste des valeurs acceptées et, le cas échéant, leur organisation ou structure hiérarchique.


<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Type de vocabulaire</th>
    <th style="border:1px solid #999; padding:8px;">Volume</th>
    <th style="border:1px solid #999; padding:8px;">N° valeurs du vocabulaire (interne)</th>
    <th style="border:1px solid #999; padding:8px;">Exemple</th>
    <th style="border:1px solid #999; padding:8px;">Document interne</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_8[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_8[0][type_vocabulaire]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_8[0][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_8[0][nb_valeurs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_8[0][exemple]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_8[0][document_interne]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_8[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_8[1][type_vocabulaire]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_8[1][volume]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="number" name="q9_8[1][nb_valeurs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_8[1][exemple]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q9_8[1][document_interne]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, qui correspondent à la valeur « Vocabulaire contrôlé » de la colonne « Type de donnée ». Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Type de vocabulaire » sont :  
  \[

  "Interne \- Liste plate (sans hiérarchie)",  
  "Interne \- Hiérarchie simple (parent-enfant)",  
  "Interne \- Thésaurus (relations hiérarchiques et associatives)",  
  "FAST (Faceted Application of Subject Terminology – OCLC/LoC)",  
  "GND (Gemeinsame Normdatei – Allemagne)",  
  "Homosaurus",  
  "LCGFT (Library of Congress Genre/Form Terms)",  
  "RAMEAU (version classique)",  
  "LCNAF (LC Name Authority File)",  
  "LCSH (Library of Congress Subject Headings)",  
  "TGM (Thesaurus for Graphic Materials – LoC)",  
  "Thésaurus UNESCO",  
  "MIGFG (Moving Image Genre-Form Guide – LoC)",  
  "SHIC (Social History and Industrial Classification)",  
  "Thesaurus Historical Person Data", "AAT (Getty Art & Architecture Thesaurus)",  
  "CONA (Cultural Objects Name Authority – Getty)",  
  "Iconclass (LOD disponible)",  
  "RAMEAU (version LOD publiée par la BnF)",  
  "TGN (Getty Thesaurus of Geographic Names)",  
  "UAT (Unified Astronomy Thesaurus)",  
  "ULAN (Getty Union List of Artist Names)",  
  "Vocabulaires suisses des arts du spectacle (forme documentaire, type d’activité, type de performance, etc.)",  
  “Interne \- autre :\_\_\_\_\_\_\_\_\_\_\_\_”,  
  "Autre :\_\_\_\_\_\_\_\_\_\_\_\_"

\]
---
### Pag.13
---
# 10 Cycle de vie

## 10.1 Périodicité de mise à jour des attributs

* Question "type": "matrixdynamic".  
* Facultative.

Cette question vise à préciser, pour chaque attribut du jeu de données, la fréquence et le mode de mise à jour de l’information ou des ressources associées.

Pour chaque attribut, indiquez la périodicité de mise à jour

**Instructions**

* **Attributs** : indiquez l’un des attributs mentionnés à la question 5.1.  
* **Périodicité de mise à jour :** indiquez la périodicité de mise à jour utilisé pour cet attribut.  
  Sélectionnez une seule option. Si plusieurs stratégies de mise à jour sont possibles pour un même attribut, sélectionnez « Autre » et expliquez la situation.  
  Les possibilités sont :  
  * Mise à jour automatique : le système met à jour l’attribut sans intervention humaine (ex. liens résolus automatiquement, identifiants synchronisés).  
  * Mise à jour semi-automatique : le système propose des mises à jour, mais la validation humaine est nécessaire.  
  * Mise à jour manuelle périodique : une personne met à jour régulièrement selon un calendrier défini.  
  * Mise à jour ponctuelle / ad hoc : l’attribut est mis à jour seulement lorsqu’un changement est identifié.  
  * Pas de mise à jour : l’attribut n’est jamais mis à jour après sa création.  
  * Autre : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Périodicité de mise à jour</th>
    <th style="border:1px solid #999; padding:8px;">Commentaires / détails</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_1[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_1[0][periodicite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_1[0][commentaires]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_1[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_1[1][periodicite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_1[1][commentaires]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1. Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Type de vocabulaire » sont :  
  \[

  "Mise à jour automatique",  
  "Mise à jour semi-automatique",  
  "Mise à jour manuelle périodique",  
  "Mise à jour ponctuelle / ad hoc",  
  "Pas de mise à jour",  
  "Autre :\_\_\_\_\_\_\_\_\_\_\_\_"

  \]

## 10.2 Durabilité et stabilité des identifiants et liens

* Cette question n’apparaît que si l’une des lignes du tableau 5.1 a été sélectionnée comme « Lien vers une autre entité/table », « Lien vers une ressource numérique (interne) », « Lien vers une ressource numérique (externe) », « Identifiant interne », ou « Identifiant ou lien externe » dans la colonne « Type de donnée ».  
* Question "type": "matrixdynamic".  
* Facultative.

Cette question vise à préciser, pour chaque attribut identifié comme identifiant ou lien, sa durabilité dans le temps, c’est-à-dire si sa valeur est permanente, stable ou susceptible de changer.

Pour chaque attribut identifié comme identifiant ou lien, indiquez sa durabilité / stabilité.

**Instructions**

* **Attributs** : indiquez l’un des attributs de lien mentionnés à la question 5.1.  
* **Durabilité / stabilité :** Sélectionnez une seule option. Si plusieurs stratégies de mise à jour sont possibles pour un même attribut, sélectionnez « Autre » et expliquez la situation.  
  Les possibilités sont :  
  * Permanent (permalien) : L’URL ou URI restera toujours valide pour accéder à la ressource dans le temps.  
  * Identifiant stable : L’attribut fournit un identifiant unique et toujours valide pour l’objet ou la ressource, même si l’objet change de contexte ou de présentation web.  
  * Identifiant ou lien susceptible de changer : L’attribut peut être modifié ou réattribué lors de migrations de données, réorganisation du système, ou changements de politique de numérotation.  
  * Autre : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
    

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Durabilité / stabilité</th>
    <th style="border:1px solid #999; padding:8px;">Commentaires</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_2[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_2[0][durabilite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_2[0][commentaires]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_2[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_2[1][durabilite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q10_2[1][commentaires]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1, qui correspondent à les valeurs «  Lien vers une ressource numérique (externe) », « Lien vers une ressource numérique (interne) », « Identifiant ou lien externe » , « Identifiant interne » de la colonne « Type de donnée ».  Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Type de vocabulaire » sont :  
  \[

  "Permanent (permalien)",  
  "Identifiant stable",  
  "Identifiant ou lien susceptible de changer",  
  "Autre :\_\_\_\_\_\_\_\_\_\_\_\_"

\]
---
### Pag.14
---
# 11 Droits et licences

* Question "type": "matrixdynamic".  
* Obligatoire.

## 11.1 Droits ou licences associés à chaque attribut

Cette question vise à identifier, pour chaque attribut du jeu de données, les droits et licences applicables à l’information ou aux ressources associées, ainsi que leur possibilité de publication sur la plateforme.

**Instructions**

* **Attributs** : indiquez l’un des attributs de date mentionnés à la question 5.1.  
* **Droits ou licences :** indiquez le type de licence ou droit associé pour cet attribut.  
  Sélectionnez toutes les options pertinentes  
  Si le droit ou la licence associée n’est pas disponible dans la liste, décrivez-le dans « Autre »

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Droits ou licences</th>
    <th style="border:1px solid #999; padding:8px;">Commentaires / détails</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q11[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q11[0][droits]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q11[0][commentaires]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q11[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q11[1][droits]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q11[1][commentaires]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1. Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Type de vocabulaire » sont :  
  \[

  "Usage interne uniquement (pas de diffusion publique)",  
  "Domaine public (ex. Public Domain Mark)",  
  "Droits réservés à l’institution / copyright interne",  
  "Droits d’auteur de tiers",  
  "CC0",  
  "CC BY",  
  "CC BY-SA",  
  "CC BY-ND",  
  "CC BY-NC",  
  "CC BY-NC-SA",  
  "CC BY-NC-ND",  
  "Licence ouverte non Creative Commons (ex. Open Government Licence, Etalab, etc.)",  
  "Open Data Commons (PDL, ODC-BY, ODbL)",  
  "Restrictions spécifiques d’utilisation par IA (ex. NoAI, clauses contractuelles)",  
  "Droit sui generis sur les bases de données (UE)",  
  "Données personnelles ou sensibles (restrictions légales)",  
  "CC BY-NC-SA",  
  "CC BY-NC-ND",  
  "Droits d’auteur de tiers",  
  "CC0",  
  "Autre :\_\_\_\_\_\_\_\_\_\_\_\_"

\]
---
### Pag.15
---
# 12 Évaluation de la publiabilité

* Question "type": "matrixdynamic".  
* Obligatoire.

## 12.1 Publiable et priorité de publication

Cette question vise à recueillir, pour chaque attribut du jeu de données, votre opinion initiale sur sa possibilité de publication sur la plateforme, ainsi que le niveau de priorité estimé pour sa diffusion. Les réponses doivent refléter votre opinion actuelle, fondée sur votre connaissance du jeu de données et de l’état de curation, sans constituer un engagement formel de publication.

**Instructions**

* **Attributs** : indiquez l’un des attributs de date mentionnés à la question 5.1.  
* **Publiable :** indiquez si l’attribut peut être publié sur la plateforme. La décision sur la publicabilité doit se baser sur votre connaissance actuelle du jeu de données et sur l’état de curation. Cette indication ne reflète que votre opinion initiale et n’engage en aucun cas la publication effective.  
  Les possibilités sont :  
  * Oui : l’information peut être publiée immédiatement.  
  * Oui ultérieurement (raison légale) : l’information ne peut pas être publiée actuellement pour razon légaux, mais il est possible qu’une modification ait lieu.  
  * Oui ultérieurement (raison curatorielle) : l’information ne peut pas être publiée actuellement pour razon de u l’état de curation), mais il est possible qu’une modification ait lieu.  
  * Non : l’information ne peut pas être publiée (ex. restrictions légales).  
  * Autre : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
* **Priorité** : indiquez le niveau de priorité estimé pour la publication de l’attribut. La priorité reflète l’importance de publier l’information, indépendamment des contraintes actuelles.  
  Les possibilités sont :  
  * Prioritaire : l’information doit être publiée en priorité.  
  * Secondaire / Moyennement prioritaire : l’information peut être publiée, mais ce n’est pas urgent.  
  * Non prioritaire : l’information peut être publiée si possible, mais ce n’est pas essentiel.  
  * Autre : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

<form>

<table style="border-collapse: collapse; width:100%;">

  <tr>
    <th style="border:1px solid #999; padding:8px;">Attributs</th>
    <th style="border:1px solid #999; padding:8px;">Publiable</th>
    <th style="border:1px solid #999; padding:8px;">Priorité</th>
    <th style="border:1px solid #999; padding:8px;">Commentaires / détails</th>
  </tr>

  <!-- Ligne vide à compléter -->
  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q12_1[0][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q12_1[0][publiable]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q12_1[0][priorite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q12_1[0][commentaires]" style="width:100%;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q12_1[1][attributs]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q12_1[1][publiable]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q12_1[1][priorite]" style="width:100%;">
    </td>
    <td style="border:1px solid #999; padding:6px;">
      <input type="text" name="q12_1[1][commentaires]" style="width:100%;">
    </td>
  </tr>

</table>

</form>

* Les options de la colonne « Attributs » dépendent des choix sélectionnés dans la colonne « Nom de l’attribut/champ » de la question 5.1. Lors de l’affichage des différentes options à choisir, l’entité de chaque attribut sera également indiquée, au cas où plusieurs entités possèdent un attribut portant le même nom.  
* Les options de la colonne « Publiable » sont :  
  \[

  "Oui",

  "Oui ultérieurement (raison légale)",  
  "Oui ultérieurement (raison curatorielle)",  
  "Non",

  "Autre :\_\_\_\_\_\_\_\_\_\_\_\_"

\]

* Les options de la colonne « Publiable » sont :  
  \[  
  "Prioritaire",  
  "Secondaire / Moyennement prioritaire",  
  "Non prioritaire"

  "Autre :\_\_\_\_\_\_\_\_\_\_\_\_"

\]
---
### Pag.16
---
# Livraison des résultats de l’enquête

Les résultats de l’enquête seront fournis sous la forme de quatre fichiers CSV : l’un contenant les informations générales de contact et sur la collection, un deuxième regroupant les données relatives aux entités identifiées, un troisième présentant les informations concernant les attributs identifiés, et un quatrième rassemblant les réponses concernant les relations entre les groupes d’attributs.

## CSV informations générales

* Il s’agit d’un tableau simple comportant une seule ligne, dont les colonnes sont :

   \[

  "1.1.- Institution",

  "1.2.- Personne",

  "1.3.- Email",

  "2.1.- Domaine",

  "2.2.- Description\_Domain",

  \]

## CSV Entités

* Chaque ligne correspond à une entité du jeu de données  
* Les colonnes du fichier contiennent les informations suivantes :

  \[

  "4.1.- Entité",

  "4.1.- Volume",

  "4.1.- Modèle",

  “4.1.- Système\_gestion”,

  “6.1.- Volume\_doublons”,

  “6.1.- Commentaires\_doublons”

  \]

## CSV Attributs

* Chaque ligne correspond à un attribut du jeu de données.  
* Chaque colonne contient la réponse à une des questions du formulaire concernant cet attribut.

  Les colonnes sont :

  \[

  "4.3.- Entité\_Modèle",

  "5.1.- Attribut\_Nom",

  "5.1.- Attribut\_Nom\_interne",

  "5.1.- Attribut\_ObliOpti",

  “5.1.- Attribut\_Type",

  “5.1.- Attribut\_Groupe",

  “5.1.- Attribut\_Langue",

  "5.1.- Attribut\_Volume",

  "5.1.- Attribut\_Description",

  "7.1.- Incertitud\_structure",

  "7.1.- Incertitud\_Expression",

  "7.1.- Incertitud\_Volume",

  "7.1.- Incertitud\_Exemple",

  "8.1.- Ambiguïté\_cardinalité\_RLogique",

  "8.1.- Ambiguïté\_cardinalité\_RSémantique",

  "8.1.- Ambiguïté\_cardinalité\_Rhiérarchique",

  "8.1.- Ambiguïté\_cardinalité\_Rqualification",

  "8.1.- Ambiguïté\_cardinalité\_Volume",

  "8.1.- Ambiguïté\_cardinalité\_Exemple",

  "8.2.- Ambiguïté\_valeurs\_Exemple",

  "8.2.- Ambiguïté\_valeurs\_Relation",

  "8.2.- Ambiguïté\_valeurs\_Volume",

  "9.1.- Normalisation\_Dates\_Formats",

  "9.1.- Normalisation\_Dates\_Volume",

  "9.1.- Normalisation\_Dates\_Exemple",

  "9.2.- Normalisation\_Identifiant\_Formats",

  "9.2.- Normalisation\_Identifiant\_Unicité",

  "9.2.- Normalisation\_Identifiant\_Formats",

  "9.2.- Normalisation\_Identifiant\_Clé",

  "9.2.- Normalisation\_Identifiant\_Volume",

  "9.2.- Normalisation\_Identifiant\_Exemple",

  "9.3.- Normalisation\_LienExterne\_Type",

  "9.3.- Normalisation\_LienExterne\_Volume",

  "9.3.- Normalisation\_LienExterne\_Exemple",

  "9.4.- Normalisation\_LienInterne\_Type",

  "9.4.- Normalisation\_LienInterne\_Ressource",

  "9.4.- Normalisation\_LienInterne\_Volume",

  "9.4.- Normalisation\_LienInterne\_Exemple",

  "9.5.- Normalisation\_LienRessourceExterne\_Type",

  "9.5.- Normalisation\_LienRessourceExterne\_Ressource",

  "9.5.- Normalisation\_LienRessourceExterne\_Volume",

  "9.5.- Normalisation\_LienRessourceExterne\_Exemple",

  “9.6.- LienRessourceinterne\_Attributs2”

  "9.7.- Normalisation\_TextLibre\_Volume",

  "9.7.- Normalisation\_TextLibre\_VFacettes",

  "9.7.- Normalisation\_TextLibre\_Exemple1",

  "9.7.- Normalisation\_TextLibre\_Exemple2",

  "9.7.- Normalisation\_TextLibre\_Exemple3",

  "9.7.- Normalisation\_TextLibre\_Exemple4",

  "9.7.- Normalisation\_TextLibre\_Exemple5",

  "9.8.- Normalisation\_Vocabulaire\_Type",

  "9.8.- Normalisation\_Vocabulaire\_Volume",

  "9.8.- Normalisation\_Vocabulaire\_NValeurs",

  "9.8.- Normalisation\_Vocabulaire\_Exemple",

  "10.1.- Cycle\_Périodicité",

  "10.1.- Cycle\_Commentaires",

  "10.2.- Cycle\_Lien\_Durabilité",

  "10.2.- Cycle\_Lien\_Commentaires",

  "11.1.- Licences",

  "11.1.- Licences\_Commentaires",

  “12.1.- Publiabilité\_Publicable”,

  “12.1.- Publiabilité\_Priorité”,

  “12.1.- Publiabilité\_Commentaires”,  
   \]

* Dans certains cas, une même question peut comporter plusieurs réponses pour un même attribut.

  C’est le cas de toutes les questions qui incluent l’instruction suivante :  
   *« S’il existe plusieurs structures acceptées pour un même attribut, créez une nouvelle ligne dans le tableau pour chacune. »*  
   (7.1, 8.1, 8.2, 9.1, 9.2, 9.3, 9.4, 9.5, 9.8).

  Dans ces cas, une nouvelle colonne est générée en dupliquant le nom de la colonne et en lui ajoutant un numéro.

  **Exemple :**

  La question 9.1 (relative à l’état de normalisation des dates) permet de préciser différents modes d’expression pour un même attribut *« Date »*.

  Chaque format (AAAA, JJ/MM/AAAA, texte libre, etc.) est alors enregistré dans une colonne distincte en modifiant le titre de la manière suivante :

  « 9.1\_Formats de dates », « 9.1\_Volume », « 9.1\_Exemple », « 9.1\_Formats de dates2 », « 9.1\_Volume2 », « 9.1\_Exemple2 », « 9.1\_Formats de dates3 », « 9.1\_Volume3 », « 9.1\_Exemple3 ».


## CSV Groupes d’attributs

* Ce CSV reproduit exactement le tableau de la question 8.3.  
* Chaque ligne représente une combinaison possible entre les attributs du groupe.  
* Chaque colonne contient la réponse à l’une des questions du formulaire concernant cette combinaison.

  Les colonnes sont :

  \[

  "8.3.- Ambiguïté\_Groupe",

  "8.3.- Ambiguïté\_Attribut1",

  "8.3.- Ambiguïté\_Attribut2",

  "8.3.- Ambiguïté\_Relation Logique",

  "8.3.- Ambiguïté\_Relation Hiérarchique / structurelle",

  "8.3.- Ambiguïté\_Relation Valeur/Contenu",

  "8.3.- Ambiguïté\_Relation Qualification/Métadonnée",  
   \]
