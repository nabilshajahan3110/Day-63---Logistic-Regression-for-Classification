## Day-63---Logistic-Regression-for-Classification
As part of a 75-day data analysis challenge, this work on Python covers Logistic Regression for classification.

Logistic regression is a statistical method used for **classification problems**. Unlike linear regression, which predicts continuous outputs, logistic regression is designed to predict the probability of a categorical outcome. It is commonly used for binary classification (e.g., yes/no, 0/1, true/false), although it can be extended to multiclass classification (via techniques like one-vs-rest or multinomial logistic regression).

### Key Concepts of Logistic Regression

**Sigmoid Function:**

Logistic regression uses the sigmoid (or logistic) function to map any real-valued number into a probability range between 0 and 1.

**Decision Boundary:**

Once probabilities are obtained, a threshold (e.g., 0.5) is used to classify the output as one of the categories (e.g., class 0 or class 1).

**Log-Loss (Cost Function):**

Logistic regression minimizes the log-loss function, which measures the difference between predicted probabilities and actual class labels.

**Assumptions:**

The target variable is categorical.

Observations are independent.

There is little to no multicollinearity among the predictors.
