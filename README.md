# Learning in AI: Perceptron vs. Gradient Descent Delta Rule

## Project Overview
This project explores and compares two fundamental machine learning algorithms: the **Perceptron Learning Rule** and the **Gradient Descent Delta Rule**. The objective is to analyze their performance in classifying iris flower species and optimize their accuracy by experimenting with different activation functions and learning rates.

## Dataset
The project utilizes the **Iris dataset**, a well-known dataset for classification problems. It contains 150 samples of iris flowers from three species (*Setosa, Versicolor, and Virginica*), with four feature measurements:
- Sepal length
- Sepal width
- Petal length
- Petal width

**Dataset Link:** [UCI Machine Learning Repository - Iris Dataset](https://archive.ics.uci.edu/dataset/53/iris)

## Implementation
The project involves implementing the two learning algorithms from scratch in Python:

### 1. Perceptron Learning Rule
- A simple linear classifier.
- Updates weights using a threshold-based step activation function.
- Converges only for linearly separable data.

### 2. Gradient Descent Delta Rule
- Uses gradient descent to minimize error.
- Incorporates a differentiable activation function (e.g., sigmoid or ReLU).
- Can work with non-linearly separable data.

## Experimentation
The following experiments were conducted:
- **Training & Testing Split:** Dataset was split in an 80/20 ratio.
- **Activation Functions:** Various functions like step, sigmoid, and ReLU were tested.
- **Learning Rate Tuning:** Adjusted learning rates to optimize convergence and minimize loss.

## Results & Observations
- **Key Differences:** The perceptron struggled with non-linearly separable data, whereas the delta rule showed better generalization.
- **Impact of Activation Functions:** Sigmoid and ReLU improved performance in the delta rule.
- **Learning Rate Adjustments:** Lower learning rates resulted in smoother convergence, while higher rates sometimes led to instability.

## Challenges & Solutions
- **Manual Implementation Complexity:** Overcame issues by structuring code modularly and debugging weight updates.
- **Optimizing Hyperparameters:** Used grid search and empirical testing to find the best learning rate and activation function.

## Requirements
To run the project, install the required Python libraries:
```bash
pip install numpy pandas matplotlib scikit-learn
```

## Running the Project
Run the Python script using:
```bash
python main.py
```
This will train both models and display performance metrics.

## Future Enhancements
- Implement additional learning algorithms (e.g., Adaline, Multi-layer Perceptron).
- Extend experiments to larger and more complex datasets.
- Improve visualization of decision boundaries.

## Output
![Sudoku Solver Screenshot](https://github.com/Muradhameed921/Sudoku-Puzzle-Solver/blob/main/O1.jpg)
