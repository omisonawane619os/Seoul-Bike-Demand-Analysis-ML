# 🚲 Seoul Bike Demand Analysis using Bigdata tools

This project performs an **end-to-end machine learning analysis** on the **Seoul Bike Sharing dataset**.  
It combines **Exploratory Data Analysis (EDA)**, **Unsupervised Learning (Clustering)**, and **Supervised Learning (Classification)** to understand and predict bike rental demand patterns.

The project is designed for **academic assessment**, **data science portfolios**, and **real-world urban mobility analysis**.

---

## 📊 Project Objectives

- Analyze bike rental demand patterns in Seoul
- Identify **rush hours** using clustering
- Classify demand into **Low, Medium, High**
- Compare multiple classification algorithms
- Optimize model performance using **Grid Search**

---

## 🧠 Machine Learning Techniques Used

### 🔹 Unsupervised Learning
- **K-Means Clustering**
- Silhouette Score evaluation

### 🔹 Supervised Learning (Classification)
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting Classifier

### 🔹 Model Optimization
- GridSearchCV (Random Forest tuning)

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Google Colab compatible**

---

## 📂 Dataset

**File:** `SeoulBikeData.csv`  
**Source:** UCI Machine Learning Repository  

### Key Features:
- Temperature
- Humidity
- Wind Speed
- Rainfall & Snowfall
- Seasons
- Holiday
- Functioning Day
- Hour of Day

### Target Variables:
- **Rented_Bike_Count** (Regression / Clustering)
- **Demand_Level** (Classification)

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Feature Engineering
- Date parsing
- Temporal feature extraction
- Weekend detection

### 2️⃣ Exploratory Data Analysis (EDA)
- Demand distribution
- Hourly demand patterns
- Seasonal analysis
- Correlation heatmap
- Temperature vs rentals

### 3️⃣ Clustering Analysis
- K-Means clustering on:
  - Hour
  - Rented Bike Count
- Identification of low, medium, and high demand periods

### 4️⃣ Demand Classification
- Demand categories:
  - Low (0–300)
  - Medium (301–1000)
  - High (1000+)
- 80/20 train-test split
- Stratified sampling

### 5️⃣ Model Evaluation
- Accuracy comparison
- Classification reports

### 6️⃣ Hyperparameter Tuning
- GridSearchCV on Random Forest
- Cross-validation for robustness

---

## 📈 Evaluation Metrics

- Accuracy Score
- Silhouette Score (Clustering)
- Cross-validation Score

---

## ▶️ How to Run (Google Colab)

1. Open **Google Colab**
2. Upload the notebook or Python script
3. Upload `SeoulBikeData.csv` when prompted
4. Run cells sequentially

---

## 📊 Outputs Generated

- EDA plots (PNG files)
- Cluster visualization
- Model accuracy comparison
- Best model parameters

---

## 🧪 Use Cases

- Urban transportation planning
- Smart city analytics
- Demand forecasting
- Mobility optimization

---

## 🔮 Future Improvements

- Time-series forecasting (LSTM, ARIMA)
- Regression-based demand prediction
- Real-time data integration
- Deployment as a web dashboard

---

## 👨‍💻 Author

**Your Name**  
Data Science | Machine Learning | Urban Analytics

---

## 📜 License

This project is licensed under the **MIT License**.
