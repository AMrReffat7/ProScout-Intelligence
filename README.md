# ProScout-Intelligence

## Overview
A comprehensive professional scouting system integrating StatsBomb performance data with FIFA ratings to provide deep player insights, lookalike searches, and market value predictions.

## Core Features
- **Lookalike Search:** Find similar players using Cosine Similarity and Nearest Neighbors.
- **Tactical Clustering:** Group players by style and sub-roles using Hierarchical Clustering.
- **Performance Analysis:** Identify underrated/overrated players by comparing real-match stats vs. FIFA ratings.
- **Market Intelligence:** Predict market values and detect cheaper alternatives.
- **Tactical Misclassification:** Detect players whose on-pitch behavior differs from their FIFA labels.
- **Recommendation System:** Input a player name to receive a full scouting report (archetype, strengths, and similar players).

## Tech Stack
- **Data:** Pandas, NumPy
- **ML:** Scikit-learn, XGBoost
- **Clustering:** SciPy, Silhouette Analysis
- **Visualization:** UMAP, Matplotlib, Seaborn

## Quick Start
1. **Install:** `pip install pandas scikit-learn xgboost umap-learn scipy`
2. **Data:** Place `fifa_data.csv` and `statsbomb_data.csv` in the root folder.
3. **Run:** `python scouting_system.py`

## License
MIT
