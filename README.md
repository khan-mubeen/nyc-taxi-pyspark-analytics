# NYC Taxi Trips — Big Data Analytics with PySpark

A big data processing and machine learning project built on the NYC Yellow Cab Trips 2019 dataset (~84.5M records, ~11.6 GB), developed as part of the Big Data Processing and Analytics course at the University of Oulu.

## Project Goals

- Predict fare amounts and trip durations using regression models
- Classify high-demand zones and time windows
- Demonstrate scalable data processing entirely within the PySpark ecosystem

## Dataset

- **Source:** [NYC Yellow Cab Trips 2019 - Kaggle](https://www.kaggle.com/datasets/dhruvildave/new-york-city-taxi-trips-2019)
- **Size:** ~84.5 million records, ~11.6 GB
- **Note:** Raw data is not stored in this repository. Processing runs on the University of Oulu CSC computing environment.

## Tech Stack

- Python 3
- Apache Spark / PySpark
- Spark MLlib
- Jupyter Notebooks
- CSC Puhti / Mahti (University HPC environment)

## Team

| Name | GitHub |
|------|--------|
| Mubeen Khan | [@mubeen](https://github.com/khan-mubeen) |
| Vu Truong | [@harry](https://github.com/HarryxDD) |
| Eshmam Rayed | [@eshmam](https://github.com/Rayed1) |

## Project Structure
```
src/           core pyspark scripts
notebooks/     exploration and prototyping
reports/       results and visualizations
data/          placeholder — data lives on CSC
```

---

**.gitignore essentials to add:**
```
*.csv
*.parquet
*.json
__pycache__/
.ipynb_checkpoints/
*.egg-info/
.env