# 🐱 Cats vs Dogs Image Classification using CNN

## 📌 Project Overview
This project uses a Convolutional Neural Network (CNN) built with PyTorch to classify images into two categories: **Cats** and **Dogs**.

The project demonstrates the fundamentals of deep learning, image classification, model training, and performance evaluation.

## 🎯 Objectives
- Understand how CNNs work for image classification.
- Prepare and preprocess image data.
- Build and train a CNN using PyTorch.
- Evaluate model performance using accuracy and classification metrics.

## 📂 Dataset
The project uses the **CIFAR-10 dataset**, which contains images belonging to 10 classes.

For this binary classification task, only the following classes are used:
- Cat
- Dog

**Dataset used in this project:**
- Training subset: 10,000 images
- Testing subset: 2,000 images
- Image dimensions: 32 × 32 pixels
- Number of classes: 2

The dataset is loaded through `torchvision`. You do not need to upload the dataset to this repository.

## 🛠️ Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🧠 Model Architecture
The CNN contains three convolutional blocks, each using:
- Convolutional layers
- ReLU activation
- Max pooling

The classifier consists of:
- A fully connected layer with 256 neurons
- ReLU activation
- An output layer with 2 neurons

The model uses **Cross-Entropy Loss** and the **Adam optimizer** during training.

## 📊 Results
The model achieved approximately **77.65% test accuracy** in the recorded experiment.

This result provides a baseline for further improvements in image classification.

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/4-4-2004/Cats-Dogs-CNN-Classification.git
```

### 2. Navigate to the project folder
```bash
cd Cats-Dogs-CNN-Classification
```

### 3. Install the dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 5. Run the notebook
Open `cats_dogs_cnn.ipynb` and execute the cells from top to bottom.

Ensure that PyTorch and Torchvision are installed correctly for your system.

## 🔮 Future Improvements
- Apply data augmentation to improve generalization.
- Add dropout and other regularization techniques.
- Experiment with different CNN architectures.
- Improve model accuracy through hyperparameter tuning.
- Visualize predictions and analyze misclassified images.

## 👩‍💻 Author
**Sonal Mishra**

GitHub: [4-4-2004](https://github.com/4-4-2004)
