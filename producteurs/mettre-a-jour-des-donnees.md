# Mettre à jour des données

Les données périmées ont un impact direct sur les usagers des transports. C'est une personne qui attend un bus qui ne passera pas par exemple. Pour cette raison, il est indispensable que vos données publiées soient toujours à jour.

### Remplacer un jeu de données existant plutôt qu'en créer un nouveau

Un jeu de données se compose d'une ou plusieurs ressources \(sous la forme de fichiers, par exemple le fichier GTFS .zip, ou les fichiers .json du GBFS sont des ressources\).

{% hint style="info" %}
Pour mettre à jour des données, il est important de ne pas créer un nouveau jeu de données, mais plutôt de remplacer les ressources concernées à l'intérieur du jeu de données.
{% endhint %}

### Procédure pas à pas pour mettre à jour

![](../.gitbook/assets/capture-de-cran-2019-07-23-a-14.16.32%20%281%29.png)

1. Allez sur transport.data.gouv.fr. Regardez en haut à droite de la page : si vous n'êtes pas déjà identifié.e, faites-le en cliquant sur _S'identifier_.
2. Sur transport.data.gouv.fr, tout en haut, cliquez sur _Publier ou mettre à jour des données_, puis _Mettre à jour un jeu de données existant_.
3. La liste des jeux de données que vous avez publiés s'affiche : cliquez sur _Sélectionner ce jeu de données ressource_ sous le jeu de données concerné. En page suivante, sélectionnez la ressource concernée.
4. Choisissez entre "_charger un fichier manuellement_" et "_indiquer une URL_" \(adresse internet qui pointe vers vos données\).
5. S'il s'agit d'un fichier GTFS, mentionnez GTFS dans le titre du fichier

### Mettre à jour ou publier une nouvelle ressource ?

Il faut mettre à jour avant expiration des données publiées, pour éviter les interruptions de service.

{% hint style="info" %}
* **Si vous publiez plus d'une semaine avant expiration** du jeu de données en cours, créez une nouvelle ressource dans le jeu de données existant.
* **Si vous publiez moins d'une semaine avant expiration**, mettez à jour \(remplacez\) la ressource concernée au sein du jeu de données existant.
* **Si vous publiez après expiration** du jeu de données précédent, mettez à jour \(remplacez\) la ressource concernée au sein du jeu de données existant.
{% endhint %}

### Dois-je indiquer une URL ou bien charger un fichier manuellement pour mes données GTFS ?

La plupart des SAEIV et autres logiciels qui fournissent du GTFS sont capables de fournir une URL, qui pointe vers leurs serveurs où le fichier GTFS est toujours à jour \(par exemple Citiway, Kisio, Mecatran...\). 

**Si votre prestataire peut vous fournir cette URL, ce sera plus pratique pour vous** : vous indiquez cette adresse une fois pour toutes et n'avez plus à vous occuper des mises à jour tant  que le fichier est à jour sur les serveurs du prestataire.

**Si ce n'est pas le cas, vous devrez publier manuellement votre fichier** - et penser à le mettre à jour avant qu'il n'expire !

### 

