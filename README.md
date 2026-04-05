# Movie Rating Prediction and User Segmentation

## 📌 Project Overview
This project focuses on movie rating prediction and audience segmentation using machine learning techniques. The goal is to analyze user rating behavior and identify meaningful user groups.

## 📊 Dataset
The project uses the MovieLens 100K dataset, which contains:
- 100,000 ratings
- 943 users
- 1,682 movies

## ⚙️ Methods
### Regression (Rating Prediction)
- Linear Regression (baseline)
- Random Forest Regression

### Clustering (User Segmentation)
- K-means clustering
- Features: user behavior + genre preferences

## 📈 Results
- Linear Regression performs better than Random Forest due to the linear nature of selected features
- Three user clusters were identified with different activity levels and genre preferences
- Clustering shows moderate separation (Silhouette Score ≈ 0.11)

## 🧠 Key Insights
- User preferences are complex and not easily separable
- Simple features can capture basic patterns but have limitations
- Genre preference plays an important role in user segmentation

## 💻 Files
- `movie_rating_prediction_and_user_segmentation.ipynb`: main code
- `ml-100k/`: dataset

## 🚀 How to Run
1. Download the dataset
2. Open the notebook
3. Run all cells

## 🔗 Author
- Liu Mengchuan
