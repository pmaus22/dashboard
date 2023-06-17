# Logbuch

## 05.05.23

- Thema festgelegt: Ausarbeitung der Corona Daten, wie zum Beispiel Fallzahlen, Todesfälle mit Unterscheidung von MIT und AN Corona gestorben, 
Impfungen mit Anzahl der Dosen, Intensivbettenbelegung (mit Corona infiziert) und Intensivbetten auch außerhalb von Corona Infektionen (alles mit Zeitstempel und Vergleiche verschiedener Datenquellen)
- Dashboard-Erstellung initial per Grafana und InfluxDB geplant. Mit den Tools gibt es in der Gruppe bereits Erfahrungen. Sie werden zwar hauptsächlich zur Echtzeitüberwachung eingesetzt, eignen sich aber auch zum Speichern und Darstellen von Daten über einen längeren Zeitraum.
- Grafana-Container auf privatem Server aufgesetzt
- Accounts und Berechtigungen in Grafana angelegt

## 26.05.23

- InfluxDB-Container auf privatem Server aufgesetzt
- InfluxDB-Datenquelle in Grafana eingerichtet
- Recherche nach CSV-Datenquellen und APIs bei RKI, Destatis, Statista, ... (Hier muss beachtet werden, dass die Aufzeichnung von Corona-Daten mittlerweile teilweise eingeschränkt oder eingestellt wurden.)
- Konzept für einzelne Dashboards erstellt
- Tests zum Datenimport von CSV-Dateien in InfluxDB
- Datenimport stellt sich bei InfluxDB als schwierig heraus, da im CSV-Format Annotations mit Metadaten gefordert werden, welche nicht in den Datenquellen enthalten sind

## 02.06.23

- Entscheidung, auf Power BI als Tool zur Datenvisualisierung umzusteigen
- Thesen aufgestellt: Welche Fragestellungen sollen wir mit dem Dashboard beantworten?
- Weitere Konzeption und Ideensammlung zu spezifischen Statistiken
- Quellensammlung zu spezifischen Statistiken
- Einarbeitung Power BI
- Themenverteilung: Wer erstellt den Bericht zu welcher Fragestellung?

## 16.06.23

- Erstellung erster Mockups in Power BI
- Ideenbesprechung und Ausarbeitung eines Konzepts für das Dashboard
