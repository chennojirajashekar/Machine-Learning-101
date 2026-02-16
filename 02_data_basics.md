# 2. Data: The Fuel of Machine Learning ⛽

Data is the most important part of ML. Without data, an ML model is like a car with no fuel—it won't go anywhere!

## Types of Data 📊
In the world of ML, we generally deal with two main types:

1.  **Numerical Data (Numbers):** 
    *   Examples: Age, Salary, House Price, Temperature.
2.  **Categorical Data (Labels/Categories):**
    *   Examples: Color (Red, Blue), Gender, Type of Fruit, Yes/No.

---

## The "Dirty Data" Problem 🧹
Real-world data is often messy. Imagine you are trying to solve a jigsaw puzzle, but some pieces are missing, and others are from a different puzzle!

*   **Missing Values:** Someone forgot to fill in their age on a form.
*   **Outliers:** A salary of $1,000,000 in a neighborhood where everyone earns $50,000.
*   **Inconsistent Labels:** Writing "USA," "U.S.A," and "United States" in the same column.

**Data Cleaning** is the process of fixing these issues so the model can learn better.

---

## Features vs. Labels (Layman Explanation) 🏷️
Think of a recipe:
*   **Features:** The ingredients (Flour, Sugar, Eggs).
*   **Label:** The final result (Cake).

In ML, we use **Features** to predict the **Label**.

---

## Feature Engineering 🛠️
This is like "pre-processing" your ingredients. Instead of just throwing a whole potato in the oven, you might peel it and slice it to make fries. 
In ML, we might combine "Height" and "Weight" to create a new feature called "BMI" because it's more useful for the model.

---

## 🚀 Practical Example: Predicting Exam Scores
*   **Features:** Hours spent studying, Previous grades, Sleep hours.
*   **Label:** The score in the next exam.

The model learns how each "feature" (like study hours) affects the "label" (the score).

**Next Up:** [Supervised Learning: Learning with a Teacher](./03_supervised_learning.md) (Coming Soon!)
