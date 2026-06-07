# Iris Flower Classification 🌸

## Overview

This project uses Machine Learning to classify Iris flowers into three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The classification is based on four flower measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The model is trained using the Iris dataset and predicts the species of a flower based on these features.

---

## Dataset

The project uses the famous Iris Dataset, which contains:

- 150 samples
- 4 input features
- 3 flower species

### Features

| Feature | Description |
|----------|------------|
| Sepal Length | Length of sepal (cm) |
| Sepal Width | Width of sepal (cm) |
| Petal Length | Length of petal (cm) |
| Petal Width | Width of petal (cm) |

### Target Classes

- Setosa
- Versicolor
- Virginica

---

## Technologies Used

- Python
- Pandas
- Scikit-Learn
- Google Colab

---

## Machine Learning Workflow

1. Load Dataset
2. Explore Dataset
3. Split Data into Training and Testing Sets
4. Train Decision Tree Classifier
5. Evaluate Model Performance
6. Predict Flower Species

---

## Project Structure

```
Iris-Flower-Classification/
│
├── iris_classification.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Iris-Flower-Classification.git
```

Move into the project directory:

```bash
cd Iris-Flower-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open the notebook in Google Colab or Jupyter Notebook and run all cells.

---

## Model Used

- Decision Tree Classifier

---

## Evaluation Metric

The model is evaluated using:

- Accuracy Score
- Classification Report

---

## Sample Prediction

Input:

```python
[5.1, 3.5, 1.4, 0.2]
```

Output:

```text
Setosa
```

---

## Results

The model achieves high classification accuracy on the test dataset.

---

## Future Improvements

- Data Visualization using Matplotlib
- Confusion Matrix
- Hyperparameter Tuning
- Compare Multiple Models
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest

---

## Author

Vansh Joshi

B.Tech Computer Science and Engineering

Interested in Artificial Intelligence and Machine Learning
