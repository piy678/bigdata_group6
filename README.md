# Big Data Project:

## Projektbeschreibung
Dieses Projekt dient der Integration, Verarbeitung und Analyse von Daten aus verschiedenen Quellen mit Fokus auf Big Data Engineering (Kafka, Spark, ETL-Prozesse).

```
big-data-project-<Data Engineering-Based Analysis of Song Popularity Using Spotify and Billboard Data>/
│
├── README.md                   # Projektbeschreibung, Ziel, Teammitglieder, Technologien
├── .gitignore                  # Ignorierte Dateien (z.B. .ipynb_checkpoints, __pycache__)
├── LICENSE                     # (Optional) Lizenz, z.B. MIT, Apache 2.0
│
├── notebooks/                  # Jupyter-Notebooks
│   ├── 01_data_collection.ipynb   # Data Collection: API, Scraping, Datei
│   ├── 02_kafka.ipynb          # Kafka Producer/Consumer Setup
│   ├── 03_data_processing.ipynb   # Spark-Analyse und Transformationen
│   ├── 04_data_storage.ipynb      # Speicherung (Datenbank, Datei)
│   └── 05_visualization.ipynb     # Visualisierung und Storytelling
│
├── data/                       # Roh- und Ergebnisdaten
│   ├── raw/                       # Rohdaten aus API, Scraping, Dateien
│   └── processed/                 # Ergebnisse der ETL-Pipeline
│
├── diagrams/                   # Data Flow Diagramme, Architekturgrafiken
│   └── data_flow.png
│
├── presentation/
│   └── presentation.pdf   
└── requirements.txt            # Benötigte Python-Pakete

```

## Technologien
- Kafka
- Spark
- REST API
- Web Scraping
- Python, Pandas, etc.

## Datenquellen
1. Datei (CSV/JSON)
2. Web Scraping
3. REST API

## Workflow
1. Datenerfassung aus 3 Quellen
2. Bereitstellung der Daten über Kafka
3. Verarbeitung mit Spark
4. Speicherung und Analyse
5. Visualisierung
