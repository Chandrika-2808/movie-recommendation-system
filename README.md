# Movie Recommendation Demo

This repository scaffolds a simple movie recommendation system using the MovieLens dataset.

Quick start:

1. Create a virtual environment and install dependencies:

```bash
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
```

2. Run the demo (downloads MovieLens small dataset and prints recommendations):

```bash
python app/run_demo.py
```

Files added:
- `data/download_movielens.py`: downloads and extracts MovieLens (ml-latest-small).
- `src/recommender.py`: core recommenders (popularity, item-based CF, content-based).
- `app/run_demo.py`: small runnable demo.

Next steps: integrate recommendations into `movierecommendation.ipynb` or build a web UI.
