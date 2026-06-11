## Aufgabe 2:

**Verkaufszahlen zweier Filialen auswerten**

Ein Einzelhändler betreibt zwei Filialen. Für eine Wochenanalyse liegen die Verkaufszahlen mehrerer Produktgruppen an mehreren Tagen vor.

Die erste Dimension der Daten steht für die Produktgruppen, die zweite Dimension für die Wochentage. Für jede Filiale gibt es eine eigene Datentabelle mit denselben Produktgruppen und denselben Tagen.

Der Einzelhändler möchte wissen, wie viele Produkte insgesamt pro Produktgruppe und Tag verkauft wurden, wenn die Verkaufszahlen beider Filialen zusammen betrachtet werden.

Entwickle eine Lösung mit **TensorFlow 2.x**, die diese Auswertung durchführt.

Deine Lösung soll:

- die Verkaufszahlen beider Filialen als geeignete TensorFlow-Struktur abbilden,
- prüfen, ob beide Datensätze dieselbe Form haben,
- bei unterschiedlicher Form eine aussagekräftige Fehlermeldung ausgeben,
- bei gleicher Form die Werte positionsweise zusammenführen,
- das Ergebnis zurückgeben und ausgeben.

Erkläre außerdem kurz:

- warum du die Daten als Tensoren abbildest,
- warum die Form der beiden Datensätze geprüft werden muss,
- warum eine elementweise Addition für diese Fragestellung passend ist.

