# Les fonctions en Python

## Objectif
Apprendre à écrire et utiliser une fonction.

## Syntaxe pour définir une fonction



## Exercice
1. Crée un nouveau fichier Python "multiple.py". 
> Note: Il est important de ne pas oublier l'extension ".py" des fichiers qui contient du code Python. Cela indique à l'ordinateur que c'est un code à exécuter par l'interpréteur Python.

2. Crée une fonction "is_multiple" qui est vide pour le moment dans le fichier "multiple.py" comme suivant:
```python 
def is_multiple(): 
    pass
```

3. Appelle la fonction "is_multiple" pour voir ce qu'elle retourne dans le Terminal (on dit aussi sur "la sortie stardard") à l'aide de la fonction "print" comme suivant:
```python
print("La fonction is_multiple retourne la valeur:", is_multiple())
```
Qu'observes-tu ?

4. Modifie la fonction "is_multiple" pour qu'elle retourne tout le temps la valeur "True".

5. Ajoute un paramètre "number" à la fonction "is_multiple" et écris le code qui permet:
- de retourner True si "number" est un multiple de 3 
- et de retourner "False" dans les autres cas. 

Pour tester ta fonction, tu peux par exemple modifier et rajouter les appels de la fonction avec plusieurs cas comme suivant:

```python
print("La fonction is_multiple retourne la valeur:", is_multiple(10))
print("La fonction is_multiple retourne la valeur:", is_multiple(27))
print("La fonction is_multiple retourne la valeur:", is_multiple(-3))
print("La fonction is_multiple retourne la valeur:", is_multiple(0))
```

6. Ajoute un autre paramètre "diviseur" et écris le code qui permet :
- de retourner True si "number" est un multiple de "diviseur"
- et de retourner "False" dans les autres cas. 

Pour tester ta fonction, tu peux par exemple modifier et rajouter les appels de la fonction avec plusieurs cas.