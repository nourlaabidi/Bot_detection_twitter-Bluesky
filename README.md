# Bot_detection_twitter-Bluesky

This repository contains a collection of Jupyter notebooks for experimenting with bot detection on **Twitter** and **Bluesky** data.  
The work includes data collection, preparation, feature engineering, and model building using different approaches (supervised, unsupervised, and semantic filtering).

---

## Twitter Notebooks

- **tsundoku_twitter_data.ipynb**  
  Preparation of the Twitter dataset in the same format used by Tsundoku, including **data extraction** (choosing relevant columns), **data preparation**, and **data compression** for integration with the Tsundoku toolkit.

- **IF.ipynb**  
  Feature extraction and **Isolation Forest model building** following the features used in Tsundoku. Includes **training the Isolation Forest**, **agreement score calculation**, **manual evaluation for 100 samples**, and additional training using **new features (Botometer features)**.

- **Clustering.ipynb**  
  Experiments on **unsupervised bot detection** for Twitter data, including **data preparation**, **feature building**, and clustering methods (**K-means, Agglomerative, DBSCAN**).

- **Random_forest.ipynb**  
  Construction of features for **Twitter bot detection** following Botometer’s feature sets: **user metadata, timing, content-based, sentiment, and network features**. Includes **merging features**, **training a Random Forest model**, and calculating the **agreement score and accuracy metrics**.

---

## Bluesky Notebooks

- **Bluesky_data_collection.ipynb**  
  Bluesky’s data collection using the **AT Protocol**.

- **Bluesky_data_indexing.ipynb**  
  Notebook for **indexing Bluesky data**.

- **Bluesky_data_Semantic_filetering.ipynb**  
  Notebook for **semantic filtering of Bluesky data**.

- **bluesky_data_preparation.ipynb**  
  Steps to **fetch missing information**, **count labeled posts**, and **prepare the final CSV dataset** from raw JSONL files.

- **Bluesky_data_featuring&model_Building.ipynb**  
  **Feature extraction for Bluesky users** (user metadata, timing, content, sentiment, and network features), followed by **merging features** and **training/testing models** (with and without retweets).

---

##  Project Overview

The project compares and experiments with bot detection methodologies across Twitter and Bluesky datasets. It explores:
- Traditional feature engineering (metadata, timing, content, sentiment, network).
- Supervised models such as **Random Forest** and **Isolation Forest**.
- Unsupervised approaches like **clustering**.
- Dataset preparation pipelines and **semantic filtering techniques** for relevant post selection.


## 📂 Structure

