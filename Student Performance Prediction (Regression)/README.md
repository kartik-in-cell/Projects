
# 🎓 Student Performance Prediction (Regression)

This project aims to predict students' final exam scores based on various features such as study hours, parental education, and attendance using **Linear Regression**.

---

## 📌 Objective
To build a regression model that accurately predicts student performance and provides insights into key factors affecting exam scores.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning model and metrics

---

## 📁 Dataset
The dataset (`student_scores.csv`) includes:
- `Study Hours`: Number of hours a student studies per day.
- `Parental Education`: Encoded level of parental education (1: No High School, 5: Master's degree).
- `Attendance`: Attendance percentage.
- `Final Score`: Target variable – student's exam score.

---

## 🔍 Steps Performed

1. **Data Exploration**
   - Checked correlations between features and target.
   - Visualized relationships using pairplots and heatmaps.

2. **Data Preparation**
   - Selected features and target.
   - Split data into training and testing sets (80/20).

3. **Model Building**
   - Applied **Linear Regression** using Scikit-learn.
   - Trained the model on training data.

4. **Model Evaluation**
   - Evaluated using **Mean Absolute Error (MAE)** and **R² Score**.
   - Plotted actual vs predicted scores.

---

## 📈 Results
- **MAE**: On average how many marks the model is off by.
- **R² Score**: Proportion of variance explained by the model.

Higher R² and lower MAE indicate better model performance.

---

## 📊 Example Visualization
![Actual vs Predicted](https://via.placeholder.com/400x200?text=Actual+vs+Predicted+Scatter+Plot)

---

## 🤔 Interview Questions You Might Face

1. **Why did you choose Linear Regression?**
   > It's simple, interpretable, and well-suited for predicting continuous outcomes like scores.

2. **What are MAE and R² Score?**
   > MAE measures average prediction error, R² shows how well the model explains the data variance.

3. **What improvements can be made?**
   > Add more features (test anxiety, sleep hours), use Regularization (Ridge/Lasso), try advanced models (Random Forest, XGBoost).

---

## ✅ Conclusion
This project demonstrates how basic regression models can be used to predict real-world outcomes, and how to evaluate them effectively.

---

Feel free to contribute or fork this project!
