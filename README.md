# Paris Centre Indicateurs BDNB

BDNB : Base de Données Nationale des Bâtiments

## Lien démonstration

https://emmaloup13.github.io/buildings/

## Description

Géovisualisation 3D de la base de données nationale des bâtiments (BDNB) sur la zone de Paris Centre (Arrondissements 1,2,3,4) : 
Nous avons extrudé les bâtiments sur cette zone. Nous visualisons les indicateurs suivants :
* Période de construction
* Diagnostic Performance Energétique et Gaz à Effet de Serre
* Date de Notation DPE
* Consommation kW/an
* Consommation en gaz

## Données
Données Paris Centre (75)

https://www.data.gouv.fr/fr/datasets/base-de-donnees-nationale-des-batiments/ 

## Installation

* Cloner ce projet

* Installer les dépendances : ``` npm install ```

* Lancer un serveur pour le développement : ``` npm start```

* Après avoir modifié le projet, si vous souhaitez publier les mises à jour : ``` npm run build ```
Dans le fichier /dist/index.html, il faut corriger les urls qui référencent les fichiers .js : 
Ajouter un "." devant le "/", ou supprimer le "/" (SANS CELA LE DEPLOIEMENT NE FONCTIONNERA PAS) 

* Lancer le déploiement : ``` npm run deploy ```

## Groupe de développement

Jacqueline Williams & Emma Bolmin
