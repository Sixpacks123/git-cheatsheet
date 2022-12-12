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
```bash
git config --global user.name "[nom]"
```
Définit l'email que vous voulez associer à toutes vos opérations de commit

```bash
git config --global user.email "[adresse email]"
```
Active la colorisation de la  en ligne de commande

```bash
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
## Reset

## Update & Delete

## Branch
Liste toutes les branches locales dans le dépôt courant
```bash
git branch
```
Crée une nouvelle branche

```bash
git branch [nom-de-branche]
```
Bascule sur la branche spécifiée et met à jour le répertoire de travail

```bash
git checkout [nom-de-branche]
```
Supprime la branche spécifiée

```bash
git branch -d [nom-de-branche]
```

## Merge

## Stash

## Compare 

## Releases & Tag 

## Colaborate 