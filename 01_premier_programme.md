# Premier pas vers la Programmation

## Objectif
Apprendre à écrire et exécuter ton premier programme Python en utilisant "***Visual Studio Code***" et ce que tu as appris sur le fonctionnement d'un "***Terminal Linux***".

## Programmer avec "*Visual Studio Code*"
1. Pour commencer, cherche l'application "*Visual Studio Code*" sur ton "*Bureau*" ("*Desktop*" en anglais) et lance-la.
> Une fenêtre s'ouvre avec 2 parties principales:
> - celle de gauche: c'est là qu'on va écrire/éditer le programme
> - celle de droite: ton fameux "***Terminal Linux***" où tu peux lancer les mêmes commandes que tu as apprises précédemment.

2. Dans la partie "***Terminal***" de l'application, déplace-toi dans ton répertoire de travail `/home/chase/ApprendreInformatique/` avec les bonnes commandes.

3. Crée un nouveau repertoire avec le nom "ApprendrePython"

4. Place-toi dans ce nouveau repertoire et verifie s'il est vide (j'espère que tu te souviens de la bonne commande à lancer pour cela :P )

5. Regarde maintenant sur la partie de gauche et ouvre le répertoire "ApprendrePython" que tu viens de créer.

> Astuce: Clique sur l'icône tout en haut à gauche si tu n'a plus la page de bienvenue

![VS Code - Ouvrir un répertoire](./Images/ouvrir_repertoire.png)

6. Trouve le moyen de créer un nouveau fichier que tu nommera "hello_world.py"

7. Dans ton "Terminal" lance la commande 
```
ls -l
``` 
pour voir ce qu'il s'est passé.

8. Toujours dans ton "Terminal", lance la commande:
 ```
 python3 hello_world.py
 ``` 
 Qu'observes tu ?

9. Dans la partie de gauche, tu visualises normalement le contenu du fichier "hello_world.py" que tu as créé et qui devrait être vide. Maintenant ecrit le code suivant dans le fichier:
```
print("Hello World!")
```
Sauvegarde le fichier (raccourci clavier: `Ctrl + S`)

10. Dans ton "*Terminal*", relance de nouveau la commande :
```
python3 hello_world.py
```  
Qu'observes-tu cette fois-ci ? 

11. Observe le code dans la partie gauche et essaye de le modifier pour qu'il affiche le message suivant:
```
Youpi! J'ai réussi à écrire et lancer mon premier programme en Python
```

12. Sauvegarde tes modifications et lance ton programme de nouveau:
```
python3 hello_world.py
```
> Attention: Bien penser à sauvegarder ton fichier qui contient le code avant de l'executer avec l'*interpreteur de code* python3

## A savoir: Visual Studio Code (ou VSCode) est un IDE
Un IDE (*Environnement de Developpement Integré* ou *Integrated Development Environment* en anglais) est une application qui permet de faciliter le developpement de code logiciel par le programmeur. 
Il comprend en general l'ensemble des fonctionnalités et outils nécessaires au développement de programme de qualité comme par exemple:
- La **coloration syntaxique**: Il connaît la grammaire du langage de programmation et les mots clé et utilise differentes couleurs, formats de polices de caractère pour faciliter la lecture du code.
- La **complétion du code intelligente**: Propose des suggestions de complétion d'une instruction de code lorsque le développeur commence à taper
- La **détection d'erreurs**: Indique instantanément les erreurs si pas conforme au langage de programmation.
- La **compilation, test et déboggage**: Des boutons ou des raccourcis pour lancer ces étapes
- Un **Terminal** intégré
- Et bien d'autres que vous apprendrez plus tard.

> Il est donc indispensable de nos jour de coder dans un IDE et pas dans un simple Editeur de texte. C'est l'outils incontournable d'un bon programmeur.

## A savoir: Python est un langage "***interprété***"
Python est un langage "***interprété***" qui nécessite un "***Interpréteur***" sur l'ordinateur d'exécution qui va alors transformer le **code source** du programme en **langage machine** (des suites d'intructions codées en binaires que l'ordinateur comprend et exécute: de la forme 0110101010100101001 par exemple) **au moment de l'exécution** du programme.  
Dans ce que vous avez manipuler plus haut, `python3` est l'***interpréteur*** qui a permis de transformer le code source dans le fichier `hello_world.py` en une série d'instructions compréhensibles et exécutables par l'ordinateur.
Il existe aussi des langages dits "***compilés***" qui ne nécessitent pas d'Interpréteur à l'exécution du programme mais qui utiliseront un "***Compilateur***" pour transformer le **code source** du langage de programmation en **code machine** dans un fichier **exécutable**. Celui-ci pourra donc etre lancé directement sans passer par un Interpréteur.      