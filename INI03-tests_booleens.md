
<!-- .slide: data-background="#2d2d2d" -->
# Les Tests Booléens en Python
### `if`, `elif`, `else`

<br>

## Qu'est-ce qu'un test booléen ?
- **Booléen** : Un type de données qui peut être **vrai** (`True`) ou **faux** (`False`).
- **Exemples** :
  - `5 > 3` est `True`
  - `4 == 5` est `False` (double = sans espace)
  - `nom == "Alice"` est `True` si `nom` contient `"Alice"`

<br>

## Structure de base : `if`
```python
if condition:
    # bloc de code exécuté si la condition est vraie
```
- **Exemple** :
```python
age = 20
if age >= 18:
    print("Vous êtes majeur")
```

<br>

## Ajouter des alternatives : `if` et `else`
```python
if condition:
    # bloc de code exécuté si la condition est vraie
else:
    # bloc de code exécuté si la condition est fausse
```
- **Exemple** :
```python
age = 16
if age >= 18:
    print("Vous êtes majeur")
else:
    print("Vous êtes mineur")
```

<br>

## Plusieurs alternatives : `if`, `elif`, `else`
```python
if condition1:
    # bloc de code exécuté si condition1 est vraie
elif condition2:
    # bloc de code exécuté si condition2 est vraie
else:
    # bloc de code exécuté si aucune condition précédente n'est vraie
```
- **Exemple** :
```python
age = 16
if age >= 18:
    print("Vous êtes majeur")
elif age >= 13:
    print("Vous êtes adolescent")
else:
    print("Vous êtes enfant")
```

<br>

## Comparaisons courantes dans les conditions
- **Égalité** : `==` (double =)
- **Différence** : `!=` (! = sans espace)
- **Supérieur à** : `>`
- **Inférieur à** : `<`
- **Supérieur ou égal à** : `>=` (> =)
- **Inférieur ou égal à** : `<=` (< =)

<br>

## Opérateurs logiques pour combiner les conditions
- **ET** : `and`
- **OU** : `or`
- **NON** : `not`

- **Exemple** :
```python
age = 20
nationalite = "française"
if age >= 18 and nationalite == "française":
    print("Vous pouvez voter en France")
```

<br>

## Exemple complet : Gestion des Dépenses
```python
budget = 100
prix_article_1 = 50

if prix_article_1 > budget:
    print("Vous dépassez votre budget !")
elif prix_article_1 == budget:
    print("Vous avez dépensé exactement votre budget.")
else:
    print("Il vous reste de l'argent.")
```

<br>

## Pourquoi utiliser les tests booléens ?
- **Prendre des décisions** : Votre programme peut réagir différemment en fonction des situations.
- **Gérer les erreurs** : Par exemple, s'assurer qu'une variable n'est pas nulle avant de l'utiliser.
- **Créer des interactions utilisateur** : Répondre aux actions ou aux saisies de l'utilisateur.

<br>

<!-- .slide: data-background="#2d2d2d" -->
# Merci !
### Des questions ?
