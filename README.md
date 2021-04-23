####### FANNY CAQUELARD #######

Comment créer le projet : 
Première chose il faut installer Node.js (en fonction de votre OS), ce qui va nous intaller NPM qui est un gestionnaire de dépendances.
Il va falloir installer ionic maintenant, ouvrez un terminal (avec les droits admin svp) et écrivez :

npm i -g @ionic/cli et BIM c'est installé.

Allez dans votre terminal, choisissez où dans l'arborescence vous souhaitez créer votre appli et faites :

ionic start sexplique blank --cordova (ça veut rien dire on s'en fout)
Qu'est-ce que ça fait ? ça dit à ionic de créer un projet qui s'appelle sexplique avec un template "blank" qui signifie
juste qu'il est vide et le --cordova est juste un outil qui va nous permettre de déployer sur différentes plateformes
sur mobile (Android, iOS).


##########


Comment récupérer le projet ?

Assurez vous d'avoir git d'installé (téléchargez le ici si vous l'avez pas : https://git-scm.com/downloads), ensuite écrivez dans un terminal (celui de VS Code par example, CTRL+J pour les nuls, les macs c'est CMD+J)
- git clone https://github.com/FannyCaquelard/sexplique.git

########

Je récupère le projet pour la première fois, que faire ? 

Déjà faut avoir lu la première partie.
Ensuite il faut déjà faire un npm install pour installer toutes les dépendances du projet (un nouveau dossier va apparaître c'est le node_modules, ne jamais l'envoyer sur github svp)
Pour s'assurer qu'un fichier/dossier ne soit pas envoyé sur github, veuillez le renseigner dans le fichier .gitignore pour que le projet s'en batte les steaks.
Ensuite, il faudra ajouter une plateforme sur cordova, en gros créer une structure pour que l'application puisse s'installer sur Android ou iOS.

Pour ce faire : ionic cordova platform add android ou bien ionic cordova platform add ios pour de l'iOS mais restez sur de l'android.



#########

J'ai bien travaillé, comment envoyer mon travail sur github ????

Et bien c'est tout simple, il faut que vous installiez github, allez sur le site c'est simple.
Une fois fait, ouvrez le terminal de Visual Studio Code (CTRL+J pour les nuls, les macs c'est CMD+J).
Faites (tout ce qui est entre parenthèses n'est bien sûr pas à écrire dans le terminal): 
- git add . (ça rajoute tous vos fichiers dans un état d'attente)
- git commit -m "un petit message qui explique ce que vous avez fait" (ici vous créez un commit, c'est comme la référence de votre travail)
- puis git push (pour envoyer sur github)