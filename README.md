# 🏡 House Price Prediction using Gradient Descent

A simple and educational implementation of **Linear Regression** using **Gradient Descent** from scratch with **NumPy** to predict house prices based on cleaned housing data. Ideal for learning machine learning fundamentals without using black-box models.

---

## 📦 Features

✅ Load dataset from Excel  
✅ Handle missing values  
✅ Normalize features and target using `StandardScaler`  
✅ Train using batch gradient descent  
✅ Evaluate using Mean Squared Error (MSE)  
✅ Visualize training loss

---

## 📁 Dataset

Ensure you have a file named:

Cleaned\_HousePricePrediction.xlsx

````

With:
- A sheet named Sheet1
- A SalePrice column (target variable)
- An Id column (will be dropped)
- All other columns should be numerical features

---

## 🚀 Getting Started

### 1️⃣ Install Dependencies

Bash

pip install pandas numpy scikit-learn matplotlib openpyxl
````

### 2️⃣ Run the Script

```bash
python your_script_name.py

---

## 📊 Example Output

txt

MSE: 145237600.25

📈 Training loss plot (MSE per iteration):

![Gradient Descent Plot](example_plot.png)

---

## ⚙️ Hyperparameters

You can tune the following parameters in the script:

Python

learning_rate = 0.01       # Step size for gradient descent
n_iterations = 1000        # Number of training iterations

---

## 📌 Notes

* This is a manual implementation of linear regression; no sklearn.linear_model used.
* Both features and target variable are standardized using StandardScaler.
* Ideal for educational purposes and understanding the core of gradient-based optimization.

---

## 📃 License

MIT License © 2025
Feel free to use and modify it for personal or academic use.

---

## 🙌 Contributions

Pull requests are welcome! If you'd like to improve performance, add visualization, or support other regression methods, feel free to contribute.

