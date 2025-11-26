
## 🔍 Logistic Regression — Overview

**Logistic Regression** is a widely used supervised machine learning algorithm for **binary classification** problems—where the goal is to predict one of two possible outcomes, such as *survived vs. not survived*, *spam vs. not spam*, or *disease vs. no disease*.

Unlike linear regression, which predicts continuous values, logistic regression predicts **probabilities**. It uses a mathematical function called the **sigmoid function** to convert a linear combination of inputs into a value between **0 and 1**, representing the probability of belonging to the positive class.

The model then assigns a class label based on a threshold (typically 0.5):

* If probability ≥ 0.5 → **Class 1**
* If probability < 0.5 → **Class 0**

---

## ⚙️ Key Concepts

* **Sigmoid Activation:**
  Converts the output into a probability value.

* **Decision Boundary:**
  A line or curve that separates data points into two classes based on learned weights.

* **Cost Function (Log Loss):**
  Measures how far the predictions are from actual values. Logistic regression tries to minimize this.

* **Optimization (Gradient Descent):**
  Adjusts model weights iteratively to improve accuracy.

---

## 🧠 Why Use Logistic Regression?

* Simple, fast, and efficient
* Works well for linearly separable data
* Easy to interpret and explain
* Performs well as a baseline model
* Widely used in real-world systems like fraud detection, medical diagnosis, and risk assessment

---

## 📌 Example Use-Case: Titanic Survival Prediction

In this project, Logistic Regression is used to predict whether a passenger survived based on attributes like:

* Age
* Gender
* Passenger class
* Number of siblings/spouses
* Fare
* Embarked location

The model learns patterns from the training data and predicts survival probabilities for unseen passengers.
