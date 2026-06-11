## Aufgabe 4:

**Beispielbilder für ein Erkennungssystem**

Ein kleines Entwicklungsteam arbeitet an einem Prototyp für eine Anwendung, die handgeschriebene Ziffern erkennen soll. Für erste Tests der Benutzeroberfläche werden zusätzliche ziffernähnliche Beispielbilder benötigt. Es sollen keine echten neuen Aufnahmen erstellt werden. Stattdessen sollen aus vorhandenen Beispielziffern neue, ähnliche Bilder erzeugt werden.

Verwende den `digits`-Datensatz aus `sklearn.datasets` als vorhandene Sammlung handgeschriebener Ziffern. Trainiere darauf ein Modell, das die Struktur dieser Bilder lernt, und generiere anschließend neue ziffernähnliche Beispiele.

Das Skript soll folgende Anforderungen erfüllen:

a) Lade die vorhandenen Ziffernbilder.

b) Prüfe und gib aus, in welcher Form die Bilddaten und Labels vorliegen.

c) Trainiere ein `GaussianMixture`-Modell auf den Bilddaten.

d) Erzeuge 100 neue ziffernähnliche Bilder.

e) Forme die generierten Daten wieder so um, dass sie als 8x8-Bilder dargestellt werden können.

f) Stelle die generierten Bilder in einem 10x10-Raster dar.

g) Begründe kurz:

- warum die vorhandenen Bilddaten direkt für das Modell verwendet werden können,
- warum das Modell neue Beispiele erzeugen kann,
- warum die generierten Daten vor der Darstellung wieder in 8x8-Bilder umgeformt werden müssen.

