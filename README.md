# bogota-motorcyclists-2019-2024
# Bogotá Motorcyclists 2019–2024 (ANSV + SaluData)

Reproducible code for descriptive analyses and figures used in the manuscript *“Risk, Bias, and Belonging: Explaining Bogotá’s Motorcyclist Fatalities with a Cognitive Bias Index (2019–2024)”*.

## Data
Public sources (links cited in the article):
- ANSV (Colombia) – National Road Safety Agency  
- SaluData (Bogotá) – Health Observatory

> ⚠️ No data files are stored here. Place downloads locally under `data/raw/`.

## How to run
```bash
conda env create -f environment.yml   # or: pip install -r requirements.txt
python analysis/01_cleaning.py
python analysis/02_cbi_construct.py
python analysis/03_figures.py
