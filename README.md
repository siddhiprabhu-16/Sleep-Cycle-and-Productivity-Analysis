# 💤 Sleep Cycle and Productivity Analysis  

## 📌 Overview  
This project analyzes the impact of sleep cycles on productivity, stress levels, and sleep quality. It explores key factors such as sleep duration, exercise, caffeine intake, screen time, and work hours.  

### 🔍 Key Features  
✔️ **Linear Regression** - Predicts productivity score based on sleep and lifestyle habits.  
✔️ **Logistic Regression** - Classifies sleep quality (Good/Bad) using sleep hours.  
✔️ **K-Means Clustering** - Groups individuals based on sleep patterns and stress levels.  
✔️ **Data Cleaning & Preprocessing** - Handles missing values and encodes categorical data.  
✔️ **Visualizations** - Uses Seaborn & Matplotlib for insights.  

---

## 📊 Dataset  
**Source:** [Kaggle - Sleep Cycle & Productivity](https://www.kaggle.com/datasets/adilshamim8/sleep-cycle-and-productivity)  
**Columns Used:**  
- `Total Sleep Hours`  
- `Exercise (mins/day)`  
- `Caffeine Intake (mg)`  
- `Screen Time Before Bed (mins)`  
- `Work Hours (hrs/day)`  
- `Mood Score`  
- `Productivity Score` (Target for Regression)  
- `Sleep Quality` (Target for Classification)  

---

## 🚀 Installation & Usage  
### 📥 1. Clone the repository  
```bash
git clone https://github.com/your-username/sleep-cycle-productivity.git
cd sleep-cycle-productivity

📌 Machine Learning Models
1️⃣ Linear Regression (Predict Productivity Score)
Input Features: Sleep hours, exercise, caffeine, screen time, work hours.
Evaluated using Mean Squared Error (MSE) and R² Score.
2️⃣ Logistic Regression (Classify Sleep Quality)
Converts sleep quality into a binary classification:
1 (Good Sleep: >6 hours)
0 (Poor Sleep: ≤6 hours)
Evaluated using Accuracy Score.
3️⃣ K-Means Clustering (Sleep Patterns)
Groups individuals into 3 clusters based on sleep patterns and stress levels.
Visualized using a scatter plot with centroids.
📊 Sample Visualizations
📈 Linear Regression - Predicted vs Actual Productivity Score

🔵 K-Means Clustering - Sleep Hours vs Mood Score

🔧 Tech Stack
Python 🐍
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Machine Learning: Regression, Classification, Clustering
📝 Future Improvements
✅ Explore Deep Learning for more accurate predictions.
✅ Add more health parameters (e.g., heart rate, diet).
✅ Improve sleep quality classification with additional features.

🤝 Contributing
Pull requests are welcome! If you'd like to contribute, please fork the repository and submit a PR.
