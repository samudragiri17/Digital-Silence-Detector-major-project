
# 🧠 Digital Silence Detector – Predict the Best Time to Focus

## 🔍 Problem Statement
This project aims to predict a user's focus rating based on environmental and behavioral factors like screen time, app switching, ambient noise, and notifications. It helps in identifying ideal focus hours throughout the day.

## 📊 Features Used
- Hour of Day (0–23)
- Number of Notifications (per hour)
- Screen Time (minutes)
- Ambient Noise (in dB)
- Number of App Switches

## 🎯 Target
- Focus Rating (0 to 1)

## 🧠 Models Used
- Linear Regression ✅ (Best Model)
- Decision Tree Regressor
- Random Forest Regressor (with GridSearchCV tuning)

## 🧪 Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

## 📈 Visualizations
- Correlation Heatmap
- Line Plot of Focus vs Hour
- Scatter Plot of Noise vs Focus
- Feature Importances

## 📦 Output Files
- `focus_predictor_model.pkl`: Final saved ML model
- `cleaned_data.csv`: Processed dataset after cleaning
- `focus_analysis.ipynb`: Full code notebook with preprocessing, training, visualization

## 💡 Sample Predictions
| Hour | Noise | Notifications | Predicted Focus |
|------|-------|----------------|------------------|
| 14   | 35    | 10             | 0.82             |
| 18   | 50    | 20             | 0.55             |

## 🚀 How to Run
1. Clone this repo
2. Install required libraries (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `joblib`)
3. Run `focus_analysis.ipynb` in Jupyter Notebook or Google Colab

## 🙌 Contribution
Feel free to fork and improve. PRs are welcome!
