## Aufgabe 5:

Implementiere eine einfache Version des Selbst-Aufmerksamkeitsmechanismus in Python. Verwende dazu `numpy`.

Gegeben ist eine Eingabesequenz aus drei Vektoren der Länge 4:

| Element | Wert           |
| ------- | -------------- |
| x1      | `[1, 0, 0, 0]` |
| x2      | `[0, 1, 0, 0]` |
| x3      | `[0, 0, 1, 1]` |

Erstelle daraus ein Programm, das die Selbst-Aufmerksamkeit mit Query-, Key- und Value-Matrizen berechnet.

a) Definiere die Eingabesequenz als `numpy`-Array.

b) Erstelle drei Gewichtsmatrizen für Query, Key und Value. Jede Matrix soll die Größe 4x4 haben und mit zufälligen Werten initialisiert werden.

c) Berechne aus der Eingabesequenz die Query-, Key- und Value-Matrizen.

d) Berechne zusätzlich die paarweisen Skalarprodukte der ursprünglichen Eingabesequenz, um die direkten Ähnlichkeiten der Eingabeelemente sichtbar zu machen.

e) Berechne die Aufmerksamkeitswerte aus Query und Key. Teile das Ergebnis durch die Wurzel der Dimension der Key-Vektoren.

f) Wende die Softmax-Funktion auf die berechneten Aufmerksamkeitswerte an, sodass für jedes Eingabeelement normierte Aufmerksamkeitsgewichte entstehen.

g) Berechne die gewichtete Summe der Value-Matrix mit den Aufmerksamkeitsgewichten.

h) Gib die direkten Ähnlichkeiten, die normierten Aufmerksamkeitsgewichte und die Ausgabe der Selbst-Aufmerksamkeit aus.

Begründe kurz:

- warum die Eingabesequenz als Array dargestellt wird,
- warum die Skalarprodukte zur Bestimmung von Ähnlichkeiten geeignet sind,
- warum die Softmax-Funktion verwendet wird,
- warum am Ende eine gewichtete Summe der Value-Matrix berechnet wird.

