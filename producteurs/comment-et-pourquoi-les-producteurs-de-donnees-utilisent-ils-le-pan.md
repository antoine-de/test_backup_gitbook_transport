---
description: Le PAN au service des producteurs de données
---

# Publier des données

### Comment publier des données sur transport.data.gouv.fr ?

**Pour les données de transport en commun \(horaires théoriques et en temps réel\), ainsi que vélos en libre-service**, le référencement prend environ 10 minutes :

1. Une personne de l’Autorité Organisatrice ou de l’opérateur de transport crée un compte personnel ;
2. Elle crée un espace pour son organisation \(par exemple Nantes Métropole\) ;
3. Elle dépose le jeu de données sur la plateforme ou référence son flux de données en suivant les indications fournies par l’équipe du PAN.

La Fédération Nationale des Transports de Voyageurs \(FNTV\) met à disposition un [guide destiné aux producteurs de données](https://www.fntv.fr/IMG/pdf/19_09_26_guide_pratique_open_data.pdf) expliquant, étape par étape, la procédure de publication de données.

**Pour les aires de covoiturage, les données de stationnement et les bornes de recharge de véhicules électriques**, l’équipe de transport.data.gouv.fr agrège les données dans un fichier national unique et le dépose sur la plateforme.

### L’offre de services de l’équipe du PAN pour les producteurs de données

* **Accompagnement technique et opérationnel** des producteurs dans la mise en qualité et en conformité de leurs données \(analyse, recommandations, suivi\), conversion au format normalisé exigé par le règlement européen. Cet accompagnement permet une mise en qualité au moindre coût ;
* **Harmonisation juridique** des conditions de réutilisation des données via le recours à la licence ODbL, adoptée par le groupe de travail animé par Etalab ;
* **Moissonnage possible** : si un producteur de données dispose déjà de son propre portail de données ouvertes, le PAN peut alors agir en tant que répertoire, donnant un accès direct à ces données stockées ailleurs ;
* **Simplification des relations avec les réutilisateurs**, qui n’ont plus besoin de contacter chaque fournisseur de données. Le PAN recueille les observations sur les données publiées et les détenteurs de ces données y répondent ;
* **Conversion automatique de données au format GTFS vers le format NETEX**, via le [convertisseur Gtfs2NetexFr](http://lafabriquedesmobilites.fr/articles/innovation/gtfs2netexfr-nouvel-outil-open-source-pour-faciliter-la-production-de-donnees-transport-au-format-netex/), afin de faciliter le respect des obligations réglementaires par les producteurs de données ;
* **Conversion automatique de données au format GTFS-RT vers le format SIRI-Lite** ;
* **Économies sur les frais de serveur** avec la possibilité d’héberger sur les serveurs du PAN les flux temps-réel à haut niveau de sollicitation.

{% hint style="info" %}
_**Focus sur les données temps-réel** : l’information en temps réel permet d’augmenter sensiblement l’usage des différents services de mobilité, car l’utilisateur maîtrise mieux son temps d’attente et de trajet. Le producteur fournit un flux de données mis à jour toutes les 30 secondes. Pour cette raison, la charge sur les serveurs est une crainte légitime de nombreux producteurs. Le PAN teste actuellement une solution dans laquelle il joue le rôle de serveur mandataire \(proxy\) : seul le PAN effectue un téléchargement toutes les 30 secondes chez le producteur et les réutilisateurs téléchargent depuis le PAN._
{% endhint %}

