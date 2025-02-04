# Simmple_ANN_Model_iris_dataset
# ANN Model on Iris Dataset

This repository demonstrates an Artificial Neural Network (ANN) built with TensorFlow and Keras to classify the Iris dataset. The model is trained to distinguish between three species of iris flowers based on their petal and sepal dimensions.

## 🚀 Project Overview
The goal of this project is to implement a simple ANN for multi-class classification using:
- TensorFlow/Keras for building and training the neural network
- Scikit-learn for data preprocessing and dataset splitting

## 📝 Dataset
The Iris dataset is a classic dataset in machine learning, containing 150 samples with 4 features each:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

There are 3 classes (species) to predict:
- Setosa
- Versicolor
- Virginica

## 📁 Project Structure
- `iris_ann.py`: Main Python script containing the ANN model implementation.
- `README.md`: Project documentation.

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/iris-ann-model.git
cd iris-ann-model

# Set up virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 🖥️ Running the Model

```bash
python iris_ann.py
```

## 🧠 Model Architecture
- Input Layer: 4 neurons
- Hidden Layer: 8 neurons with ReLU activation
- Output Layer: 3 neurons with Softmax activation

## 📊 Results
Achieved a test accuracy of over 90% on the Iris dataset.

## 🤝 Contributing
Feel free to open issues or submit pull requests.

## 📄 License
This project is licensed under the MIT License.

## 📫 Contact
For any questions, feel free to reach out!

