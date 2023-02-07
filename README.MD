<!-- Preview = Ctrl + Maj + V on VsCode-->


# Utilisation de Github
#### Liste des commandes
* ##### Exercice 1: Créer un nouveau repository. 


```bash

# Initialiser le projet. 
## S'assurer d'être à la racine du projet.
    git init  

# Ajouter un Fichier intitulé "README.md" à la liste d'attente.
    git add README.md

# Ajouter tous les fichiers à la liste d'attente
    git add * 

# Création d'un commit intitulé "first commit".
    git commit -m "first commit"

# Liaison de mon repo github à mon projet.
    git remote add origin https://github.com/NomDuProfil/NomDuRepo.git

# Copie de mon projet sur mon Repo
    git push -u origin main

### Mon repo github comporte désormais mon projet !
```

*********
* ##### Exercice 2: Travailler sur une branche secondaire. 

```bash

# Création d'une nouvelle branche nommée front_branche
    git branch front-branche

# Basculer sur la branche front-branche existante.
    git switch front-branche

# Création d'une nouvelle branche nommée "nouvelle-branche",
## Basculer automatiquement sur cette branche.
    git checkout -b nouvelle-branche

### Nouvelle branche créée !

# Supprimer une branche.
    git branch -d

```
*********
* ##### Exercice 2: Travailler sur une branche secondaire. 

```bash

#Le contenu sera directement téléchargé dans le répertoire "repertoire"

git clone git@github.com:monDossier repertoire

#Le contenu sera téléchargé dans le dossier où vous vous situez.

git clone git@github.com:monDossier .

```


