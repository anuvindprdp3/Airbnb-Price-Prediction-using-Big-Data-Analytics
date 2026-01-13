# Airbnb-Price-Prediction-using-Big-Data-Analytics
This project explores Airbnb listing data using Big Data analytics and machine learning to understand and predict rental pricing behavior across different cities. The goal was to build scalable machine learning models using Apache Spark on Databricks, evaluate their performance, and interpret results from a business perspective



I worked on an Airbnb data analytics project using **Databricks and Apache Spark**, where I built machine learning models to **predict Airbnb listing prices** and analyze how model performance varies across different cities. The project focused on applying **regression-based machine learning techniques** on large datasets and interpreting results using standard evaluation metrics.

Using Airbnb listing data from **Barossa Valley (Australia)** and **Berlin (Germany)**, I developed both **univariate and multivariate linear regression models** with Spark MLlib. I evaluated model performance using **RMSE and R²** to compare accuracy and explanatory power across regions. The results showed that models trained on one city do not generalize well to another, highlighting the importance of **region-specific modeling** for pricing strategies.

As part of exploratory analysis, I also experimented with **logistic regression and clustering** as a bonus exercise to further understand the dataset and machine learning capabilities in a big data environment. Overall, the project strengthened my understanding of **big data processing, regression modeling, and business interpretation of predictive analytics results**.




## 🛠 Tools & Technologies

* **Databricks**
* **Apache Spark (MLlib)**
* **PySpark**
* **Big Data Analytics**
* **Machine Learning (Regression Models)**
* **Data Visualization**

---

## 📌 Project Overview

This project explores Airbnb listing data using **Big Data analytics and machine learning** to understand and predict rental pricing behavior across different cities. The goal was to build scalable machine learning models using **Apache Spark on Databricks**, evaluate their performance, and interpret results from a business perspective.

The project emphasizes:

* Distributed data processing
* Regression modeling
* Cross-city model evaluation
* Business-driven interpretation of predictive metrics

---

## 📊 Dataset Description

The dataset consists of Airbnb property listings containing features such as:

* Property location
* Listing characteristics
* Amenities
* Number of rooms
* Customer reviews
* Rental price

Two cities were selected to compare model performance across regions:

* **Barossa Valley, South Australia, Australia**
* **Berlin, Germany**

---

## 🔄 Project Workflow

### 1️⃣ Data Exploration & Preparation

* Loaded large Airbnb datasets into **Databricks**
* Performed exploratory data analysis using Spark’s `display()` function
* Visualized feature distributions and relationships
* Split the data into **training and testing datasets**

---

### 2️⃣ Regression Modeling with Spark MLlib

* Built a **univariate linear regression model** using one selected feature
* Developed a **full multivariate regression model** using multiple predictors
* Used **Apache Spark MLlib** for scalable model training

---

### 3️⃣ Model Evaluation

Model performance was evaluated using:

* **RMSE (Root Mean Squared Error)** – to measure prediction error
* **R² (Coefficient of Determination)** – to measure how well the model explains price variance

These metrics were used to compare:

* Univariate vs multivariate models
* Performance across different cities

---

### 4️⃣ Cross-City Model Comparison

* Tested models trained on **Barossa Valley data** against **Berlin data**
* Observed a significant drop in predictive performance
* Demonstrated that pricing models are **highly region-dependent**

---

### 5️⃣ Bonus Machine Learning Exploration

* Experimented with **logistic regression and clustering**
* Used these models for exploratory understanding rather than primary prediction
* Gained additional exposure to Spark MLlib’s machine learning capabilities

---

## 📈 Key Results & Insights

* The **Barossa Valley model** achieved lower RMSE and higher R² than Berlin
* Applying a model trained on one city to another resulted in reduced accuracy
* Local market characteristics strongly influence Airbnb pricing
* Models should be **trained and tuned per region** for reliable business use

---

## 💡 Business Interpretation

* The regression models can support **pricing strategy optimization**
* Hosts and investors can estimate rental value more accurately within a specific city
* Cross-region model reuse without retraining can lead to misleading insights
* Region-specific modeling improves decision-making and forecasting reliability

---
Screenshots
The first city I have chosen is:
Barossa Valley, South Australia, Australia

S1. A plot of variables using the display() command in data bricks.
 <img width="975" height="475" alt="image" src="https://github.com/user-attachments/assets/655c2386-efe6-4957-b641-ff6081c66339" />
<img width="975" height="475" alt="image" src="https://github.com/user-attachments/assets/9cc1c64b-2319-4252-b7fa-67cfd0a4643f" />
<img width="974" height="424" alt="image" src="https://github.com/user-attachments/assets/4b5d7b55-f12d-45f7-90d9-f24874914aa9" />

 
S2. An output statement about the split dataset into training and test data.
 <img width="975" height="358" alt="image" src="https://github.com/user-attachments/assets/4712aa07-8852-459b-9459-ba414563c033" />

S3. A univariate regression model with one feature changed from the provided example.
 <img width="975" height="429" alt="image" src="https://github.com/user-attachments/assets/0205d6d9-0218-4fc5-8c84-c2260093b425" />
<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/561f72fa-49c2-43b8-acb3-078571b90049" />

 
S4. A linear regression line print out showing your variable selection for the univariate model.
 <img width="975" height="435" alt="image" src="https://github.com/user-attachments/assets/d3ccd5a9-52b7-4d01-8ca2-f8d89aa3a112" />

 <img width="973" height="372" alt="image" src="https://github.com/user-attachments/assets/844a31a8-12fd-461c-aa68-897f1166332c" />

S5. A printout of RMSE and R^2 values for your univariate model.
 
 <img width="975" height="532" alt="image" src="https://github.com/user-attachments/assets/aeffb853-6cdc-45bd-9acb-69d3315f0b08" />
<img width="975" height="560" alt="image" src="https://github.com/user-attachments/assets/0d9fb788-d026-4891-8bd5-f3914e3e1e98" />

 
S6. A printout of RMSE and R^2 values for the full model.
 
 <img width="975" height="420" alt="image" src="https://github.com/user-attachments/assets/f8d4d1d5-c9e4-41cf-91f8-658abc15ebdb" />
 <img width="975" height="588" alt="image" src="https://github.com/user-attachments/assets/d15d10d3-4513-458b-a7db-f6ec11ec6f0b" />


S7. Bonus: An output of a logistic regression or clustering on the dataset.
 <img width="975" height="541" alt="image" src="https://github.com/user-attachments/assets/025033b0-c7f2-4270-8eb9-ebac02c3cbc9" />

 <img width="975" height="595" alt="image" src="https://github.com/user-attachments/assets/51161933-df09-4638-89c6-c6d8fa950c32" />
<img width="975" height="602" alt="image" src="https://github.com/user-attachments/assets/4abdd8af-d57a-41b5-801b-342119e70769" />



S8. Bonus: A printout of RMSE and R^2 values for the model tested out on data from another city.
The second city I have chosen is:
Berlin, Berlin, Germany

 
 <img width="975" height="559" alt="image" src="https://github.com/user-attachments/assets/52ca0d1a-f943-439e-915e-368588544861" />
<img width="975" height="528" alt="image" src="https://github.com/user-attachments/assets/7cfa6a16-4b48-44d0-9e68-507643144d9b" />

 <img width="975" height="657" alt="image" src="https://github.com/user-attachments/assets/92c34c82-9e3b-48d2-a95c-c7c9b359df2b" />

 <img width="975" height="603" alt="image" src="https://github.com/user-attachments/assets/d65d40b5-0798-4035-b500-2b7324f40cc4" />



## 🎯 Key Learnings

* Hands-on experience with **Big Data machine learning pipelines**
* Practical understanding of **regression evaluation metrics**
* Importance of **data locality and regional patterns**
* Translating ML outputs into **business-relevant insights**

