# Supermarket-Sales-Analysis
#  Supermarket Sales Analysis – Data Analytics Portfolio Project

## Introduction

This project explores 1,000 supermarket sales transactions collected across three branches in Myanmar.  
The objective is to analyse customer behaviour, product performance, sales trends, and satisfaction ratings in order to support business decision-making.

We applied core data analysis techniques — grouping, aggregation, visualisation, and basic machine learning — in a real-world scenario to extract actionable insights.  
The project was built using Google Colab and is fully reproducible.

🇫🇷 **Résumé en français** :  
Ce projet a été réalisé dans le cadre de mon chemin en exploration des données, et celui de mon MBA en analytique d'affaires à L'univeristé Laval.  
L'objectif ? Utiliser des méthodes simples mais efficaces pour explorer des données réelles de ventes en supermarché.  
On y parle de clients, de chiffres, de satisfaction… et un peu de prédiction ✨  
Un vrai projet fun et formateur, appliqué à un cas concret !---

##  Dataset Overview

- **Source**: Public CSV dataset
- **Transactions**: 1,000
- **Features**:  
  - `City`, `Gender`, `Customer Type`, `Product Line`, `Unit Price`, `Quantity`, `Total`, `Rating`, `Time`, `Date`, `Payment`

---

##  Tools Used

- `Python` (Jupyter Notebook / Google Colab)
- `Pandas` – data wrangling
- `Matplotlib` / `Seaborn` – data visualisation
- `Scikit-learn` – basic machine learning
- `Markdown` – presentation and business storytelling

---

##  Exploratory Data Analysis (EDA)

### ✅ Key Visual Analyses:

- **Sales by City** – Yangon had the highest revenue overall  
- **Top Product Lines** – Food and Beverages & Electronic Accessories dominated  
- **Sales by Hour** – Clear peaks at 1 PM and 7 PM  
- **Sales by Gender** – Female customers generated slightly more revenue  
- **Sales by Customer Type** – Members spent more on average  
- **Payment Methods** – (This dataset shows that most of the customers pay by cash)  
- **Satisfaction vs Total Spent** –  
  → The Pearson correlation coefficient was **-0.04**, showing **no meaningful relationship** between money spent and satisfaction rating.  
  → Customer satisfaction appears to be driven by other factors (experience, service).

---

##  Predictive Modeling

A **Linear Regression model** was trained to predict the `Total` amount spent based on:

- Gender
- Customer Type
- Product Line
- Hour of purchase

 **Root Mean Squared Error (RMSE)** = **258.34**  
This basic model provides a first step in predictive analytics and can be enhanced with more complex techniques in the future.

---

## ✅ Business Recommendations

- Focus marketing efforts on **female and member customers**
- Promote during **peak hours** (1 PM and 7 PM)
- Highlight and restock **top-selling product categories**
- Improve **overall customer satisfaction** (not only through pricing)
- Leverage insights from sales patterns to optimise resource allocation

---

##  Future Improvements

- Replace linear regression with **Random Forest or XGBoost** for improved predictions
- Apply **K-Means clustering** for customer segmentation
- Add **time series forecasting** for predicting monthly sales
- Build an **interactive dashboard** using Power BI or Tableau

---

## 👤 Author

**Mbacke Serigne Modou**  
MBA – Business Analytics at Université Laval, Canada 
Currently in an exchange program at Loughborough University, United Kingdom  
📧 smodouu01@gmail.com  
📍 Currently based in the UK 🇬🇧

---

## 💬 Feedback / Collaboration

Feel free to reach out via email or open a GitHub issue for any questions, suggestions, or collaboration opportunities.
