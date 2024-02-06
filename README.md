# AdmCO_QuestPre
```python
def add(x, y):
#Cette fonction prend 2 variables en arguments, les additionent et retourne un message pour afficher le nom du module ou #l'operation a lieu, puis retroune le resultat de l'addition
  z=x+y

  print('add() executed under the scope: ', __name__)

  return z

if __name__ == '__main__': #on verifie qu'on a pas importé un module
#on recupere deux variables
  x=input('Enter the first number to add: ')

  y=input('Enter the second number to add: ')
#on appelle la fonction pour additioner
  result = add(int(x),int(y))
# on realise un affichage
  print(x, '+', y,'=', result)

  print('Code executed under the scope: ', __name__)
```
#Questions
Pour chaque question, indiquez vos sites choisis pour reference ( où le prompt de l'outil d'IA utilisé)

  1. A quoi sert requirments.txt ?
    Il sert a transmettre les informations pour installer, configurer, initialiser... Pour pouvoir utiliser correctement l'application ou fichier.

  1. A quoi ressemble un module en python ?
      Un module python est composé de code python, il peut contenir des variables, des fonctions... qui peuvent être importé dans d'autre fichier python.
     
  1. A quoi ressemble un package ?
      un package est un ensemble de module python dans un repertoire. Il possède un nom et un fichier d'initialisation.
     
  1. Créer un code python utilisant sous forme de module addition.py
    ```python
import addition
a=5
b=2
print(addition.add(a,b))

```
  1. A quoi sert pip ? 
      pip est un gestionnaire de package. C'est-à-dire qu'il peut permettre leurs instalattions, leurs mises à jours, leurs désinstallation...

  1. A quoi sert PYTHONPATH ?
      PYTHONPATH est une varirable d'environnement qui contient le chemin d'accès aux modules pour pouvoir les importer.

  1. Où sont stockés les paquets installé par pip ?
      Sans le -user les paquets installé par pip sont installés dans le répertoire globale de python bibliothèque 
  1. A quoi sert pip install –user ? 
      Il permet de stocker les paquets dans un répertoire personnel.
  1. A quoi sert venv ? 
      Il sert a créer des environnements virtuels isolés. Cela permet de travailler sur différents projets sans que les modules interfères 
  1. Comment utiliser venv ?

  1. A quoi sert docker ?
      Un docker est un conteneur, il sert à executer une application dans un environnment isolé, avec seulement les ressources nécessaires pour éxecuter           l'applications
  1. Comment utiliser docker ?

