🏏 Cricket Player Performance Prediction
This project predicts the performance of cricket players (batsmen and bowlers) using machine learning models like Decision Tree and LightGBM. It processes player stats and match-related features to forecast player output, helping with strategy, selection, and game analysis.
📂 Project Structure

├── data/

│   ├── batsman.csv                             # Batsman statistics dataset

│   ├── bowler.csv                              # Bowler statistics dataset

│   └── X_predict.csv                           # Sample input for making predictions

├── models/

│   └── README.md                               # Info on training models

├── notebooks/

│   └── code_playerrunspred.ipynb               # Model training and prediction notebook

├── presentations/

│   └── Cricket-Player-Performance-1.pptx       # Project presentation

└── README.md


🧠 How It Works

- Data Preprocessing: Cleans and merges batsman and bowler data.
- Feature Engineering: Extracts relevant features for prediction.
- Model Training: Trains ML models using Decision Tree and LightGBM.
- Prediction: Predicts future performance of players using test data.

🏋️‍♂️ How to Train the Model

1. Open the notebook notebooks/code_playerrunspred.ipynb.
2. Run all cells to:
   - Load data
   - Train models
   - Evaluate performance
3. Save trained models (optional):

import joblib
joblib.dump(model, 'model_name.pkl')
Alternatively, you can modify the notebook to experiment with different ML models or hyperparameters.

📈 Accuracy & Results

- Decision Tree Accuracy: ~91% on training set  
- LightGBM Accuracy: ~95% on training set  
- Predictions are based on structured input like past performance, opposition, match conditions, etc.

🔍 How to Make Predictions

1. Prepare a dataset similar to data/X_predict.csv.
2. Load your trained model (or use one from the notebook).
3. Use the model to predict:

prediction = model.predict(new_data)
print(prediction)

🗂️ Dataset Source & Disclaimer

- The datasets were compiled manually for academic purposes.  
- This project is intended for educational and demonstrative use only.  
- Predictions are not to be used for betting or commercial decisions.

📌 Authors

Shravan,

Srikanth,

Vijayalakshmi,

Mohammad Shafee ur Rahaman --->
LinkedIn: https://www.linkedin.com/in/mohammad-shafee05/
