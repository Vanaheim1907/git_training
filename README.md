# git_training
Training how to use git
- git clone <URL> : clone the repository on the local machine
- git init : Initialise le dossier à versionner 
- git add « filename » permet de rajouter à la liste des Index de git (liste des fichiers qui sont garder en mémoire)
    Pour gagner du temps, vous pouvez ajouter tous les fichiers dans le répertoire courant en tapant <git add .>
    dans la console. Évidemment, faites bien attention quand vous utilisez ce raccourci à ne pas rajouter trop de fichiers à            
    l'index.
- git commit -a -m « comment » 
    -a permet d’éviter de faire le add avant (-a correspond au add)
  
- git push <origin> <master> : push on github
    origin : repository where to commit
    master : branch

- git log : permet de voir l’historique

- git checkout <CommitSHA> permet de revenir à une version plus ancienne lorsqu’un bug/problème surviens

- git pull <origin> <master> : récupère les derniers fichiers modifier sur origin et branche master

Penser à toujours faire des git pull et git push le plus souvent possible afin d'être toujours à jour !


- git branch: Pour connaître sur quelle branche on se trouve et les branches disponible sur le répertoire

- git checkout <branchName>: switch sur la branche qu'on passe en paramètre


Et si j'étais un poisson dans l'eau à la place d'être un être humain, quel serait mon expérience de vie? 
