# Directives de contribution

Merci d'avoir envisagé de contribuer au projet Partiel de Git ! Nous apprécions vos efforts pour améliorer ce projet. Veuillez prendre un moment pour passer en revue les directives suivantes afin d'assurer une collaboration harmonieuse.

## Table of Contents
- [Création du Repo](#création-du-repo)
- [Lier au Repo GitHub](#lier-au-repo-github)
- [Git Config](#git-config)
- [First Status, Commit, and Push](#first-status-commit-and-push)
- [Commit Signé](#commit-signé)
- [Vérifier si le Commit est Bien Signé](#vérifier-si-le-commit-est-bien-signé)
- [Créer un .gitignore](#créer-un-gitignore)
- [Créer une Branche](#créer-une-branche)
- [Respecter le Git Flow](#respecter-le-git-flow)
- [Naviguer entre les Branches](#naviguer-entre-les-branches)
- [Lister Toutes les Branches](#lister-toutes-les-branches)
- [Merge Request](#merge-request)
- [Git Pull](#git-pull)
- [README](#readme)
- [CODE_OF_CONDUCT.md](#code_of_conduct.md)
- [CONTRIBUTING.md](#contributing.md)
- [GitHub Project](#github-project)
- [Git Issue](#git-issue)


## Création du Repo

mkdir partielGit
cd partielGit
git init

## Lier au Repo GitHub

git remote add origin git@github.com:AnthonyMaquet/partielGit.git
git branch -M main
git push -u origin main

## Git Config

git config --global user.name "Prenom Nom"
git config --global user.email Mail

## First Status, Commit, and Push

git add anthony_test.txt
git status # pour vérifier ce qu'il faut/manque à ajouter
git commit -m "first commit"
git push

## Commit Signé

git commit -S -m "Commit signé Anthony"
git push

## Vérifier si le Commit est Bien Signé

git log --show-signature (-Nombre = mettre les derniers commits)

## Créer un .gitignore

à remplir

## Créer une Branche

git branch nomdelabranche

## Respecter le Git Flow

Branche main/master
Branche develop depuis la branche master
Branche(s) hotfix depuis la branche master
Branche(s) feature depuis la branche develop
Branche release depuis la branche develop
## Naviguer entre les Branches

git checkout nomdelabranche

## Lister Toutes les Branches

git branch

## Merge Request

Branche main/master
Branche develop depuis la branche master
Branche(s) hotfix depuis la branche master
Branche(s) feature depuis la branche develop
Branche release depuis la branche develop
## Git Pull

Utiliser la commande git pull pour mettre à jours la branche avec laquelle vous venez d'effectuer la merge request

## README.md

Un fichier README est un guide qui donne aux utilisateurs une description détaillée du projet sur lequel vous avez travaillé.

## CODE_OF_CONDUCT.md

Un fichier CODE_OF_CONDUCT est un document qui énonce les règles et les normes de comportement attendues de la part de tous les participants du projet.

## CONTRIBUTING.md

Un fichier CONTRIBUTING est un document qui fournit des directives et des instructions aux personnes souhaitant contribuer au projet. Il s'agit d'un guide pratique pour les contributeurs potentiels.

## GitHub Project

Github Projects permet de faire des tableaux de bord de projet. Ces tableaux sont utilisés pour organiser et suivre l’organisation liée à un projet spécifique, en fournissant une vue d'ensemble des tâches.

## Git Issue

Git Issue permet d’avoir suivi des problèmes. C'est un outil pour la gestion des problèmes, des bugs, des demandes de fonctionnalités... Les "issues" sont utilisées pour signaler, discuter et résoudre les problèmes rencontrés dans le projet.

Si vous avez des questions contactez-nous : 
anthonyhand92@gmail.com
nasrallah.khadiri@gmail.com
hamdiamine2002@gmail.com

Nous apprécions votre contribution et vous remercions pour votre soutien.
