# Movie Recommendation System

This project has implemented Four different types of Recommendation System on **100K movie ratings dataset**.

## **Overview**

The notebook explores and builds four different recommendation engines, each employing distinct methodologies:

### **Simple Recommendation System**
- Generates top movie charts based on **IMDB vote count** and **vote averages**.  
- Utilizes the **IMDB Weighted Rating System** for more accurate rankings.  
- Provides general recommendations and genre-specific suggestions.

### **Content Based Recommendation System**
- Two separate models were developed:  
  - First model based on **movie overviews and taglines**.  
  - Second model based on **metadata** such as **cast, crew, genres, and keywords**.  
- A filtering mechanism prioritizes movies with higher votes and ratings.

### **Collaborative Filtering Based Recommendation System**
- Built using the **Surprise Library** and **Singular Value Decomposition (SVD)**.  
- Predicts user-specific movie ratings with an **RMSE of less than 1**.  
- Provides estimated ratings for any user-movie combination.  

### **4. Hybrid Recommendation Engine**  
- Combines **content-based filtering** and **collaborative filtering** techniques.  
- Suggests movies to a specific user by utilizing internally predicted ratings.  

## **Dataset**  
The dataset used for this project can be found here:  
[The Movies Dataset - Kaggle](https://www.kaggle.com/rounakbanik/the-movies-dataset)

## Steps to Run the Projects.

1. Clone the Repository:
git clone https://github.com/YashSitapara/Movie_Recommendation_System.git

2. cd Movie_Recommendation_System

3. Create and activate virtual environment (Optional BUT recommended)

4. Install all Dependencies: pip install -r requirements.txt

5. Open any code editor and Run the cells step by step.
