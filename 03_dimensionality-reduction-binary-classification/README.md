# Assignment 3 – Dimensionality Reduction & Binary Classification (ML2)

## Task
Solve a **binary classification problem** on image data (Fashion MNIST).  
The dataset contained grayscale images of size **28×28 pixels**, provided in CSV format.  
The task required handling **high-dimensional input data** through dimensionality reduction and applying multiple classification models.

## Approach
- **Preprocessing:**  
  - Split data into train/validation/test subsets  
  - Normalized features using Min-Max scaling  
  - Visualized and explored input images  

- **Models:**  
  - **Support Vector Machine (SVM):** tested with multiple kernels
  - **Naive Bayes Classifier**  
  - **Linear Discriminant Analysis (LDA)**  

- **Dimensionality Reduction:**  
  - **PCA (Principal Component Analysis):** experimented with different numbers of components  
  - **LLE (Locally Linear Embedding):** compared results to PCA  

## Results
- Best model: **PCA + SVM (30 components)**  
- Test accuracy: **0.9667**  
- Evaluation accuracy: **0.976** (above expectations, praised in feedback)  

## Files
- `dimensionality_reduction_binary_classification.ipynb` – Jupyter notebook with full solution  
- `train.csv` – training data  
- `evaluate.csv` – evaluation data  
- `results.csv` – predictions for evaluation data  
