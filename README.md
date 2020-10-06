# Handwritten-Digit-Recognizer
Recognizing MNIST Handwritten Digits using KNN

Algorithm:
Let m be the number of training data samples. Let p be an unknown point.

Store the training samples in an array of data points arr[]. This means each element of this array represents a tuple (x, y).
for i=0 to m:
  Calculate Euclidean distance d(arr[i], p).
Make set S of K smallest distances obtained. Each of these distances corresponds to an already classified data point.
Return the majority label among S.
