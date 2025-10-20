# 📈 E-commerce Customer Churn Prediction

A project to understand *why* customers leave and *who* might be next.

### Hi there! 👋

In e-commerce, losing a customer is easy, but winning them back is hard (and expensive!). This project is all about getting one step ahead.

I built a machine learning model that acts like an early warning system. By looking at a customer's past behavior, it can predict how likely they are to "churn" (or stop being a customer).

The goal wasn't just to get a high score; it was to give a business real, actionable insights so they can step in with the right offer *before* the customer is gone for good.

*This project was developed during my S.N. Bose Research Internship (May 2025 - Jun 2025).*

---

## 🎯 What This Project Does

* **Finds the 'At-Risk' Customers:** Uses machine learning to flag users who are showing signs of leaving.
* **Picks the Best Tool for the Job:** I didn't just pick one model. I trained and compared three different ones (Logistic Regression, Random Forest, and the champ, XGBoost) to see which one was the most accurate and reliable.
* **Answers the "Why?":** This is the cool part. I used a technique called **SHAP** to look "inside the box" and understand *why* the model thinks a customer might leave. Is it because they call support too often? Or because they haven't bought in a while? Now we know.

---

## 📊 The Results

The final model (an XGBoost classifier) was pretty good at this!

* **Accuracy:** It correctly predicted the outcome (churn or stay) **85%** of the time.
* **AUC Score:** It's **91%** (or 0.91) good at distinguishing between a churning and a non-churning customer.
* **Key Churn Drivers:** The "why" I mentioned? The top reasons for churn turned out to be:
    1.  `Tenure` (how long they've been a customer)
    2.  `TotalOrderValue` (how much they've spent)
    3.  `CustomerServiceCalls` (how many times they've needed help)

---

## 🛠️ Tech & Toolkit

* **Core:** Python
* **Data Wrangling:** Pandas & NumPy (for all the data cleaning and shaping)
* **ML Magic:** Scikit-learn (for building the models) & XGBoost (the winning model)
* **The "Why" Engine:** SHAP (for model interpretability)
* **Data Viz:** Matplotlib & Seaborn
* **Saving My Work:** Git & GitHub

---


---

## 📁 Project Structure

Here's a map of the repository so you can find your way around:
