## Aufgabe 4:

*Szenario:* 

Du entwickelst die Steuerung für einen smarten Thermostat in einem Gewächshaus. Der Thermostat soll entscheiden, ob die Heizung eingeschaltet wird (y=1) oder aus bleibt (y=0).

Es gibt zwei Sensoren, die jeweils nur zwei Zustände kennen (binär): 

- Sensor A (Temperatur): 0 = Temperatur ist okay, 1 = Temperatur ist zu niedrig.
- Sensor B (Frostschutz-Modus): 0 = Frostschutz ist deaktiviert, 1 = Frostschutz ist manuell aktiviert.

*Die Logik:* 

Die Heizung soll nur dann angehen, wenn die Temperatur zu niedrig ist ODER wenn der Frostschutz-Modus manuell aktiviert wurde.

*Deine Aufgaben*

a) Datensatz-Bestimmung: Erstelle basierend auf der obigen Logik den Datensatz in Python mit numpy. Überlege dir alle vier möglichen Kombinationen der Sensoren A und B für x und bestimme die korrekten Zielwerte y. Tipp: Es handelt sich um ein logisches ODER-Gatter.

b) Implementierung: Nutze deine bestehende Klasse Perzeptron (mit eta, n_iter, fit und predict), um das Modell auf diesen selbst erstellten Datensatz zu trainieren.

c) Validierung: Lass das trainierte Perzeptron für alle vier Kombinationen eine Vorhersage treffen. Prüfe, ob die Heizung bei der Kombination [0, 0] (Temperatur okay & Frostschutz aus) korrekterweise aus bleibt.

