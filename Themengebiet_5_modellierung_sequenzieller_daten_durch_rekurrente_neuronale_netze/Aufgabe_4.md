## Aufgabe 4:

in Streaming-Anbieter erhält viele schriftliche Rückmeldungen zu Filmen. Damit das Redaktionsteam schneller einen Überblick bekommt, soll automatisch eingeschätzt werden, ob eine Rückmeldung eher **positiv** oder eher **negativ** ist.

Entwickle dafür ein Modell mit TensorFlow, das anhand vorhandener Beispielbewertungen lernt, neue Bewertungen entsprechend einzuordnen. Verwende als Trainingsgrundlage den IMDb-Datensatz.

Die Texte sollen vor dem Training so vorbereitet werden, dass sie vom Modell verarbeitet werden können. Anschließend soll ein einfaches RNN mit mindestens einer LSTM-Schicht trainiert und auf Testdaten bewertet werden.

Bearbeite folgende Anforderungen:

a) Lade den IMDb-Datensatz und teile ihn in Trainings- und Testdaten auf.

b) Begrenze den Wortschatz auf die 10.000 häufigsten Wörter.

c) Bringe alle Bewertungen durch Padding auf dieselbe Länge.

d) Erstelle ein Modell mit einer `Embedding`-Schicht, einer `LSTM`-Schicht und einer Ausgabeschicht für die binäre Klassifikation.

e) Trainiere das Modell und evaluiere es mit den Testdaten.

f) Gib die Testgenauigkeit aus.

g) Begründe kurz:

- warum die Texte auf dieselbe Länge gebracht werden,
- warum eine LSTM-Schicht für Bewertungen geeignet ist,
- warum die Sigmoid-Aktivierung zur Ausgabe passt.

