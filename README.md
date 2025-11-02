# Movie Rating Predictor

A mini-project to predict movie ratings using demographic and movie metadata.

## Overview
This project predicts how users rate movies based on their information (age, gender, occupation) and movie details (release year, genre).  
It uses machine learning models to learn patterns from existing ratings and predict new ones.

### Key Steps
- Data loading and cleaning  
- Merging user, movie, and genre data  
- Feature engineering (user mean, item mean, genre encoding)  
- Model training using Linear Regression and Random Forest  
- Evaluation using Mean Squared Error (MSE)  
- Output predictions saved as `Movie_rating_predictions.csv`

###  Tools Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Jupyter Notebook  

###  Files
- `movie_rating_predictor.ipynb` — main notebook  
- Dataset files — `train.csv`, `test.csv`, `user.csv`, `item.csv`, `genre.csv`, `occupation.txt`

###  Output
The final predictions are saved in **Movie_rating_predictions.csv**.

### How to Run
1. Open the notebook in Jupyter.  
2. Run all cells sequentially.  
3. The output CSV file will be generated automatically.


