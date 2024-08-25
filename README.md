

# MNIST CNN Experiments

This repository contains the results of various experiments performed on the MNIST dataset using a Convolutional Neural Network (CNN) architecture. The focus of these experiments was to explore different activation functions, dropout rates, learning rates, and network configurations to optimize model performance.

## 🧪 **Experiments Overview**

We conducted 10 broad categories of experiments with a total of 5 variations for each. The primary goal was to maximize the test accuracy while maintaining a good balance between training and validation accuracy. Below is a summary of the experiments:

### 1. **Base Code**
   - **Experiment**: Alternative use of ReLU and tanh activation functions (starting with tanh).
   - **Train Accuracy**: 98.708%
   - **Test Accuracy**: 99.06%
   - **Validation Accuracy**: 98.625%

### 2. **All Layers with Tanh Activation**
   - **Experiment**: All layers having tanh as the activation function.
   - **Train Accuracy**: 98.285%
   - **Test Accuracy**: 98.76%
   - **Validation Accuracy**: 98.15%

### 3. **Starting with ReLU Function**
   - **Experiment**: Alternative use of ReLU and tanh activation functions (starting with ReLU).
   - **Train Accuracy**: 98.49%
   - **Test Accuracy**: 98.97%
   - **Validation Accuracy**: 98.475%

### 4. **Using Leaky ReLU Activation**
   - **Experiment**: Using Leaky ReLU activation in every layer.
   - **Train Accuracy**: 98.613%
   - **Test Accuracy**: **99.23%** (Highest Test Accuracy)
   - **Validation Accuracy**: 98.6%

### 5. **Changing Dropout (p=0.2 to p=0.4)**
   - **Experiment**: Changing dropout from p=0.2 to p=0.4.
   - **Train Accuracy**: 98.085%
   - **Test Accuracy**: 99.04%
   - **Validation Accuracy**: 98.483%

### 6. **Changing Dropout (p=0.2 to p=0.15)**
   - **Experiment**: Changing dropout from p=0.2 to p=0.15.
   - **Train Accuracy**: 98.746%
   - **Test Accuracy**: 99.14%
   - **Validation Accuracy**: 98.75%

### 7. **Changing Learning Rate**
   - **Experiment**: Changing the learning rate from lr=0.0003 to lr=0.0008.
   - **Train Accuracy**: 98.723%
   - **Test Accuracy**: 99.16%
   - **Validation Accuracy**: 98.50%

### 8. **Adding a New Fully Connected Layer**
   - **Experiment**: A new fully connected layer was added with `in_features=10` and `out_features=10` (new number of parameters = 8315).
   - **Train Accuracy**: 98.542%
   - **Test Accuracy**: 99.07%
   - **Validation Accuracy**: 98.525%

### 9. **Changing the Number of Neurons**
   - **Experiment**: The number of neurons in the last fully connected layer was changed (`in_features=40`, `out_features=10`).
   - **Train Accuracy**: 98.35%
   - **Test Accuracy**: 99.09%
   - **Validation Accuracy**: 98.56%

### 10. **Changing Kernel Size**
   - **Experiment**: Kernel size was changed from `kernel size=3` to `kernel size=2`.
   - **Train Accuracy**: 98.65%
   - **Test Accuracy**: 99.15%
   - **Validation Accuracy**: 98.46%

## 📊 **Results**

- **Green cells** represent the highest test accuracy achieved across the experiments.
- The highest test accuracy of **99.23%** was achieved using the **Leaky ReLU activation** function in every layer.

## 📝 **Conclusion**

These experiments provide insight into how different activation functions, dropout rates, learning rates, and network configurations impact the performance of a CNN model on the MNIST dataset. The Leaky ReLU activation function proved to be the most effective in maximizing test accuracy.

---

