# ipl_player_score_prediction
This project builds a machine learning model to predict IPL batsman scores based on historical ball-by-ball data. By leveraging regression algorithms, feature engineering, and ensemble learning, the model aims to provide accurate run predictions for players under different match conditions.
📌 Project Overview
Processed 1095 JSON files containing 200,000+ ball-by-ball data points from IPL matches.
	•	Engineered 12+ statistical features, including batting average, strike rate, venue-based trends, and opposition economy rates.
	•	Evaluated Linear Regression, Random Forest, and XGBoost, achieving the best performance with:
	•	Linear Regression: R² = 0.5124, MAE = 10.344
	•	Random Forest: R² = 0.5005, MAE = 9.87 (after hyperparameter tuning)
	•	XGBoost: R² = 0.5114, MAE = 9.94 (after hyperparameter tuning)
	•	Improved model accuracy by 12% through RandomizedSearchCV-based hyperparameter tuning.
	•	Compared stacked ensemble models but found that Linear Regression outperformed them by 3% in R² score.
 📊 Technologies Used
	•	Programming: Python
	•	Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
	•	ML Models: Linear Regression, Random Forest, XGBoost
	•	Techniques: Feature Engineering, Hyperparameter Tuning, Ensemble Learning
 🚀 Future Enhancements
	•	Incorporate detailed feature engineering, including:
	•	Shot type, ball type, field placements, bowler stats, fielder stats, weather conditions, and other dynamic factors to make the model more consistent and adaptable for ensemble learning.
	•	Improve the model’s accuracy to achieve MAE below 5, ensuring higher prediction reliability.
	•	Develop a web-based card game where users collect player cards, with stats dynamically updating based on the player’s recent form.
	•	Integrate real-time match data to predict the number of runs a player is expected to score in the next match.
