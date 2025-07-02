# Multiple-linear-Regression-on-housing-dataset
A practical multiple linear regression model built using Python to estimate housing prices from multiple variables. This project demonstrates data preprocessing, model training, and visualization of regression outputs.

# 🏠 Multiple Linear Regression - House Price Prediction

This project demonstrates the use of **Multiple Linear Regression** to predict house prices based on factors like square footage and number of bedrooms. It is built using Python and standard data science libraries.

---

## 📊 Dataset Overview

The dataset contains the following features:

- `Size_sqft`: The area of the house in square feet
- `Bedrooms`: Number of bedrooms in the house
- `Price`: Final price of the house (target variable)

---

## 🎯 Objective

To build a multiple linear regression model that can accurately predict the price of a house using more than one independent variable.

---

## ⚙️ Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🧠 Project Workflow

1. **Data Loading**  
   Load the dataset from CSV.

2. **Exploratory Data Analysis (EDA)**  
   - Visualize feature relationships
   - Check correlation and data distribution

3. **Model Training**  
   - Use `LinearRegression()` from `sklearn.linear_model`
   - Fit model using multiple input features

4. **Model Evaluation**  
   - Predict house prices
   - Evaluate performance using R² score and residual plots

5. **Visualization**  
   - 2D/3D regression plots for understanding model behavior

---

## 📁 Project Files
├── multiple_reg_house_dataset.ipynb # Jupyter Notebook with full code
├── real_estate_dataset.csv # Dataset file (optional)
└── README.md # This project documentation


---

## ✍️ Author

**Ankita Pawar**

---

## 📈 Result

The trained regression model provides reasonably accurate price predictions and clearly shows how different features impact house pricing in the dataset.

---

## 🚀 Future Scope

- Add more features (e.g., location, house age)
- Apply regularization techniques
- Use real-world housing datasets (like from Kaggle or open data portals)



