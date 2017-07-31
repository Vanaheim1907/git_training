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

- git branch <NewBranch> : Créer une nouvelle branche
 -git checkout -b : Créer la branche et se positionne directement dessus

Petite astuce pour manipuler vos branches : vous pouvez utiliser la commande 'git checkout -b' pour créer une branche et vous y positionner. Ainsi, au lieu de taper la commande suivante pour créer votre branche 
 
-git blame <fileName> : Permet de voir qui a modifier le fichier exactement

-git show <keySHA> : Permet de voir qui a modifier le fichier mais permet de savoir extactement où les modifications ont été apportées;

Pour retrouver qui a modifié une ligne précise de code dans un projet, faire une recherche avec git log peut s'avérer compliqué, surtout si le projet contient beaucoup de commits. Il existe un autre moyen plus direct de retrouver qui a fait une modification particulière dans un fichier : la commande git blame.

git blame <nomdufichier.extension>

Créez le fichier .gitignore pour y lister les fichiers que vous ne voulez pas versionner dans Git (les fichiers comprenant les variables de configuration, les clés d'APIs et autres clés secrètes, les mots de passe, etc.). Listez ces fichiers ligne par ligne dans .gitignore en indiquant leurs chemins complets

- git stash : Permet de mettre de coté les modifications en cours
	git stash pop : récupère les modifications mise de coté
Attention, pop vide votre stash des modifications que vous aviez rangées dedans. Donc une fois que vous avez récupéré ces modifications dans votre branche, il vous faut finir votre tâche et les committer ! (ou bien les remettre de côté en exécutant à nouveau la commande git stash).

Si vous voulez garder les modifications dans votre stash, vous pouvez utiliser apply à la place de pop: 
