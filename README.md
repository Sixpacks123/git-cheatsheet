 # <center> Git-cheatsheet</center>

## Sommaire 


## Global Settings
## Commande de base
Créer un nouveau répertoire local
```bash
git init
```
Cloner un répertoire
```bash
git clone https://github.com/Sixpacks123/git-cheatsheet.git
```
Afficher l'état du répertoire de travail et de la zone de staging
```bash
git status
```
Ajouter tous les changements pour le prochain commit
```bash
git add .
```
Afficher les modifications entre les commits, un commit et l’arbre de travail, etc
```bash
git diff
```
Envoyer toutes les modifications locales 
```bash
git commit -a
```
Envoyer les modifications récentes
```bash
git commit
```
Charger le contenu d'un dépôt local vers un dépôt distant
```bash
git push
```
Rapatrier et intégrer un autre dépôt ou une branche locale
```bash
git pull
```
Montrer tous les commits, en commençant par le plus récent
```bash
git log
```
## Reset
Réinitialiser la HEAD actuelle à l'état spécifié
```bash
git reset 
```

## Update & Delete

## Branch

## Merge
>Intègre tous les fichiers de développement dans une seule branche, combine deux branches et fusionne plusieurs commits en un seul historique. La fusion s'arrête en cas de conflit et git présente les fichiers en conflit. Une fois les conflits résolus, la fusion se poursuit.

- d'abord, vérifiez la branche à fusionner
```bash
git checkout -b
```
```bash
git add <file>
```
- ajouter et valider les fichiers
```bash
git commit
```
```bash
git checkout master
```
- fusionner la branche avec master
```bash
git merge
```

## Stash

## Log

## Compare 

## Releases & Tag 

## Colaborate 