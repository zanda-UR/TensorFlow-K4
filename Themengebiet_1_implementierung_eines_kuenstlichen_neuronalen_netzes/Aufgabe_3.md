## Aufgabe 3:

Erstelle ein System, dass entscheidet, ob eine Warnlampe leuchten muss. Die Lampe soll leuchten, wenn mindestens einer von zwei Sensoren (X) ein Signal (1) gibt.

a) Definiere eine Klasse `Perzeptron`, die bei der Initialisierung die Lernrate (`eta`) und die Anzahl der Epochen (`n_iter`) akzeptiert. 

b) Implementiere in der Klasse eine `fit`-Methode, die als Parameter die Trainingsdaten `X` (Features) und `y` (Zielwerte) nimmt. Diese Methode sollte den Algorithmus des Gradientenabstiegs verwenden, um die Gewichte nach jeder Epoche basierend auf den Trainingsdaten zu aktualisieren. 

c) Füge der Klasse eine `predict`-Methode hinzu, die die Vorhersage auf Basis der gelernten Gewichte und der Eingabedaten `X` trifft. 

d) Teste dein Modell mit einem einfachen Datensatz für ein logisches oder

e) Dein Datensatz sollte wie folgt aussehen:

```
# Eingabe: Vier Kombinationen von 0 und 1
X = np.array([[0, 0], [0, 1], [1, 0], [1, 1]])
# Ziel: 1, wenn mindestens eine 1 vorhanden ist
y = np.array([0, 1, 1, 1])
```

