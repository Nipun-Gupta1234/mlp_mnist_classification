# 🧠 MNIST Handwritten Digit Classification using PyTorch MLP

A complete PyTorch implementation of a **Multi-Layer Perceptron (MLP)** for handwritten digit classification on the **MNIST** dataset. This project demonstrates the complete deep learning workflow—from data preprocessing to model training, evaluation, hyperparameter experimentation, and visualization.

---

## 📌 Features

- ✅ PyTorch implementation of an MLP classifier
- ✅ Automatic GPU (CUDA/MPS) support
- ✅ Configurable architecture
  - Hidden layer sizes
  - Activation functions
  - Dropout
  - Learning rate
- ✅ Early stopping
- ✅ Learning rate scheduling
- ✅ Training & validation monitoring
- ✅ Test set evaluation
- ✅ Confusion matrix visualization
- ✅ Prediction visualization
- ✅ Multiple experiment comparison

---

## 📂 Project Structure

```
mlp_mnist_classifier.ipynb
```

The notebook contains:

1. Library imports
2. Reproducibility setup
3. Device configuration
4. Data preprocessing
5. Dataset loading
6. Model definition
7. Training pipeline
8. Validation
9. Testing
10. Visualization
11. Hyperparameter experiments
12. Result comparison

---

## 🏗️ Model Architecture

The classifier consists of:

- Flatten input image (28×28 → 784)
- Fully Connected Hidden Layers
- Activation Functions
- Dropout Regularization
- Output Layer (10 classes)

Example architecture:

```
784
 ↓
Linear(784 → 256)
 ↓
ReLU
 ↓
Dropout
 ↓
Linear(256 → 128)
 ↓
ReLU
 ↓
Dropout
 ↓
Linear(128 → 10)
```

The architecture is fully configurable.

---

## ⚙️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn

---

## 🚀 Training Features

The notebook includes:

- Early Stopping
- Validation Accuracy Tracking
- Learning Rate Scheduler
- Model Checkpoint Selection
- Training History Recording

Metrics tracked:

- Training Loss
- Validation Loss
- Training Accuracy
- Validation Accuracy

---

## 📊 Evaluation

After training, the notebook evaluates the model on the MNIST test dataset using:

- Test Accuracy
- Test Loss
- Confusion Matrix
- Sample Predictions
- Correct vs Incorrect Predictions

---

## 🧪 Hyperparameter Experiments

Multiple experiments can be performed by changing:

- Hidden layer sizes
- Activation functions
- Dropout probability
- Learning rate
- Number of epochs

The notebook compares each experiment and reports:

- Number of parameters
- Test accuracy
- Test loss

---

## 📈 Visualizations

The project generates:

- Training loss curves
- Validation loss curves
- Accuracy curves
- Confusion matrix
- Prediction samples
- Experiment comparison plots

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/mlp-mnist-classifier.git

cd mlp-mnist-classifier
```

Install dependencies:

```bash
pip install torch torchvision matplotlib numpy scikit-learn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
mlp_mnist_classifier.ipynb
```

---

## ▶️ Usage

Run the notebook sequentially.

The notebook will:

1. Download the MNIST dataset
2. Train the MLP model
3. Validate during training
4. Evaluate on the test dataset
5. Display performance metrics and visualizations

---

## 📚 Dataset

**MNIST Handwritten Digits**

- 70,000 grayscale images
- Image size: **28 × 28**
- 10 digit classes (0–9)

Automatically downloaded using `torchvision.datasets.MNIST`.

---

## 🎯 Learning Objectives

This project demonstrates:

- Neural network implementation in PyTorch
- Data preprocessing
- Model training
- Validation strategies
- Hyperparameter tuning
- Performance evaluation
- Visualization of results
- Experiment management

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ If you found this project useful, consider giving it a star!