

---

# Data Portfolio Projekt Smart City 🚀

> In diesem Projekt sollen unterschiedliche Daten vom Open Data Portal Dortmund genutzt werden um nützliche Verbesserungen in Bezug zu Smart City Themen exemplarisch zu zeigen. Im Fokus ist die Darstellung der Ortsinformation in 2D und 3D Karten.

## 📊 Projektübersicht

**Problemstellung:** 
Daten in Open Data Portalen von Städten liegen oft in Text- und Tabellen-Formaten vor. Diese Formate sind allerdings nicht sehr anschaulich für die Bürger. 
Es heißt 80% aller Informationen haben einen Ortsbezug. Somit ist die Ortsinformation eine sehr gute Schnittstelle um unterschiedliche Daten zu verknüpfen.
Daher werden auch immer mehr Geo-Informations-Systeme (GIS) verwendet um diese Daten graphisch aufzubereiten. 
GIS Marktführer ist die Firma ESRI die mit Ihrer Software Städte bei der Visualisierung Ihrer Daten unterstüzt, wie z.B. den Kreis Lippe:
[Geoportal - Digitaler Zwilling](https://gis.kreislippe.de/portal/apps/sites/#/geoportal)
Andere Städte und Kreise möchten jedoch nur bzw. hauptsächlich Open Source Software und Lösungen verwenden, wie z.B. die Stadt Dortmund:
[Dortmund goes Open Source](https://osb-alliance.de/pressemitteilungen/dortmund-goes-open-source)

**Ziel:** 
Das Ziel des Projektes ist daher zu untersuchen wie gut Daten mit Smart City Bezug vom Open Data Portal Dortmund mit Open Source Karten wie z.B. Open-Street-Map (OSM) verknüpft werden können.   

**Methoden:** 
Mit klassischen Data Science Methoden sollen Daten vom Open Data Portal Dortmund
geladen, ggfs. aufgereitet, analysiert und graphisch dargestellt werden.
Beispiel Daten: 
[Offene Geodaten der Stadt Dortmund](https://geoweb1.digistadtdo.de/doris_gdi/opengeodata/alkis/)

Der Fokus liegt auf der Darstellung der Daten in 2D und 3D Open Source Karten,
die über einen github link erreichbar sind.
Somit sind individuelle Kartendarstellungen als Bausteine für ein persönliches Smart-City-Dashboard möglich.

---

## Setup

Dies verlinkt auf diese README Datei innerhalb dieses GitHub-Projekts:
[Zur Dokumentation](README.md)

Dies verlinkt auf die zugrunde liegende Data Science Projekt Template - Dokumentation:
[Zur Dokumentation](docs/project.md)

Lokale Hauptseite des Repositories:
[Zurück zur Repository-Startseite](/)

Komplette Webadresse:
[Projekt auf GitHub](https://github.com/T-Schulz/dppsc/tree/refs/heads/main)

Notebook Datei:
[Quellcode anzeigen](/notebooks/01_exploration.ipynb)

---

### Smart City Beispiele

1. Digitaler Zwilling H-Bahn TU-Dortmund (2D OSM Karte):
[2D_H-Bahn_TU-Dortmund](https://t-schulz.github.io/schulz-dev-hub/karte3.html)
Next step: Erweiterung H-Bahn-Netz

2. 3D Stadtmodel für das DiWoDo-Event Digitale Woche Dortmund:
[3D_Dortmund](https://t-schulz.github.io/3D_viewer/Option6_OSM_B_jumb.html)
DiWoDo Veranstaltungen:
[DiWoDo](https://www.diwodo.de/)
Next step: Event-Ortsdaten laden und mit der Karte verknüpfen.

3. Beispiel tbd: Daten Vergleich OSM vs. Stadt Geoserver ALKIS
[OSM vs. ALKIS](https://geoweb1.digistadtdo.de/doris_gdi/opengeodata/alkis/)
Next step: ALKIS Daten laden

<!--
2. Beispiel
3. Beispiel
4. Beispiel
-->

---

### Ausführung

Notebooks in dieser Reihenfolge ausführen:
1. notebooks/01_exploration.ipynb
<!--
2. notebooks/02_preprocessing.ipynb
3. notebooks/03_modeling.ipynb
4. notebooks/04_results.ipynb
-->

---
