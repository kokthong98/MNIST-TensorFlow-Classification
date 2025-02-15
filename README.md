# 🖼️ Image Classification with TensorFlow

## 📌 Project Overview
This project implements an image classification model using TensorFlow and Keras. The model is trained on a dataset of images and utilizes a fully connected neural network (Dense layers) to classify input images into different categories.

## 📊 Model Architecture
The neural network follows a fully connected (dense) architecture with the following layers:
- **Input Layer**: 28x28 images flattened into 784 features
- **Hidden Layer 1**: 128 neurons, ReLU activation
- **Hidden Layer 2**: 64 neurons, ReLU activation
- **Output Layer**: 10 neurons (softmax activation for multi-class classification)

## 🏋️ Training Details
- **Optimizer**: Adam (Adaptive Moment Estimation)
- **Loss Function**: Sparse Categorical Crossentropy (for multi-class classification)
- **Evaluation Metric**: Accuracy

## 📂 Dataset
- **Source**: [Specify dataset source, e.g., MNIST, CIFAR-10, custom dataset]
- **Preprocessing**:
  - Normalized pixel values to [0,1] range
  - Reshaped images if necessary
  - Split into training and test sets

## 📈 Results & Performance
- **Training Accuracy**: 0.9728
- **Test Accuracy**: 0.9766
- **Test Loss**: 0.0811
- **Predictions vs Actual**:
  - **Predicted**: [7, 2, 1, 0, 4, 1, 4, 9, 5, 9]
  - **Actual**: [7, 2, 1, 0, 4, 1, 4, 9, 5, 9]

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📌 Future Improvements
- Experiment with CNNs for better performance
- Data augmentation techniques to improve generalization
- Hyperparameter tuning for optimal accuracy


