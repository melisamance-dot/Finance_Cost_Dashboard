# Finance & Cost Analytics Dashboard

Dieses Projekt zeigt, wie man mit Python eine **Kostenanalyse** inklusive **Forecasting** aufbaut.  
Es ist ein Portfolio-Projekt, das die Nutzung von **Datenanalyse, Visualisierung und maschinellem Lernen** demonstriert.
---
## Features
- Simulierte Monatskosten für Material, Personal und Betrieb
- KPI-Berechnung:
  - Gesamtkosten pro Monat
  - Durchschnittskosten pro Kategorie
- Visualisierung:
  - Gesamtkostenentwicklung
  - Kostenentwicklung nach Kategorien
  - Balkendiagramm der Durchschnittskosten
- Forecasting:
  - Lineare Regression zur Vorhersage der Gesamtkosten für die nächsten 6 Monate
---
## Technologien
- Python 3.x
- Bibliotheken:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
---
## Installation
1. Repository klonen:
```bash
git clone https://github.com/melisamance-dot/Finance_Cost_Dashboard.git

python -m venv .venv
# Windows
.venv\Scripts\activate
pip install -r requirements.txt

## Screenshots

### Gesamtkosten pro Monat
![Gesamtkosten](screenshots/total_cost.png)

### Kostenentwicklung nach Kategorien
![Kosten nach Kategorien](screenshots/cost_by_category.png)

### Forecast der Gesamtkosten
![Forecast](screenshots/forecast.png)
