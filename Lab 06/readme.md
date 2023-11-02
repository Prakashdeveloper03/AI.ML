# Lab 06 Questions

### Aim:

To build and optimize Random Forest Classifier for the given test datasets using python scikit-learn package.

### Classification Datasets:

1. Car Evaluation (D1):
   - Target attribute class:
     - unacc
     - acc
     - good
     - vgood
2. Zoo (D2):
   - Target attribute class:
     - 7 classes of animals

### Exercise 1: Implement Random Forest Classifier

1. Importing Required Libraries Let's first load the required libraries.
2. **Loading Data:** Let's first load the required dataset using pandas read CSV function.
3. **Feature Selection:** Here, you need to divide given columns into two types of variables
   dependent (or target variable) and independent variable (or feature variables).
4. **Splitting Data:** To understand model performance, dividing the dataset into a training set
   and a test set is a good strategy. - Let's split the dataset by using function train_test_split(). You need to pass 3
   parameters features, target, and test_set size.
5. **Building Decision Tree Model:** Let's create a Random Forest Model using Scikit-learn.
6. **Evaluating Model:** Let's estimate, how accurately the classifier or model can predict the
   different classes.
7. Accuracy can be computed by comparing actual test set values and predicted values
