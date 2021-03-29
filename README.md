#Tuto git

Ouvrir un terminal dans le dossier du projet
(pour s'y rendre: ```cd /repertoire_de_mon_projet```)

##Initialisation

- ```git init```

##Ajout repo distant (généralement nommé origin)

- ```git remote add origin url_du_repo_distant```

##Voir les repos distants associés

- ```git remote -v```

##Voir le status du projet 

- ```git status```

##Ajouter des fichiers (stage)

- ```git add nom_du_fichier```
- ```git add -A``` pour tout ajouter

##Commiter les fichiers du stage

- ```git commit -m "message_du_commit"```

##Push vers le repo distant

- ```git push origin master (ou main)```