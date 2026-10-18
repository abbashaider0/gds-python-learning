# Geospatial Data Science — Python Learning

This is the Phase 0 / Phase 1 repository for Abbas Haider's Geospatial Data Science (GDS) Python learning plan at the University of Waterloo.

The progression is core Python → pandas → GeoPandas → Rasterio.

## Phases

- **Phase 0 — Setup.** Python environment and this first GitHub repo.
- **Phase 1 — Core Python + Pandas.** Language basics and tabular data.
- **Phase 2 — GeoPandas.** Vector data with open Canadian and local datasets.
- **Phase 3 — Raster + small project.** Rasterio, then a short end-to-end project.

## Repo layout

- `notebooks/` — Jupyter notebooks
- `data/` — datasets used by the notebooks
- `requirements.txt` — packages for the learning environment

## Setup

```bash
git clone https://github.com/abbashaider0/gds-python-learning.git
cd gds-python-learning
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

On Windows, activate the environment with `.venv\Scripts\activate`.

## Learning resources

- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
- [Python for Everybody](https://www.py4e.com/)
- [pandas Getting Started](https://pandas.pydata.org/docs/getting_started/index.html) and [10 minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
- [Real Python pandas tutorials](https://realpython.com/learning-paths/pandas-data-science/)
- [GeoPandas user guide](https://geopandas.org/en/stable/docs/user_guide.html)
- [Real Python: GeoPandas Basics](https://realpython.com/geopandas/)
- [Rasterio documentation](https://rasterio.readthedocs.io/)
