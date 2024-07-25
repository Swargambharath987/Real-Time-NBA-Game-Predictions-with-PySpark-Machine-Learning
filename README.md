# Real-Time-NBA-Game-Predictions-with-PySpark-Machine-Learning

## Project Overview
This project aims to predict the outcomes of NBA games in real-time using PySpark and machine learning techniques. By analyzing historical game performances, player statistics, and team dynamics, we developed a robust predictive model that provides actionable insights for coaches, players, sports analysts, and betting companies.

## Features
Predicts NBA game outcomes with a 72% accuracy rate.
Processes over 500,000 data points from NBA.com.
Utilizes three machine learning models: Logistic Regression, Random Forest, and Decision Tree.
Integrates real-time NBA game data for dynamic predictions.

## Data Collection
Data was extracted from the NBA.com/stats site using web scraping techniques. The dataset includes team stats, player stats, and game stats.

## Data Preprocessing
Data preprocessing involved cleaning, transforming, and normalizing the collected data. Missing values were imputed to ensure data quality. Both historical and real-time data were formatted consistently for model training and prediction.

## Model Training
Three machine learning models were trained using PySpark:
Logistic Regression
Random Forest Classifier
Decision Tree Classifier
The models were evaluated, and the best-performing model was selected for real-time predictions, achieving a 20% improvement over baseline methods.

## Real-Time Prediction
Real-time NBA game data was web scraped, preprocessed, and fed into the trained models to predict game outcomes. The system provides insights into the probable results of ongoing matches.

## Results
The model demonstrated a 72% accuracy rate in predicting NBA game outcomes, significantly enhancing decision-making for stakeholders.

## Requirements
Python 3.x,
PySpark,
Pandas,
NumPy,
request,
scikit-learn,
matplotlib

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
Bharath Kumar Swargam - LinkedIn - swargambharath987@gmail.com. 
Feel free to reach out if you have any questions or suggestions.
