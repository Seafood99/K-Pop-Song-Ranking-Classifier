# 🎶 K-Pop Song Ranking Classifier

This project uses machine learning to classify the **ranking of K-Pop songs** based on the **song title and artist name**. The goal is to analyze how textual features influence chart performance.

## 📁 Dataset
The dataset `kpop_rankings.csv` contains:
- `year`: Release year
- `time`: Time period (e.g., week/month)
- `rank`: Song rank on the chart
- `song_title`: Title of the song
- `artist`: Name of the artist
- `album`: Album title

## 🧠 Models & Methods
- **TF-IDF Vectorization** to represent text numerically.
- **Random Forest Classifier** for classification.
- **Feature Selection**:
  - Mutual Information (MI)
  - Chi-Square Test (χ²)

## 📊 Results
Accuracy comparison of different feature selection methods:
- Without Feature Selection: `xx.xx%`
- With Mutual Information: `xx.xx%`
- With Chi-Square Test: `xx.xx%`

> Results are visualized using matplotlib.

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install pandas scikit-learn matplotlib
