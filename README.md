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

#First commit + push : 
- git add anthony_test.txt
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
