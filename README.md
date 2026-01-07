# Drug Safety Dashboard using Holoviz

## Project Overview
This project analyzes adverse event data from the U.S. Food and Drug Administration (FDA) Adverse Event Reporting System (FAERS) to generate Data Dashboard. The analysis demonstrates data cleaning, preprocessing, exploratory analysis, and visualization using HoloViz, with a focus on glucagon-like peptide-1 (GLP-1) receptor agonists.

## Data Souurce
Data were obtained from the FDA FAERS (FDA Adverse Event Reporting System) Public Dashboard and filtered to include reports involving all GLP-1 receptor agonists. FAERS is a spontaneous reporting system that contains adverse event reports submitted by healthcare professionals, manufacturers, and consumers. (Note: FAERS data are subject to reporting bias, duplication, and missingness and are intended for signal detection rather than incidence estimation.)

## Folder Structure
- `notebooks/` - Jupyter notebooks: data cleaning, dashboard app
- `data/` - Sample CSV used for analysis
- `requirements.txt` - Python dependencies

## How to Run
1. Clone this repo:
2. Install dependencies:
3. Run notebooks in order:
- `01_GLP1_20250530.ipynb` (data processing)
- `02_GLP1app_202506053.ipynb` (dashboard app)
4. Dashboard is also hosted at: https://engrossing-forest-cobra.anacondaapps.cloud/GLP1app_20250605

## Key Features
- Data cleaning and preprocessing
- Interactive Holoviz dashboard
- Visualizations of adverse event trends
