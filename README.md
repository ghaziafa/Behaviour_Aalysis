# 📊 Advanced User/Consumer Behaviour Analysis
### Erweiterte Nutzerverhaltenanalyse

---

## 🇬🇧 English

### Project Overview
An end-to-end data analysis project that simulates, cleans, and analyses user behaviour data across 25 years (2000–2025). The project covers data pipeline construction, KPI engineering, trend prediction using machine learning, and multi-level analytical reporting.

### Project Goals
- Analyse user behaviour to extract actionable insights
- Simulate, clean, merge and enrich datasets from multiple sources
- Compute key performance indicators (KPIs) for user engagement
- Predict future user activity using a machine learning model
- Generate automated reports and interactive dashboards

### Key Features
- **Data Simulation** — generated 2,000 user session records with realistic attributes (user ID, content ID, device, session duration, timestamp)
- **Data Pipeline** — built a reusable `load_clean()` function that loads, cleans, merges and enriches data automatically
- **KPI Computation** — calculated Daily Active Users (DAU), average session duration, most viewed content, and device distribution
- **Trend Prediction** — applied Linear Regression (scikit-learn) to forecast Daily Active Users for the next 7 days
- **Cohort & Retention Analysis** — tracked user engagement patterns over time

### Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python | Core analysis language |
| pandas | Data manipulation and cleaning |
| NumPy | Data simulation and numerical operations |
| scikit-learn | Linear Regression for DAU prediction |
| Jupyter Notebook | Development and reporting environment |

### Key Insights
- Device usage is evenly distributed across Laptop, Desktop, Tablet and Smartphone (~25% each)
- `content_11` is the most viewed content with 51 views
- Average session duration varies significantly by month, peaking in certain periods
- DAU prediction model forecasts stable user activity around ~6.4 users per day

### Project Structure
```
AdvancedUserBehaviourAnalysis/
│
├── data/
│   ├── user_data.csv          ← Simulated user session data
│   └── content_meta.csv       ← Content metadata (category, author)
│
├── AdvancedUserBehaviourAnalysis.ipynb   ← Main analysis notebook
└── README.md
```

### How to Run
1. Clone the repository
2. Install dependencies: `pip install pandas numpy scikit-learn`
3. Open `AdvancedUserBehaviourAnalysis.ipynb` in Jupyter Notebook
4. Run all cells from top to bottom

---

## 🇩🇪 Deutsch

### Projektübersicht
Ein vollständiges Datenanalyseprojekt, das Nutzerverhaltensdaten über 25 Jahre (2000–2025) simuliert, bereinigt und analysiert. Das Projekt umfasst den Aufbau einer Datenpipeline, KPI-Berechnung, Trendvorhersage mittels maschinellem Lernen sowie mehrstufige analytische Berichte.

### Projektziele
- Nutzerverhalten analysieren, um handlungsrelevante Erkenntnisse zu gewinnen
- Datensätze aus mehreren Quellen simulieren, bereinigen, zusammenführen und anreichern
- Wichtige Leistungskennzahlen (KPIs) zur Nutzerbindung berechnen
- Zukünftige Nutzeraktivitäten mithilfe eines maschinellen Lernmodells vorhersagen
- Automatisierte Berichte und interaktive Dashboards erstellen

### Hauptmerkmale
- **Datensimulation** — 2.000 Nutzersitzungen mit realistischen Attributen generiert (Nutzer-ID, Inhalts-ID, Gerät, Sitzungsdauer, Zeitstempel)
- **Datenpipeline** — wiederverwendbare `load_clean()`-Funktion zum automatischen Laden, Bereinigen, Zusammenführen und Anreichern von Daten
- **KPI-Berechnung** — Berechnung von täglich aktiven Nutzern (DAU), durchschnittlicher Sitzungsdauer, meistgesehenen Inhalten und Geräteverteilung
- **Trendvorhersage** — Lineare Regression (scikit-learn) zur Vorhersage der täglich aktiven Nutzer für die nächsten 7 Tage
- **Kohortenanalyse** — Verfolgung von Nutzerengagement-Mustern über die Zeit

### Verwendete Tools
| Tool | Zweck |
|------|-------|
| Python | Hauptanalysesprache |
| pandas | Datenverarbeitung und -bereinigung |
| NumPy | Datensimulation und numerische Operationen |
| scikit-learn | Lineare Regression für DAU-Vorhersage |
| Jupyter Notebook | Entwicklungs- und Berichtsumgebung |

### Wichtige Erkenntnisse
- Die Gerätenutzung ist gleichmäßig auf Laptop, Desktop, Tablet und Smartphone verteilt (~25% jeweils)
- `content_11` ist der meistgesehene Inhalt mit 51 Aufrufen
- Die durchschnittliche Sitzungsdauer variiert erheblich je nach Monat
- Das DAU-Vorhersagemodell prognostiziert stabile Nutzeraktivität von ca. 6,4 Nutzern pro Tag

### Projektstruktur
```
AdvancedUserBehaviourAnalysis/
│
├── data/
│   ├── user_data.csv          ← Simulierte Nutzersitzungsdaten
│   └── content_meta.csv       ← Inhalts-Metadaten (Kategorie, Autor)
│
├── AdvancedUserBehaviourAnalysis.ipynb   ← Haupt-Analyse-Notebook
└── README.md
```

### Ausführung
1. Repository klonen
2. Abhängigkeiten installieren: `pip install pandas numpy scikit-learn`
3. `AdvancedUserBehaviourAnalysis.ipynb` in Jupyter Notebook öffnen
4. Alle Zellen von oben nach unten ausführen



# Humen Behaviour_Aalysis
Text analysis using regex method

Psychological Text Behavior Analyzer
This is a Python program that analyzes:
--text for sentiment, emotions, and cognitive distortions.
--Detects sentiment: positive, negative, or neutral
--Detects emotions: joy, sadness, anger, fear
--Detects common cognitive distortions: all-or-nothing thinking, catastrophizing, negative self-talk
