## Aufgabe 4:

**Gesamtabweichung von Messwerten berechnen**

In einer Werkstatt werden an mehreren Maschinen täglich kleine Abweichungen von einem Sollwert gemessen. Die Werte liegen in einer Tabelle vor.

Jede Zeile steht für eine Maschine. Jede Spalte steht für eine Messung an dieser Maschine. Die Werte können als Abweichungen vom Sollwert verstanden werden.

Um einen einzigen Gesamtwert für die Stärke aller Abweichungen zu erhalten, soll aus allen Messwerten die L2-Norm berechnet werden.

**Aufgabenstellung**

Entwickle eine Python-Funktion, die aus den gegebenen Messwerten einen Gesamtwert für die Abweichungen berechnet.

Die Messwerte sollen als Liste von Listen gespeichert werden. Verwende keine externen Bibliotheken.

**Anforderungen**

a) Definiere eine Funktion mit dem Namen `calculate_total_deviation`.

b) Die Funktion soll eine Liste von Listen als Eingabeparameter erhalten.

c) Berechne die Summe der quadrierten Messwerte.

d) Berechne daraus die Quadratwurzel.

e) Gib den berechneten Gesamtwert zurück.

f) Begründe kurz:

- warum eine Liste von Listen für diese Messwerte geeignet ist,
- warum alle einzelnen Werte durchlaufen werden müssen,
- warum das Quadrieren und anschließende Wurzelziehen zur Fragestellung passt.

**Beispieldaten**

```
deviations = [
    [1, 2, 2],
    [3, 0, 4]
]
```

Erwartete Ausgabe:

```
5.830951894845301
```

