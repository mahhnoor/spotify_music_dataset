# spotify_music_dataset

# 🎶 Spotify Audio Features Analysis and Modeling

### Goal: **Exploration and Prediction** using the Spotify Track Dataset

This project performs an end-to-end data science analysis focusing on Spotify tracks. We use various audio features (e.g., Danceability, Energy, and Valence) to understand musical trends, group similar songs, and build a model to predict a track's success or classify its characteristics.

---

## 💻 1. Project Workflow

This project utilized a full data science pipeline:

* **Data Acquisition & Cleaning:** Initial assessment of track metadata and handling of features like `key`, `mode`, and categorical text data (e.g., `genre`).
* **Exploratory Data Analysis (EDA):** Visualizing the distribution of key audio features and their correlation with overall track popularity.
* **Feature Scaling/Preprocessing:** Preparation of numerical features for clustering and modeling.
* **Clustering / Modeling:** Applying unsupervised learning (e.g., K-Means) to group songs by mood, or supervised learning (e.g., classification/regression) to predict success.

---

## 📊 2. Key Analytical Insights

* **Feature Impact:** Analyzed how `Liveness` and `Acousticness` correlate with track `Popularity`.
* **Genre Trends:** Visualized differences in average `Danceability` and `Energy` across major music genres.
* **Clustering:** Used unsupervised learning to successfully group tracks into 3-5 distinct 'mood clusters' (e.g., High Energy Dance vs. Low Valence Acoustic).

---

## 🛠️ 4. Technologies Used

* **Python 3.x**
* **Pandas & NumPy:** Data cleaning and numerical manipulation.
* **Seaborn & Matplotlib:** Data visualization for feature distribution and correlation.
* **Scikit-learn:** Feature scaling, clustering (K-Means), and supervised machine learning models.

---

## 🚀 5. How to Replicate

1.  **Clone the Repository:**
    ```bash
    git clone [Your-Repo-Link-Here]
    ```
2.  **Run the Notebook:** All code is contained within the `spotify_analysis.ipynb` file.
