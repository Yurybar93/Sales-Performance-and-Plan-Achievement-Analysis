# Analyse der Verkaufsleistung und der Planerfüllung

## Überblick
Dieses Projekt konzentriert sich auf die Analyse der Verkaufsleistung, der Planerfüllung und der Rentabilität in verschiedenen Regionen und Kategorien. Es umfasst auch die Visualisierung wichtiger Kennzahlen wie Umsatz, Gewinn und den Prozentsatz der Planerfüllung. Die Analyse erfolgt anhand historischer Verkaufsdaten und umfasst die Prognose für zukünftige Zeiträume basierend auf historischen Trends.

## Funktionen
- Datenanalyse zu Umsatz und Gewinn in verschiedenen Regionen und Kategorien.
- Berechnung und Visualisierung der Planerfüllung.
- Identifizierung von Regionen und Kategorien mit niedriger Leistung (unter 70% der Planerfüllung).
- Zeitreihenprognose mit dem SARIMA-Modell zur Vorhersage zukünftiger Umsätze.
- Visualisierungen wie Streudiagramme, Balkendiagramme und Liniendiagramme.

## Projektstruktur
- **data/**: Enthält das Datenset (CSV ).
- **notebooks/**: Jupyter-Notebooks mit Analysecodes.
- **scripts/**: Python-Skripte für Datenanalyse und Visualisierung.
- **requirements.txt**: Eine Liste der benötigten Python-Bibliotheken.

## Anforderungen
Um dieses Projekt auszuführen, benötigen Sie Python 3.x und die folgenden Bibliotheken:

- pandas
- numpy
- matplotlib
- statsmodels
- seaborn
- scikit-learn

Installieren Sie die benötigten Bibliotheken mit folgendem Befehl:

```bash
pip install -r requirements.txt
