Bij het coderen wil je soms dezelfde paar regels code meerdere keren in je script gebruiken. Je kunt ook dezelfde paar coderegels laten uitvoeren telkens wanneer een bepaalde gebeurtenis plaatsvindt, bijvoorbeeld wanneer een specifieke toets wordt ingedrukt of een bepaalde zin wordt getypt. Voor taken als deze kun je overwegen een **functie** te gebruiken.

Functies zijn **benoemde** blokken code die een gedefinieerde taak uitvoeren. Zo ongeveer de eenvoudigste functie die je in Python kunt maken, ziet er zo uit:

```python
def hallo():
    print('Hallo wereld!')
```

Je vertelt Python dat je een nieuwe functie maakt met behulp van het trefwoord `def`, gevolgd door de naam van de functie. In dit geval wordt deze `hallo` genoemd. De haakjes achter de functienaam zijn belangrijk.

De dubbele punt aan het einde van de regel geeft aan dat de code binnen de functie wordt ingesprongen op de volgende regel, zoals in een `for` of `while` lus of een `if`/`elif`/`else` voorwaardelijke opdracht.

Je kunt een functie **aanroepen** door het intikken van de naam met de haakjes inbegrepen. Dus om de voorbeeldfunctie uit te voeren, typ je `hallo()`. Hier is het complete programma:

```python
def hallo():
    print('Hallo wereld!')

hallo()
```


