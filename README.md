# partielGit
Partiel de Git

#Création du Repo : 
- mkdir partielGit
- cd partielGit
- git init

#Lier au repo GitHub : 
- git remote add origin git@github.com:AnthonyMaquet/partielGit.git
- git branch -M main
- git push -u origin main

#Git config : 
- git config --global user.name "Prenom Nom"
- git config --global user.email Mail

#First status + commit + push : 
- git add anthony_test.txt
- git status (pour vérifier ce qu'il faut/manque à ajouter)
- git commit -m "first commit"
- git push 

#Commit signé : 
- git commit -S -m "Commit signé Anthony"
- git push

#Vérifier si le commit est bien signé : 
- git log --show-signature (-Nombre = mettre les derniers commits)

#Créer un .gitignore
- nano .gitignore
- remplire le fichier .gitignore
- git add .gitignore

#Créer une branche 
- git branch nomdelabranche

#Respecter le Git Flow 
- Branche main/master
- Branche develop depuis la branche master
- Branche(s) hotfix depuis la branche master 
- Branche(s) feature depuis la branche develop
- Branche release depuis la branche develop

#Naviguer entre les branches 
- git checkout nomdelabranche

#Lister toutes les branches
- git branch

#Merge Request
- Aller sur gihub
- Chercher la branche que vous souhaitez merge
- New pull request 
- Choisir la branche avec laquelle vous voulez merger
- Create pull request
- Resolver les conflits si il y en a 
- Commit merge
- Merge pull request
