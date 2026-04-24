# Neural Network Experiments and Implementations

This repository presents a structured set of neural network experiments implemented from scratch and using standard libraries. The focus is not only on implementation, but on understanding how different models behave, where they fail, and why they are used.

The project progresses from basic numerical operations to advanced neural architectures such as MLP, CNN, RNN, and Hopfield Networks.

---

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- Scikit-learn

---

## Project Structure
Neural-Network-Lab/
│
├── Ex-1 NumPy/
├── Ex-2 Pandas/
├── Ex-3 SciPy/
├── Ex-4 Plotting/
├── Ex-5 Perceptron/
├── Ex-6 XOR-MLP/
├── Ex-7 Activation/
├── Ex-8 MLP/
├── Ex-9 CNN-RNN/
├── Ex-10 Regression/
├── Ex-11 Hopfield/
│
└── README.md


---

## Experiments Breakdown

### 1. NumPy Operations
Basic array manipulation, matrix operations, and numerical computation.

**Key Insight**  
Vectorization is critical for performance in machine learning pipelines.

**Output**

![Output](Ex-1_Numpy/Ex-1_output(a).jpeg)
![Output](Ex-1_Numpy/Ex-1_output(b).jpeg)

---

### 2. Pandas Data Handling
DataFrame creation, feature addition, and aggregation using group-by.

**Key Insight**  
Data preprocessing is often more important than the model itself.

**Output**

![Output](Ex-2_Pandas/Ex-2_output.jpeg)

---

### 3. SciPy Operations
Root finding, optimization, sparse matrices, and distance calculations.

**Key Insight**  
Optimization is the backbone of training neural networks.

**Output**

![Output](Ex-3_Sicpy/Ex-3_output(a).jpeg)
![Output](Ex-3_Sicpy/Ex-3_output(b).jpeg)

---

### 4. Function Visualization
Plotting sine wave using Matplotlib.

**Key Insight**  
Visualization helps in understanding function behavior and model outputs.

**Output**

![Output](Ex-4_Matplotlib/Ex-4_output.jpeg)

---

### 5. Perceptron Learning

Implements a basic perceptron using weight updates.

**Key Insight**  
- Works only for linearly separable data  
- Fails on XOR problem  

**Output**

![Output](Ex-5_Perceptron/Ex-5_output.jpeg)

---

### 6. XOR Problem using MLP

Uses hidden layers to solve a non-linear classification problem.

**Key Insight**  
Adding hidden layers introduces non-linearity, enabling complex decision boundaries.

**Output**

![Output](Ex-6_XOR_(MLP)/Ex-6_output.jpeg)

---

### 7. Activation Functions

Visualization of Sigmoid, ReLU, and Linear functions.

**Key Insight**

| Function | Behavior | Problem |
|--------|--------|--------|
| Sigmoid | Smooth | Vanishing gradient |
| ReLU | Fast, sparse | Dead neurons |
| Linear | Simple | No learning power |

**Output**

![Output](Ex-7_Activation_Function/Ex-7_output.jpeg)

---

### 8. Multi-Layer Perceptron (MLP)

Implementation using Scikit-learn.

**Key Insight**  
MLPs approximate complex functions but require proper tuning.

**Output**

![Output](Ex-8_MLP/Ex-8_output.jpeg)

---

### 9. CNN and RNN Basics

- CNN: Convolution operation for feature extraction  
- RNN: Sequence processing using temporal dependency  

**Key Insight**

| Model | Strength | Use Case |
|------|--------|--------|
| CNN | Spatial understanding | Images |
| RNN | Sequential memory | Time series |

**Output**

![Output](Ex-9_RNN_CNN/Ex-9_output.jpeg)

---

### 10. Linear Regression

Basic regression model using optimization.

**Key Insight**  
Serves as the foundation for gradient-based learning.

**Output**

![Output](Ex-10_Optimizer_Alternative/Ex-10_output.jpeg)

---

### 11. Hopfield Network

Implements associative memory.

**Key Insight**  
Recalls stored patterns from incomplete or noisy input.

**Output**

![Output](Ex-11_Hopfield/Ex-11_output.jpeg)

---

## Model Comparison

| Model | Type | Limitation |
|------|------|----------|
| Perceptron | Linear | Cannot solve XOR |
| MLP | Non-linear | Needs tuning |
| CNN | Spatial | Requires large data |
| RNN | Sequential | Vanishing gradient |
| Hopfield | Memory | Limited capacity |

---

## What This Project Demonstrates

- Understanding of core ML foundations  
- Implementation from scratch and library-based  
- Ability to analyze model behavior  
- Comparison of different architectures  

---

## How to Run

```bash
pip install numpy pandas matplotlib scipy scikit-learn
python filename.py
