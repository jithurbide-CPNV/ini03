
<!-- .slide: data-background="#2d2d2d" -->

# Python

## Console


<br>


## Introduction à la console Python

La console Python est un outil interactif qui permet d'exécuter des commandes et de voir immédiatement les résultats. C’est un excellent moyen de tester des petites portions de code ou de réaliser des calculs rapidement.


<br>


### Comment accéder à la console Python

- **Sous Windows :**
  - Ouvrir le terminal (cmd ou PowerShell).
  - Taper `python` ou `python3` selon la version installée.

![Console Python sous Windows (CMD)](./images/CMD_PythonConsole.png).


<br>


- **Sous MacOS/Linux :**
	- Ouvrir le terminal.
	- Taper `python3`.


<br>


- **Dans l'application PyCharm :**
	- Cliquer sur le bouton ![PyCharm - Console Python](./images/PyCharm_05-PythonConsole_01-Open.png)


<br>


Le symbole `>>>` s'affiche lorsqu'on se trouve dans la console Python. C’est le **prompt** de Python, qui attend qu'une commande soit tapée.

``` Python Console
>>>
```

---

<!-- .slide: data-background="#2d2d2d" -->
# Python
## Interagir avec la console Python


<br>

### **Que se passe-t-il si j'entre les chiffres 5+3 ?**


```Console PyCharm
>>> 3+5
8
```

La console Python peut être utilisée comme une simple calculatrice.

<br>

**Essaye ces commandes :**
```Console PyCharm
>>> 5 - 3
?
>>> 10 * 2
?
>>> 20 / 4
?
>>> 10.0 // 2
?
>>> 11 % 3
?
```

<br>


```Console PyCharm
>>> 5 + 3
8
>>> 10 * 2
10
>>> 20.0 / 4
5.0
>>> 10.0 // 2
5
>>> 11 % 3
?
```


**Explication :** À chaque fois que vous tapez une commande mathématique dans la console, Python effectue le calcul et affiche immédiatement le résultat.


<br>

### **Déclaration et utilisation de variables**
Qu'est-ce qui se passe lorsqu'on tape les commandes suivantes dans la console ? 

**Exemple :**
```Console PyCharm
>>> x = 10
>>> y = 5
>>> z = x + y
>>> z
15
```

**Explication :** Dans l'exemple ci-dessous, `x` et `y` sont des variables qui stockent des valeurs. Quand on fait `z = x + y`, Python additionne les valeurs de `x` et `y` et les stocke dans `z`. En tapant simplement `z`, la console nous montre le contenu de la variable `z`.

Note: Expliquer que dans la console Python de PyCharm, on peut voir les variables déclarées dans la console, leur type ainsi que les valeurs stockées.

<br>

### **4. Exécution d’instructions pas à pas**
Explique aux élèves que dans la console, on peut exécuter chaque ligne de code individuellement et voir le résultat immédiatement. Cela permet de tester et corriger facilement.

**Exemple :**
```Console PyCharm
>>> nom = "Alice"
>>> age = 12
>>> print(f"Je m'appelle {nom} et j'ai {age} ans.")
Je m'appelle Alice et j'ai 12 ans.
```

**Explication :** Ici, on a stocké le prénom et l’âge dans des variables, puis on les a utilisés dans une phrase avec `print`.

---

### **5. Les erreurs dans la console**
Souligne que faire des erreurs est normal et que la console Python les affichera clairement.

**Exemple d’erreur courante :**
```bash
>>> x = 10
>>> y = "5"
>>> z = x + y
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: unsupported operand type(s) for +: 'int' and 'str'
```

**Explication :** Python ne sait pas additionner un nombre (`x = 10`) et une chaîne de caractères (`y = "5"`). L'erreur nous dit clairement ce qui ne va pas, et on peut la corriger en convertissant la chaîne en nombre avec `int()`.

---

### **6. Comment quitter la console Python**
Il est important d’expliquer comment quitter la console.

- Taper `exit()` ou utiliser le raccourci clavier `Ctrl+Z` puis `Enter` (sur Windows) ou `Ctrl+D` (sur Linux/macOS).

---

### **7. Application pratique : Résolution d’un problème simple**
Pour consolider ce qu'ils ont appris, propose un exercice simple.

**Exercice :**
Demande aux élèves d’utiliser la console pour calculer la somme de deux nombres entrés par l’utilisateur.

```bash
>>> x = int(input("Entrez un nombre : "))
Entrez un nombre : 4
>>> y = int(input("Entrez un autre nombre : "))
Entrez un autre nombre : 5
>>> somme = x + y
>>> print(f"La somme de {x} et {y} est {somme}.")
La somme de 4 et 5 est 9.
```

**Explication :** Ici, on utilise `input()` pour demander à l’utilisateur d’entrer des nombres. Ensuite, on les additionne et on affiche le résultat avec `print()`.

---

### **Conseils pour l'enseignement :**
1. **Montrer en direct :** Si possible, connecte un ordinateur à un projecteur et montre à toute la classe comment utiliser la console.
2. **Encourager l’expérimentation :** Demande aux élèves de tester leurs propres idées dans la console, comme faire d'autres calculs, essayer des chaînes de caractères, etc.
3. **Répétition :** Encourage-les à pratiquer régulièrement pour bien comprendre comment les variables et les commandes Python fonctionnent.

---

En suivant ces étapes, tu pourras introduire la console Python aux élèves de manière interactive et amusante, tout en les rendant à l’aise avec cet outil essentiel.