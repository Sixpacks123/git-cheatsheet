 # <center> Git-cheatsheet</center>

Git est un logiciel de gestion de versions décentralisé. C'est un logiciel libre et gratuit, créé en 2005 par Linus Torvalds, auteur du noyau Linux, et distribué selon les termes de la licence publique générale GNU version 2. Le principal contributeur actuel de Git, et ce depuis plus de 16 ans, est Junio C Hamano.

# Sommaire 


# Configuration
GitHub fournit des clients desktop qui incluent une interface
graphique pour les manipulations les plus courantes et une "an
automatically updating command line edition of Git" pour les scénari
avancés.

 |
GitHub pour [Mac](https://mac.github.com) |
Git pour toutes les [plate-formes](http://git-scm.com)


Définit le nom que vous voulez associer à toutes vos opérations de
commit
```
git config --global user.name "[nom]"
```
Définit l'email que vous voulez associer à toutes vos opérations de commit

```
git config --global user.email "[adresse email]"
```
Active la colorisation de la  en ligne de commande

```
git config --global color.ui auto
```
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
Liste toutes les branches locales dans le dépôt courant
```
git branch
```
Crée une nouvelle branche

```
git branch [nom-de-branche]
```
Bascule sur la branche spécifiée et met à jour le répertoire de travail

```
git checkout [nom-de-branche]
```
Combine dans la branche courante l'historique de la branche spécifiée
```
git merge [nom-de-branche]
```
Supprime la branche spécifiée

```
git branch -d [nom-de-branche]
```

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