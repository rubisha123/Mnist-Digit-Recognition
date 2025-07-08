# Mnist-Digit-Recognition
This project uses two machine learning models to recognize handwritten digits from images:

1. Logistic Regression  
2. Random Forest Classifier

---

##  Files Used

- train.csv → Training data (with labels)
- test.csv  → Test data (without labels)
- digit_predictions.csv → Final predictions (from Random Forest)

---

##  Steps Performed

1. Loaded and normalized image data (28x28 pixels → 784 features)
2. Split training data into training and validation sets
3. Trained both models and compared accuracy
4. Visualized confusion matrix and sample predictions
5. Used best model (Random Forest) to predict test set digits
6. Saved predictions to CSV

---

##  Accuracy

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ~92%     |
| Random Forest      | ~96%     |

---

##  Output

Test digit images shown with predicted labels. Final results saved in `digit_predictions.csv`.

---
