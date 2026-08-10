# Coursera IBM Machine Learning Capstone

## Personalized Online Course Recommender System

This project focuses on building a personalized online course recommendation system using machine learning. The project analyzes course and user enrollment data and explores different recommendation approaches to recommend relevant courses to learners.

## Project Objectives

- Analyze course and user enrollment data.
- Explore course genres, enrollment patterns, and course popularity.
- Build content-based recommender systems.
- Develop a clustering-based recommender system.
- Implement collaborative filtering approaches.
- Compare the performance of collaborative filtering models using RMSE.

## Project Workflow

The project consists of the following major stages:

1. **Exploratory Data Analysis**
   - Course distribution by genre
   - Course enrollment distribution
   - Most popular courses
   - Course-title word analysis

2. **Content-Based Recommendation**
   - User profile-based recommendations
   - Course similarity-based recommendations
   - Clustering-based recommendations

3. **Collaborative Filtering**
   - KNN-based collaborative filtering
   - NMF-based collaborative filtering
   - Neural Network Embedding-based recommendation

4. **Model Evaluation**
   - Evaluation of recommendation results
   - RMSE-based comparison of collaborative filtering models

## Notebooks

| Notebook | Description |
|---|---|
| `eda.ipynb` | Exploratory Data Analysis |
| `content_user_profile.ipynb` | User Profile-Based Recommender |
| `content_course_similarity.ipynb` | Course Similarity-Based Recommender |
| `content_clustering.ipynb` | Clustering-Based Recommender |
| `knn.ipynb` | KNN-Based Collaborative Filtering |
| `nmf.ipynb` | NMF-Based Collaborative Filtering |
| `neural_network_embedding.ipynb` | Neural Network Embedding-Based Recommender |

## Model Performance

The collaborative filtering models were evaluated using Root Mean Square Error (RMSE).

| Model | RMSE |
|---|---:|
| KNN | 1.2886 |
| NMF | 1.3040 |
| Neural Network Embedding | 0.4832 |

The Neural Network Embedding model achieved the lowest RMSE among the evaluated collaborative filtering models.

## Project Presentation

The final project presentation/report is included in this repository.

## Tools and Technologies

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Machine Learning

## Author

**Ariyan Adak**

Machine Learning Capstone Project  
Coursera — IBM Machine Learning
