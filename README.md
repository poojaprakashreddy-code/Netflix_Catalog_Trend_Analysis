# 🎬 Netflix — Content Engineering Pipeline & Catalog Trend Analysis

An end-to-end data cleansing and textual parsing pipeline designed to evaluate catalog data profiles, structure multi-value string arrays, and map global streaming media trends.

## 🚀 Key Technical Features
* **Text Processing & Imputation Engine:** Formulated dynamic data scrubbing steps to convert unformatted string scores (e.g., `6.6/10`) into high-precision continuous variables and extract absolute numeric weights from text patterns.
* **Categorical Feature Unnesting:** Implemented an array optimization script to explode combined category strings (comma-separated entries like `Horror Movies, Thrillers`), successfully eliminating downstream aggregation analysis errors.
* **Modern Trend Visualization Dashboard:** Constructed a multi-variate statistical visualization layout tracking distribution profiles across content ratings, top unnested genres, and historical release volume trajectories.
* **Clean Configuration Architecture:** Organized execution layers using an object-oriented `CatalogConfig` blueprint to guarantee fully reproducible analysis environments and prevent global variable state pollution.

## 🛠️ Local Execution 
1. Place `Netflix_Catalog_Trend_Analysis.ipynb` and `netflixData.csv` inside the same workspace directory.
2. Launch your local server environment:
   ```bash
   jupyter notebook
