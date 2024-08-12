
# Movie Recommendation System

## Project Overview
This project, **"Movie Recommendation System,"** focuses on building a recommendation system that predicts user ratings and delivers personalized movie suggestions. The project leverages collaborative and content-based filtering techniques and uses a large dataset from Kaggle, making it a comprehensive exercise in data analysis, natural language processing, and machine learning.

## Project Objectives
- **Build a Recommendation System:** Develop a system that uses collaborative and content-based filtering to recommend movies to users based on their past ratings.
- **Data Analysis:** Perform extensive data analysis to understand user behavior and movie trends.
- **Model Optimization:** Use techniques like SVD (Singular Value Decomposition) for collaborative filtering and TfidfVectorizer for content-based filtering.
- **Deploy with Flask:** Deploy the recommendation system on a web platform using Flask.

## Skills Utilized
- **Python:** For overall programming and model development.
- **Data Analysis:** Understanding and interpreting the dataset to extract valuable insights.
- **Collaborative Filtering:** Using SVD to predict user ratings based on past interactions.
- **Content-Based Filtering:** Using TfidfVectorizer to recommend movies based on movie content.
- **Data Cleaning:** Preparing the dataset by handling missing values and preprocessing text data.
- **Natural Language Processing (NLP):** Using techniques like TfidfVectorizer to process movie descriptions and tags.
- **Matplotlib/Seaborn:** For visualizing data trends and model performance.
- **Flask:** Deploying the recommendation system as a web application.

## Dataset
The dataset used for this project is the **MovieLens** dataset, enriched with additional data from IMDB. The dataset includes millions of user ratings and tags for movies, along with additional metadata like movie genres and links to IMDB and TMDB. 

### Data Source
The dataset is too large to upload directly to GitHub. You can download it from the following link:  
[MovieLens Dataset on Kaggle](https://www.kaggle.com/competitions/alx-movie-recommendation-project-2024/data)

### Data Files
- **genome_scores.csv:** Contains scores mapping the strength between movies and tag-related properties.
- **genome_tags.csv:** Provides user-assigned tags related to genome scores.
- **imdb_data.csv:** Additional movie metadata scraped from IMDB.
- **links.csv:** Provides a mapping between MovieLens ID and associated IMDB and TMDB IDs.
- **sample_submission.csv:** A sample of the submission format for the competition.
- **tags.csv:** Contains user-assigned tags for movies within the dataset.
- **test.csv:** The test split of the dataset, containing user and movie IDs without rating data.
- **train.csv:** The training split of the dataset, containing user and movie IDs with associated rating data.

## How to Use This Project
1. **Download the Dataset:**
   - Download the dataset from the Kaggle link provided above.
2. **Setup Environment:**
   - Ensure that you have Python and the necessary libraries (Pandas, Sklearn, Numpy, Flask, etc.) installed.
3. **Data Preparation:**
   - Run the data cleaning scripts to preprocess the dataset, including handling missing data and text preprocessing.
4. **Model Building:**
   - Use the provided scripts to build the collaborative filtering and content-based filtering models.
5. **Model Optimization:**
   - Apply techniques like SVD and TfidfVectorizer for model improvement.
6. **Deploy with Flask:**
   - Use Flask to deploy the model as a web application, allowing users to get personalized movie recommendations.

## Key Insights
- **User Behavior:** The analysis uncovers patterns in user preferences, which are crucial for making accurate movie recommendations.
- **Model Performance:** The combination of collaborative and content-based filtering provides a robust solution for personalized recommendations.
- **Web Deployment:** The system is successfully deployed using Flask, making it accessible via a web interface.

## Conclusion
The "Movie Recommendation System" project is a comprehensive demonstration of applying data science techniques to solve a real-world problem. By leveraging both collaborative and content-based filtering, the project delivers accurate and personalized movie recommendations to users.

