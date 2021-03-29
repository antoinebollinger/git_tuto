# Tuto git

Ouvrir un terminal dans le dossier du projet (pour s'y rendre: ```cd /repertoire_de_mon_projet```).

## Initialisation

- ```git init```

## Gestion des branches 

### Affichage des branches

- ```git branch```
Cela renvoie la liste des branches. La branche actuelle chargée est marquée d'un astérisque (*).
La branche principale par défaut est appelée ```master```.

### Ajout de branche 

- ```git branch nom_de_la_branche```

### Changer de branche de travail

- ```git checkout nom_de_la_branche```

## Gestion des repos distants

### Ajout repo distant (généralement nommé origin)

- ```git remote add origin url_du_repo_distant```

### Voir les repos distants associés

- ```git remote -v```

## Voir le status du projet 

- ```git status```

## Ajouter des fichiers (stage)

- ```git add nom_du_fichier```
- ```git add -A``` pour tout ajouter

## Commiter les fichiers du stage

- ```git commit -m "message_du_commit"```

## Push d'une branche (ici master) vers le repo distant (ici origin)

- ```git push origin master```

## Illustration

![Illustration](https://user-images.githubusercontent.com/56133015/112811080-fc1bf580-907b-11eb-8e1e-2dd63788bc3c.jpg)