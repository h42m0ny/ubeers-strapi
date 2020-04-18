<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<h1 align="center">
  UBeers Strapi 
</h1>

Ce projet est développé dans le cadre d'un cours sur la JAM Stack donné à CESI en Avril 2020.

## Les données

Désormais nous allons construire la partie `bières` avec les données présent sur Strapi.

Les données viennet du site [bières bretonnes](bieresbretonnes.fr/) qui ont été scrappées avec Puppeteer.

Dans un premier temps, il faut créer les modèles. Voici les modèles et leurs relations :

![Image](/images/categories.png)
![Image](/images/brew.png)
![Image](/images/beers.png)
![Image](/images/relation_beers_brew.png)
![Image](/images/relation_beers_cat.png)

Ensuite, il faut charger les données dans la base `bzh-beers`. Mongo présent dans `/data/dump/`.

## Et après ?

Vous devriez avoir cela pour la recherche de la brasserie "Lancelot" :

![Image](/static/images/lancelot.png)
