# 🎬 Netflix Movies & TV Shows Clustering

![Netflixjpg](https://github.com/user-attachments/assets/4b93671e-672c-48f4-ad30-08fe23a0620c)

## Overview  
This project dives into Netflix's diverse collection of movies and TV shows using **unsupervised learning**. The aim is to uncover meaningful clusters based on show attributes like genre, country, duration, and description—creating insights that could support **personalized recommendations** and content strategy decisions for platforms like Netflix.

🔗 **Dataset Source**: Flixable (Third-party Netflix search engine)  
📅 **Data Year**: Up to 2019  
📁 **Total Records**: 7,787  
🧠 **Technique**: Clustering (K-Means, Hierarchical, Agglomerative, DBSCAN)  
🎓 **Project Type**: Capstone (AlmaBetter)

## Project Objective  
The goal is to explore and segment Netflix content to:

- 📊 Understand the composition of content (TV Shows vs. Movies).
- 🌍 Identify country-wise content contributions.
- 🎭 Analyze most common genres.
- 🧪 Apply NLP for text-based features like descriptions.
- 🤖 Use clustering algorithms to build content-based recommendation clusters.

## 🧾 Dataset Description

The dataset includes:

| Feature       | Description |
|---------------|-------------|
| `show_id`     | Unique identifier |
| `type`        | Movie or TV Show |
| `title`       | Title of content |
| `director`    | Director’s name |
| `cast`        | Cast members |
| `country`     | Country of origin |
| `date_added`  | Date added to Netflix |
| `release_year`| Year of release |
| `rating`      | Age rating (e.g., TV-MA, PG) |
| `duration`    | Duration or seasons |
| `listed_in`   | Genre categories |
| `description` | Summary of content |

## Project Workflow

1. **Data Inspection** & Summary  
2. **Data Cleaning** – Handling null values, dropping unneeded columns  
3. **Exploratory Data Analysis (EDA)**  
4. **Text Preprocessing** – NLP on `description`  
5. **Feature Selection**  
6. **Clustering Algorithms** – K-Means, Hierarchical, Agglomerative, DBSCAN  
7. **Find Optimal Clusters**  
8. **Conclusions & Recommendations**

## Key Findings

- 📉 Dropped `director` and `cast` columns due to heavy null values.
- 📺 69.14% content are **Movies** and 30.86% are **TV Shows**.
- 🗓️ Peak years for release:  
  - TV Shows: **2017**  
  - Movies: **2020**
- 🌍 **USA** produces the highest volume of Netflix content.
- 🏆 **Top Genres**:
  - International Movies  
  - Dramas  
  - Comedies
- 🧠 **Text Analysis** used: Stop words removal, punctuation removal, stemming, TF-IDF.
- 🤖 Best clustering achieved with **3 clusters**.
- 💡 Output clusters can help build **recommendation systems** and support **topic modeling**.

## Project Images  

![image](https://github.com/user-attachments/assets/9abc374e-e7f6-4fd4-9076-c0467301926a)

![image](https://github.com/user-attachments/assets/899afbcc-6639-4818-93d8-97b2d25b1abb)



## Tools & Libraries

- Python (Pandas, Matplotlib, Seaborn)
- NLP (NLTK, Scikit-learn)
- Machine Learning (KMeans, DBSCAN, AgglomerativeClustering)
- Jupyter Notebook

## Conclusion

Through careful analysis and clustering techniques, we segmented Netflix content into meaningful clusters. This approach allows us to build targeted recommendation systems, understand content strategy, and explore viewer preferences using unsupervised learning.
