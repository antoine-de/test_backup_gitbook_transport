# Zones à Faibles Emissions

transport.data.gouv.fr propose un schéma de données pour favoriser la diffusion de l'information concernant les Zones à Faibles Emissions en France par leur intégration dans les applications de mobilité. 

## Documentation

### Fonctionnement du modèle de données

Les données concernant les Zones à Faibles Emissions repose sur deux fichiers au format GeoJSON. 

* Le premier jeu de données précise les règles sur des _aires_ de la ZFE d'un territoire
* Un second jeu de données précise les règles particulières et les exceptions sur certains _tronçons routiers_. 

Les mêmes informations sont attendues sur les deux fichiers, néanmoins la modélisation géographique est différente : Polygone ou Multi-Polygone pour les _aires_ et Linestring et MultiLinestring pour les _tronçons routiers_.



### Représentation géographique

#### Aires couvertes par une Zone à Faibles Emissions

Les arrêtés mettant en place des Zones à Faibles Emissions précisent des aires administratives sur lesquelles s'appliquent une réglementation spécifique. Les géométries des aires couvertes correspondent donc généralement à des zones administratives : communes ou EPCI.

Ces géométries prennent pour référentiel le Référentiel Grande Echelle de l'IGN. AdminExpress peut être utilisé pour sélectionner les géométries de ces zones. 

Les géométries utilisent le système de projection WGS84. 

Si des zones spécifiques sont précisées par un arrêtés \(centre-ville, bois...\) alors le producteur de données doit modéliser aussi précisément que possible la géométrie de la zone.

#### Voies exceptionnelles

Les arrêtés précisent également régulièrement des voies spéciales où les règles de la ZFE s'appliquent différemment. 

Les géométries de ces tronçons routiers prennent pour référentiel la couche TRONCON\_DE\_ROUTE de la BD Topo de l'IGN.

Les géométries utilisent le système de projection WGS84.

### Granularité

#### Aires couvertes par une Zone à Faibles Emissions

Pour les aires, chaque ligne ou objet correspond à :

* une aire géographique
* décrite par un arrêté
* où la réglementation est homogène \(hormis axes exceptionnels\)

Aussi :

* si sur une même commune où un arrêté précise des réglementations différentes sur plusieurs zones on utilise plusieurs lignes/objets pour décrire la ZFE
* si les règles sont homogènes sur tout un EPCI mais que les arrêtés sont limités à chaque commune, on utilise autant de lignes/objets pour décrire chaque commune. 

#### Voies exceptionnelles

La granularité des voies exceptionnelles est la même que les tronçons routiers de la BD Topo de l'IGN. [La documentation de la BD Topo ](https://geoservices.ign.fr/ressources_documentaires/Espace_documentaire/BASES_VECTORIELLES/BDTOPO/DC_BDTOPO_3-0.pdf)précise qu'un tronçon de routes est une _portion de voie de communication destinée aux automobiles, aux piétons, aux cycles ou aux animaux, homogène pour l'ensemble des attributs et des relations qui la concernent_.

Le découpage d'une voie en tronçon est précisé dans la documentation de la BD Topo.

## Publication des données







