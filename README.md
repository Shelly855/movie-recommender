# Movie Recommender (Decision Tree)

A simple **Decision Tree-based movie genre predictor** using **Scikit-learn**.  
It supports **model saving/loading, accuracy evaluation, and visualisation**.

## Project Structure
```
/movie-recommender/
│── data/
│   ├── movie.csv  # Dataset
│── notebooks/
│   ├── model_prediction.ipynb
│── models/
│   ├── movie_recommender.joblib  # Saved Decision Tree model
│── visualisations/
│   ├── movie_recommender.dot  # Graphviz visualisation file
│── README.md
├── requirements.txt  # Dependencies for the project
```

## Features
- Train a **Decision Tree Classifier**  
- Save & load model with `joblib`  
- Evaluate model accuracy with `accuracy_score()`  
- Visualise the decision tree

## How to Run
```bash
git clone https://github.com/Shelly855/movie-recommender
cd movie-recommender-python
pip install -r requirements.txt
jupyter notebook

