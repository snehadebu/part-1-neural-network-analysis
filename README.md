# part-1-neural-network-analysis
# Part 1 - Neural Network Fundamentals and Training Behavior Analysis

## Objective
The objective of this project is to build and analyze a feed-forward neural network model for a supervised learning problem using a structured dataset.

---

## Tasks Performed

### 1. Dataset Understanding
- Loaded and explored the dataset
- Checked dataset shape and feature types
- Performed missing value analysis
- Generated statistical summaries
- Visualized target variable distribution

### 2. Data Preprocessing
- Removed missing values
- Encoded categorical variables
- Scaled numerical features
- Split dataset into training and testing sets

### 3. Neural Network Model Building
- Built a feed-forward neural network using TensorFlow/Keras
- Used ReLU activation in hidden layers
- Used Sigmoid activation in output layer
- Used Binary Crossentropy loss function
- Used Adam optimizer

### 4. Training and Evaluation
- Trained the neural network model
- Evaluated model performance on testing data
- Generated confusion matrix
- Generated classification report
- Visualized training and validation accuracy/loss

### 5. Hyperparameter Experimentation
Different neural network configurations were tested by modifying:
- Number of hidden layers
- Number of neurons
- Learning rate
- Number of epochs

---

## Technologies Used
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Repository Structure

```text
part-1-neural-network-analysis/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
    ├── model_comparison_table.csv
    ├── confusion_matrix.png
    ├── accuracy_graph.png
    └── loss_graph.png
```

---

## Conclusion
The neural network successfully learned patterns from the dataset and achieved good classification performance. Hyperparameter tuning improved overall model accuracy and training behavior.
