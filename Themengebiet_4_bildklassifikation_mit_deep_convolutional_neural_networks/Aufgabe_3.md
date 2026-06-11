## Aufgabe 3:

**Gleitender Differenzfilter**

Implementiere eine Python-Funktion `apply_filter`, die eine eindimensionale Filteroperation auf einer Liste von Zahlen durchführt. Die Funktion soll zwei eindimensionale Listen als Eingabe erhalten: `values` für die Eingangswerte und `filter_kernel` für den Filter.

Die Funktion soll für jeden Wert der Eingangsliste den passenden Ausschnitt der Liste mit dem Filter verrechnen und das Ergebnis als neue Liste zurückgeben. Für die Ränder soll `same` padding mit Nullen verwendet werden, sodass die Ausgabeliste dieselbe Länge wie die Eingangsliste hat.

Du kannst davon ausgehen, dass der Filter eine ungerade Länge hat.

