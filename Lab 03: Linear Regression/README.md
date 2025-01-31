# 🏠 Housing Price Prediction using Linear Regression

## 📌 Overview
This project applies **Linear Regression** to predict housing prices based on given features. The dataset is analyzed using **scikit-learn**, and key metrics like **slope (β₁)** and **R² value** are evaluated to determine model performance.

**⚠️ Note:** The current results are **not efficient**, and we will update and improve the model in the next lab.

---

## 📊 Dataset Description
The dataset consists of multiple features related to housing prices in a given region. The target variable is **Price**, and the features influencing it are:

| Feature Name                    | Description |
|----------------------------------|-------------|
| `Avg. Area Income`              | Average income of residents in the area |
| `Avg. Area House Age`           | Average age of houses in the area |
| `Avg. Area Number of Rooms`     | Average number of rooms per house |
| `Avg. Area Number of Bedrooms`  | Average number of bedrooms per house |
| `Area Population`               | Population of the area |
| `Price`                         | House price (Target variable) |
| `Address`                       | Address of the house |

📌 **Sample Dataset Output:**
![Dataset Sample](img.jpg)

---

## 🚀 Implementation Steps

### **1. Load Data**  
```python
import pandas as pd
data = pd.read_csv("housing.csv")
print(data.head())

```

### **2. Train-Test Split**  
```python
from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
```

### **3. Train the Model**  
```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(X_train, y_train)
```

### **4. Evaluate the Model**  
```python
r2 = model.score(X_test, y_test)
print(f"Model R² Score: {r2:.4f}")
```
📌 **Current R² Score is low, indicating the model needs improvement.**  
✅ We will enhance this model in the **next lab** to achieve better accuracy.

---

## 📈 Results and Visualizations  

### **1. Regression Line Plot**  
📌 This plot shows the **linear regression model fitted** to the dataset.  
- **Blue dots** represent actual housing prices.  
- **Red line** represents the predicted price trend using linear regression.  
- A weak correlation suggests that a better model or feature selection is needed.  

![Regression Line](image1.png)

---

### **2. Residuals Distribution**  
📌 Residuals represent the difference between actual and predicted values.  
- A **normal distribution** of residuals is preferred for a good regression model.  
- The plot indicates that **our model needs improvement**, as residuals are not centered well around zero.  

![Residuals Plot](image2.png)

---

## 📌 How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo-name.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook Lab_03.ipynb
   ```

📢 **Next Steps:**  
🔹 Improve feature selection  
🔹 Try polynomial regression for better fitting  
🔹 Optimize hyperparameters  

---

## 📚 References & Documentation  
- **Pandas:** [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)  
- **Scikit-Learn (Linear Regression):** [https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)  
- **Matplotlib (Plotting Library):** [https://matplotlib.org/stable/contents.html](https://matplotlib.org/stable/contents.html)  

---
