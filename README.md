# Perceptron - Simple Machine learning Algorithm

## Perceptron Algorithm

The perceptron algorithm is a type of linear classifier and one of the simplest types of artificial neural networks. It was invented by Frank Rosenblatt in the mid-20th century for performing certain calculations to detect input data capabilities or business intelligence. 

The algorithm is used for supervised learning of binary classifiers, which means it can be used to classify data into one of two categories.

## How it Works

The perceptron algorithm works by finding a hyperplane that separates the two classes in the feature space. The weights and bias determine the position and orientation of this hyperplane. During training, the algorithm adjusts the weights and bias to minimize the error between the predicted output and the actual output. Once trained, the perceptron can make predictions on new data by calculating the weighted sum of inputs and passing it through the activation function.

Here's how the perceptron algorithm works, step by step:
1. **Initialize the weights and bias**: The algorithm starts with initializing the weights and bias to small random values.
2. **Calculate weighted sum**: For each training example, the weighted sum of inputs and weights is calculated, which is also known as the dot product.
3. **Apply activation function**: The result of the weighted sum is passed through an activation function, which can be a step function, sigmoid function, or any other non-linear function.
4. **Update weights and bias**: The weights and bias are updated based on the error between the predicted output and the actual output.
5. **Repeat**: Steps 2-4 are repeated for a fixed number of iterations or until the error is minimized.

