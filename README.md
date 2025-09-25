# Dog vs Cat Classifier 🐶🐱

A simple Python project that classifies **dogs and cats** based on two features:

- **Whisker Length**  
- **Ear Flappiness Index**

The project uses a **random linear classifier** to separate the two classes and demonstrates training, testing, and prediction on unseen data.

---

## Features

- Random linear classifier for binary classification  
- Train/Test split for model validation  
- Predict labels for new/unseen data points  
- Compute accuracy on the test set  
- Simple scatter plot visualization with decision boundary  

---

## How It Works

1. Generate synthetic data for dogs and cats.  
2. Split the data into **training (80%)** and **testing (20%)** sets.  
3. Train a **random linear classifier** by selecting the linear boundary with the lowest error.  
4. Test the model on unseen data and compute classification accuracy.  
5. Visualize the results with a scatter plot and decision boundary.

---

## Accuracy

- Accuracy is calculated as:

```python
accuracy = (len(y_test) - test_error) / len(y_test) * 100
print(f"Test Accuracy: {accuracy:.2f}%")


#Note: Accuracy may vary slightly due to the random nature of the classifier.


A beginner-friendly project for understanding linear classification and data visualization in Python.
