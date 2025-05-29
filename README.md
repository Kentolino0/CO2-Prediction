# 🌍 CO₂-Emissionen Vorhersage (1980–2035)

Dieses Projekt analysiert globale CO₂-Daten und sagt die zukünftige Entwicklung der Emissionen mit Hilfe von Python und Linearer Regression voraus. Es verwendet öffentliche Daten mit Länder-, Jahres- und CO₂-Angaben.

---

## 📊 Inhalt

- Berechnung des globalen Durchschnitts der CO₂-Werte pro Jahr
- Visualisierung des zeitlichen Trends (1980–heute)
- Lineare Regression zur Vorhersage der CO₂-Werte bis 2035
- Optional: Zoom auf interessante Zeiträume (z. B. 1990)

---

## 📁 Dateien

| Datei            | Beschreibung                                              |
|------------------|-----------------------------------------------------------|
| `co2_analysis.py`| Haupt-Python-Skript für Analyse und Visualisierung        |
| `co2_data.csv`   | Datensatz (z. B. mit Spalten: `CountryCode`, `CountryName`, `Year`, `Value`) |
| `README.md`      | Diese Datei                                               |

---

## 🛠️ Benötigte Bibliotheken

Installiere die benötigten Pakete mit:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
