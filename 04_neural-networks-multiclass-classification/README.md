# Assignment 4 – Neural Networks & Multiclass Classification (ML2)

## 📘 Task
Solve a **multiclass classification problem** on image data (Fashion MNIST).  
The dataset contained grayscale images of size **32×32 pixels**, provided in CSV format.  
The task required designing and training both **feedforward** and **convolutional** neural network models.

## 🔬 Approach
- **Preprocessing:**  
  - Normalized pixel values to [0,1]  
  - Split data into train/validation/test subsets  
  - Created PyTorch `TensorDataset` and `DataLoader`  

- **Feedforward Neural Networks (FNN):**  
  - Tested multiple depths and layer sizes  
  - Experimented with activation functions and optimizers
  - Validation accuracy: ~84%  

- **Convolutional Neural Networks (CNN):**  
  - Tried different architectures (2–5 convolutional layers, pooling, dropout, batch normalization)  
  - Validation accuracy: **~90%**, outperforming FNN  

## 📊 Results
- Final model: **CNN with 5 convolutional layers + max pooling + batch normalization + 1 fully connected layer**  
- Test accuracy: **0.91**  
- Evaluation accuracy: **0.90** (confirmed in feedback, considered a good result)  

---

## 📂 Files
- `neural_networks_multiclass_classification.ipynb` – Jupyter notebook with full solution  
- `train.csv` – training data *(not included due to size / Fashion MNIST source)*  
- `evaluate.csv` – evaluation data *(not included due to size / Fashion MNIST source)*  
- `results.csv` – predictions for evaluation set  
