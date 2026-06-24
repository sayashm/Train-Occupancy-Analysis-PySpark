# Belgian Train Occupancy EDA with PySpark

Exploratory data analysis of passenger-reported train occupancy on the Belgian rail network, using PySpark's distributed DataFrame and RDD APIs.

**Dataset:** iRail API logs — 7,930 records spanning 2016, 2017, 2019, 2020, and 2022, covering 465 unique stations and 13 train types.

## What This Project Does

- Loads and cleans multi-year CSV data from the iRail dataset using PySpark
- Analyzes occupancy distribution (low / medium / high) across time, train type, route, and station
- Identifies commuter patterns by hour, weekday vs. weekend, and season
- Compares 2016 vs. 2019 usage trends
- Recommends low-usage stations based on boarding/alighting counts

## Key Findings

- Weekday rush hours (6–8 AM, 5–7 PM) dominate usage; weekends show flatter, afternoon-shifted patterns
- IC trains account for ~66% of all logs across both years
- Occupancy reporting shifted toward "high" in 2019 (37%) vs. 2016 (31%), despite 26% fewer total logs
- 20 stations recorded only a single trip — strong candidates for service review

## Tech Stack

- Python 3.10, PySpark 3.5
- pandas, matplotlib (for visualization)
- Google Colab (recommended runtime)

## How to Run

```bash
git clone https://github.com/sayashm/PySpark.git
cd PySpark
pip install -r requirements.txt
```

Open `SajjadAyashm_SparkLab.ipynb` in Jupyter or Google Colab. Mount your Drive and set the `base_dir` path to the folder containing the four CSV files (`json_cleaned_2016.csv`, etc.).

> **Note:** Raw data files are not included in this repo. Download the iRail dataset from Kaggle and place CSVs in the `data/` folder.

## Course Context

Big Data Tools lab — Advanced Master's in Statistical Data Analysis, Ghent University (2025)
