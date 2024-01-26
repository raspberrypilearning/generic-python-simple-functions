Lors du codage, il arrive que tu veuilles utiliser les mêmes lignes de code plusieurs fois dans ton script. Tu peux aussi vouloir que les mêmes lignes de code soient exécutées chaque fois qu'un certain événement se produit, par exemple lorsqu'une touche spécifique est appuyée ou qu'une expression particulière est tapée. Pour des tâches comme celle-ci, tu peux envisager d'utiliser une **fonction**.

Les fonctions sont des blocs de code **nommés** qui effectuent une tâche définie. La fonction la plus simple que tu puisses créer en Python ressemble à ceci :

```python
def bonjour():
    print('Bonjour le monde !')
```

Tu indiques à Python que tu crées une nouvelle fonction en utilisant le mot-clé `def`, suivi du nom de la fonction. Dans ce cas, elle s'appelle `bonjour`. Les parenthèses qui suivent le nom de la fonction sont importantes.

Les deux points à la fin de la ligne indiquent que le code à l'intérieur de la fonction sera indenté sur la ligne suivante, comme dans une boucle `for` ou `while` ou un `if`/`elif`/`else` conditionnel.

Tu peux **appeler** une fonction en tapant son nom avec les parenthèses incluses. Ainsi, pour exécuter la fonction d'exemple, tu taperais `bonjour()`. Voici le programme complet :

```python
def bonjour():
    print('Bonjour le monde !')

bonjour()
```


