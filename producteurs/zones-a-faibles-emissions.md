# Zones à Faibles Emissions

transport.data.gouv.fr propose un schéma de données pour favoriser la diffusion de l'information concernant les Zones à Faibles Emissions en France par leur intégration dans les applications de mobilité. 

## Documentation

### Fonctionnement du modèle de données

Les données concernant les Zones à Faibles Emissions repose sur deux fichiers au format GeoJSON. 

* Le premier jeu de données précise les règles sur des _aires_ de la ZFE d'un territoire
* Un second jeu de données précise les règles particulières et les exceptions sur certains _tronçons routiers_. 

Les mêmes informations sont attendues sur les deux fichiers, néanmoins la modélisation géographique est différente : Polygone ou Multi-Polygone pour les _aires_ et Linestring et MultiLinestring pour les _tronçons routiers_.

