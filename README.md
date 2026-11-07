# TP 1 : Introduction à Python – Les premières étapes

## Présentation

Ce TP a pour objectif de découvrir le langage Python et d'apprendre à utiliser ses fonctionnalités de base. Il permet de se familiariser avec l'interpréteur interactif, la création et l'exécution des fichiers Python, ainsi que la lecture et l'affichage des données.

## Étape 1 : Ouvrir l'interpréteur interactif (REPL)

Dans cette première étape, nous avons appris à ouvrir l'interpréteur interactif Python à partir de l'invite de commandes (CMD) sous Windows.

**Commande utilisée :**

```bash
python
```

Une fois l'interpréteur ouvert, le symbole `>>>` apparaît. Il permet d'écrire et d'exécuter directement des instructions Python.

**Exemple :**

```python
print("Bonjour")
```

**Résultat :**

```text
Bonjour
```

Nous avons également appris à quitter l'interpréteur avec la commande :

```python
exit()
```

## Étape 2 : Créer et exécuter un fichier Python (.py)

Dans cette étape, nous avons appris à créer notre premier fichier Python avec un éditeur de texte comme Notepad.

**Nom du fichier :** `bonjour.py`

**Code source :**

```python
# bonjour.py
print("Bonjour Python")
```

Après avoir enregistré le fichier, nous avons utilisé l'invite de commandes pour accéder au dossier contenant le programme et l'exécuter.

**Commandes utilisées :**

```bash
cd Desktop\python-labs
python bonjour.py
```

**Résultat obtenu :**

```text
Bonjour Python
```

Cette étape nous a permis de comprendre comment enregistrer un programme Python dans un fichier et comment l'exécuter depuis le terminal.

## Étape 3 : Utiliser input(), print() et les f-strings

Dans cette dernière étape, nous avons appris à interagir avec l'utilisateur en utilisant la fonction `input()` pour saisir des informations et la fonction `print()` pour afficher les résultats.

**Nom du fichier :** `bonjour_input.py`

**Code source :**

```python
prenom = input("Quel est votre prénom ? ")

print("Bonjour " + prenom)

print(f"Ravi de te rencontrer, {prenom} !")

print(f"Longueur du prénom : {len(prenom)} caractères.")
```

**Exemple d'exécution :**

```text
Quel est votre prénom ? Ikram

Bonjour Ikram
Ravi de te rencontrer, Ikram !
Longueur du prénom : 5 caractères.
```

**Fonctions et notions utilisées :**

- `input()` : permet de lire une donnée saisie par l'utilisateur.
- `print()` : permet d'afficher un message ou un résultat.
- `len()` : retourne le nombre de caractères d'une chaîne.
- `f-string` : permet d'insérer des variables directement dans une chaîne de caractères.
- `+` : permet de concaténer plusieurs chaînes de caractères.
- `strip()` : permet de supprimer les espaces au début et à la fin d'une chaîne.

## Conclusion

Ce TP nous a permis de découvrir les bases du langage Python et de comprendre son fonctionnement.

Nous avons appris à :
- Ouvrir et utiliser l'interpréteur interactif Python (REPL).
- Créer et enregistrer des fichiers avec l'extension `.py`.
- Exécuter des programmes Python depuis l'invite de commandes.
- Utiliser les fonctions `input()` et `print()`.
- Manipuler les chaînes de caractères avec `len()` et les f-strings.

**Les trois étapes ont été réalisées avec des exemples simples et fonctionnels, permettant de comprendre les premières notions essentielles de la programmation en Python.**
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/fa061cd7-fbcc-47a7-868c-2648d35e4665" />
