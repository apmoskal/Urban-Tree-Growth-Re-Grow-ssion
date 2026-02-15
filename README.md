# Urban-Tree-Growth-Re-Grow-ssion

**Project:** Using the USDA's Urban Tree Dataset (n ≈ 14K; 17 U.S. cities), I created a model for Urban Tree Growth to study drivers of tree height and group trees into meaningful clusters by species and region.

**Purpose:** Repository for a class project exploring Urban Tree Growth. 

**Contents:**
- **Data:** `Data/TS3_Raw_tree_data.csv` — Includes required dataset downloadable from USDA: https://www.fs.usda.gov/rds/archive/catalog/RDS-2016-0005

- **Notebooks:**
	- `Notebooks/amoskal_8440_finalproject.ipynb` — Full project notebook.

- **Environment:** `requirements.txt` is included for reproducibility.

**My Role:**
  - Cleaned and engineered the USDA Forest Service Urban Tree Database (n ≈ 14K; 17 U.S. cities), including imputation, one-hot encoding, and outlier filtering.
  - Used multiple regression, PCA, and K-means clustering to study drivers of tree height and group trees into meaningful clusters by species and region.


**Notes & Assumptions**
- The notebooks expect the datasets at `Data/`.


**Attribution & License**

Thank you to USDA U.S. Department of Agriculture Research Data Archive for their dataset. 

McPherson, E. Gregory; van Doorn, Natalie S.; Peper, Paula J. 2016. Urban tree database. Fort Collins, CO: Forest Service Research Data Archive. Updated 21 January 2020. https://doi.org/10.2737/RDS-2016-0005

This data contains urban tree growth data collected over a period of 14 years (1998-2012) in 17 cities from 13 states across the United States: Arizona, California, Colorado, Florida, Hawaii, Idaho, Indiana, Minnesota, New Mexico, New York, North Carolina, Oregon, and South Carolina. 

- License: see `LICENSE` in repo root
