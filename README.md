# Scalable Music Recommendation Using PySpark

This project explores user listening behavior and builds a collaborative filtering–based recommendation system using **Apache Spark** and **PySpark**. It combines scalable ETL, behavioral analytics, and machine learning (ALS) on music interaction data, simulating real-world use cases like Spotify or Last.fm.

# Project Overview

- Cleaned and transformed raw user-artist interaction logs
- Extracted behavioral insights (top artists, peak listening hours)
- Built a personalized recommendation system using **Spark MLlib (ALS)**
- Visualized recommendation frequency and listening patterns

# Dataset
- **Source**: Modified Last.fm dataset (100K+ records)
- **Fields**:  
  - `user_id`  
  - `artist_name`, `track_name`, `album_name`  
  - `date`, `time` → combined into `timestamp`
 
# Tech Stack

| Component       | Description                           |
|----------------|---------------------------------------|
| **Apache Spark** | Distributed ETL, SQL, and ML engine    |
| **PySpark**      | Python interface to Spark              |
| **Google Colab** | Cloud notebook environment             |
| **Spark MLlib**  | ALS-based collaborative filtering      |
| **Matplotlib**   | Data visualizations  


# Behavioral Analytics

- **Peak Listening Hours**:  
  Highest activity observed between **6 PM and 10 PM**

- **Top Artists** (by activity frequency):
  Radiohead, Bon Iver, Sufjan Stevens, Metric, Madlib
  
# Key Takeaways

- Demonstrated scalable data processing with Spark
- Applied collaborative filtering for real-world personalization
- Built an end-to-end machine learning pipeline on user activity logs
- Created visual outputs for business insights and model interpretability

## Author

**Arya Mane**  
Master’s Student, Business Analytics & AI  
University of Texas at Dallas  
🔗 [LinkedIn](https://www.linkedin.com/in/aryamane20/)  

---

 *Star this repo if you found it helpful!*
