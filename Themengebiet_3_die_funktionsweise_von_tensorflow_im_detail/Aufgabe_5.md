## Aufgabe 5:

**Kraftstoffverbrauch mit linearer Regression vorhersagen**

Erstelle ein einfaches Modell mit TensorFlow, das die MPG-Werte eines Autos basierend auf ausgewählten Fahrzeugmerkmalen vorhersagt. Verwende dazu die Auto-MPG-Datenmenge aus dem UCI Machine Learning Repository.

Verwende die folgenden Schritte:

a) Lade die Auto-MPG-Datenmenge herunter und lies sie in einen Pandas-DataFrame ein.

b) Wähle die Merkmale **„Zylinder“**, **„Hubraum“**, **„PS“**, **„Gewicht“** und **„Modelljahr“** für die Vorhersage aus. Behandle diese Merkmale als numerische Eingabewerte.

c) Teile die Daten in Trainings- und Testdaten auf. Verwende 80 % der Daten für das Training und 20 % für das Testen.

d) Normalisiere die numerischen Eingabemerkmale.

e) Definiere mit TensorFlow ein einfaches lineares Regressionsmodell, das aus den gewählten Merkmalen den MPG-Wert vorhersagt.

f) Trainiere das Modell mit den Trainingsdaten und evaluiere es anschließend mit den Testdaten.

g) Gib die durchschnittliche absolute Abweichung auf den Testdaten aus.

