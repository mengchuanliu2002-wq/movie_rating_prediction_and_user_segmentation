# Movie Rating Prediction and User Segmentation

## Project Overview
This project focuses on predicting movie ratings and analyzing user behavior using machine learning techniques. The objective is to understand user preferences and identify meaningful user groups based on rating patterns.

## Dataset
The analysis is based on the MovieLens 100K dataset, which includes:
- 100,000 ratings
- 943 users
- 1,682 movies

The dataset also provides user information and movie genre data, which are used for feature construction.

## Methodology

### Rating Prediction
Two regression models are applied:
- Linear Regression as a baseline model
- Random Forest Regression to explore nonlinear relationships

### User Segmentation
K-means clustering is used to group users based on:
- Rating behavior (average rating, activity level)
- Genre preferences

All features are standardized before clustering.

## Results
The results show that Linear Regression performs better than Random Forest in this case, likely due to the simplicity of the selected features.

Three user groups are identified with different characteristics:
- Users with higher ratings and preference for Romance and Comedy
- Highly active users with interest in Action and Sci-Fi
- Less active users with stronger preference for Thriller

The clustering result shows moderate separation between groups.

## Files
- movie_rating_prediction_and_user_segmentation.ipynb: main implementation
- ml-100k/: dataset files

## How to Run
1. Download the dataset
2. Open the notebook file
3. Run all cells

## Author
Liu Mengchuan
