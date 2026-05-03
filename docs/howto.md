# HOWTO Dromi

## Cos'è HOWTO Dromi?

**HOWTO Dromi** è una guida approfondita di Dromi.

## Strumenti da terminale

### PIP

#### Installare

Digitate nel terminale:

```bash
dromi --mdl pip install [PACKAGE]
```
- **[PACKAGE]** ⟶ Il nome pacchetto

#### Disinstallare

Digitate nel terminale:

```bash
dromi --mdl pip remove [PACKAGE]
```
- **[PACKAGE]** ⟶ Il nome pacchetto

#### Vedere tutti i moduli preinstallati

Digitate nel terminale:

```bash
dromi --mdl pip list
```

### REPL

Digitate nel terminale:

```bash
dromi --mdl repl
```

### Far partire un file

Digitate nel terminale:

```bash
dromi [NAMEFILE]
```
- **[NAMEFILE]** ⟶ Il nome file

## Sintassi

### Funzioni Python Supportate

Ecco codice esempio per le funzioni Python supportate in Dromi

```python
print("Questo è un esempio di funzione Python. Puoi usare qualsiasi funzione Python qui dentro.")
input("Input Python:")

var = 0

def funzione():
    global var
    var += 1
    print("La variabile var è ora:", var)


if var == <5:
    funzione()
elif var == 5:
    print("La variabile var è uguale a 5.")
else:
    print("La variabile var è maggiore di 5.")

class Classe:
    def __init__(self, nome):
        self.nome = nome

    def saluta(self):
        print("Ciao, il mio nome è", self.nome)

# Conclusioni:
# Dromi riesce a girare tutte le funzioni Python, tranne i suoi Imports
```

### Titoli

```Dromi
h1("Titolo 1")
h2("Titolo 2")
h3("Titolo 3")
h4("Titolo 4")
```

### Scrittura e input

```Dromi
p("Questo è un paragrafo di testo. Puoi scrivere quello che vuoi qui dentro.")
inputer("Questo è un input. Puoi scrivere qualcosa qui dentro e poi usarlo in seguito.")
```

### Variabili

```Dromi
variabili = "Questa è una variabile. Puoi usarla per memorizzare valori e usarli in seguito."
COSTANTE = "Questa è una costante. Puoi usarla per memorizzare valori che non cambiano."
lista = ["Questo", "è", "una", "lista", "di", "valori."]
tupla = ("Questo", "è", "una", "tupla", "di", "valori.")
dizionario = {"chiave1": "valore1", "chiave2": "valore2", "chiave3": "valore3"}
```

### Import Dromi

```Dromi
from mdl import windawk #dromi.exe --mdl pip install windawk - no alias
from mdl import windawk a wdwk #dromi.exe --mdl pip install windawk - alias wdwk
```

### Gestione contenuti finestra

```Dromi
clear()
update()
```

### Esecuzione finestra

```Dromi
run()
dr.init()

# run e dr.init fanno la stessa identica cosa, puoi usare quello che preferisci. run è più breve da scrivere, ma dr.init è più esplicito.
```

### Gestione finestra

```Dromi
set_window_size(600, 400) #Finestra 600x400
set_window_title("Titolo finestra")
```
