# Lab 04 Questions

### Aim:

The goal of this assignment is to:

- Implement KNN Classifier and the other variants for Nearest Neighbor Learning Algorithms.
- Implement the criterion for choosing the optimal value of K.
- Evaluate the performance of the different variants and interpret the results.

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

### Exercise 1: Implement K-Nearest Neighbor (KNN)

You have to implement KNN algorithm. To implement KNN you have to

- Split data into a train and a test split (70% and 30% respectively).
- Implement a similarity (or a distance) measure. To begin with you can implement the Euclidean
  Distance.
- Implement a function that returns top K Nearest Neighbors for a given query (data point).
- You should provide the prediction for a given query (for a classification task you can use
  majority voting and for a regression you can use mean).
- Measure the quality of your prediction. [Hint: You have to choose a quality criterion according
  to the task you are solving i.e., a regression or a classification task].

### Exercise 2: Determination of Optimal Value of K in KNN algorithm

- How you can choose value of K for KNN. Give a criterion to choose an optimal value of K.
- Implement the criterion for choosing the optimal value of K.
- Experimentally, give evidence that your chosen value is better than other values of K. [Hint:
  run your experiment with different values of K and plot the error measure for each value].

### Exercise 3: Compare KNN algorithm with other Variants of Nearest Neighbor Learning

- Present the comparison of the three methods using evaluation results on test datasets
