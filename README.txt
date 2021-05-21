1/ Config user/email GIT:
git config --global --list
git config --global user.name saadmou 
git config --global user.email saad@hpe.com 
git config --global --list


2/ Initialisation GIT en local
git init   # Initialized umpty repository in xxx/projets/perf (master)


3/ Versionning en local
git add .      #consigner les changements dans une zone d'indexe 
git status     #verification des changements
git commit -m "explication" #Sauvegarde dans un nouveau commit avec explication

4/ Gestion des commit
git log              #affiche "commit shat-1  (HEAD -> master)
git log -n2          #afficher les 2 dernier commit
git show "shat-1"    #voir commit specifique identifie par "shat-1"
git checkout shat-1  #remettre la version sha-1
git checkout master  #remettre la vesrion la plus recente

5/ Versionning sur le depot distant


