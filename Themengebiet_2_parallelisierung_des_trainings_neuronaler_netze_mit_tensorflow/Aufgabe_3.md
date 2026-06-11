## Aufgabe 3:

**L2-Norm eines zweidimensionalen Tensors berechnen**

Entwickle eine Python-Funktion, die die **L2-Norm** eines gegebenen zweidimensionalen Tensors berechnet.

Der Tensor soll als **Liste von Listen** dargestellt werden. Jede innere Liste steht für eine Zeile des Tensors.

Die Funktion soll alle Werte des Tensors quadrieren, die Quadrate aufsummieren und anschließend die Quadratwurzel dieser Summe berechnen.

Verwende keine externen Bibliotheken wie NumPy oder TensorFlow.

**Anforderungen**

a) Definiere eine Funktion mit dem Namen `calculate_l2_norm`.

b) Die Funktion soll einen Tensor als Eingabeparameter erhalten.

c) Iteriere über alle Zeilen und alle Elemente des Tensors.

d) Berechne die Summe der quadrierten Elemente.

e) Gib die Quadratwurzel dieser Summe zurück.

**Beispiel**

Eingabe-Tensor:

```
tensor = [
    [2, 0],
    [3, 6]
]
```

Aufruf der Funktion:

```
result = calculate_l2_norm(tensor)
```

Erwartete Ausgabe:

```
7.0
```

