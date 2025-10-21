# TV, Radio, and Newspaper Advertising Regression 📺📻📰

This project analyzes how advertising investments across **TV**, **Radio**, and **Newspaper** impact product **sales performance** using a **Multiple Linear Regression** model.

## 🎯 Objective
To determine how much sales increase when additional investment is made in each advertising channel.  
The goal is to achieve:
- **R² > 0.80**
- **RMSE < 0.10M**

## 📊 Dataset
The dataset was obtained from **Kaggle** and contains advertising spending and corresponding sales values.  
Each record includes:
- **TV** — Advertising budget for TV (in thousands of dollars)  
- **Radio** — Advertising budget for Radio  
- **Newspaper** — Advertising budget for Newspaper  
- **Sales** — Units sold (target variable)

## 🧠 Methodology
1. Imported and explored the dataset using **pandas**.  
2. Visualized feature relationships with **seaborn** and **matplotlib**.  
3. Split the data into training and test sets using **train_test_split**.  
4. Trained a **Linear Regression** model with **scikit-learn**.  
5. Evaluated performance using:
   - **R² (Coefficient of Determination)**
   - **RMSE (Root Mean Squared Error)**
6. Visualized residuals using **Yellowbrick’s ResidualsPlot**.

## 🧮 Results
- **Train R²:** 0.908  
- **Test R²:** 0.864  
✅ The model meets the target accuracy threshold.

## 🧰 Technologies Used
- Python 3.x  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn  
- yellowbrick  

## 📁 Project Structure
TVRadioNewspaper-Regression/
│
├── advertising.csv # Dataset
├── TVRadyoGazeteRegression.ipynb # Main Jupyter Notebook
├── README.md # Project description
└── LICENSE # MIT License


## 📜 License
This project is licensed under the **MIT License** – you are free to use, modify, and share it with attribution.
