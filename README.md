# Multi-class-classification-using-KNN-classifier
Build a KNN-based classification model from scratch to classify images in the  CIFAR-10 dataset.

---

## 📊 Dataset Description
The **CIFAR-10 dataset** consists of **60,000 color images** of size **32×32 pixels**, divided into:
- **50,000 training images**
- **10,000 testing images**

Each image belongs to one of the following **10 classes**:
1. Airplane  
2. Automobile  
3. Bird  
4. Cat  
5. Deer  
6. Dog  
7. Frog  
8. Horse  
9. Ship  
10. Truck  

---

## 🧠 Methodology
- Images are flattened into feature vectors
- The dataset is divided into **training and testing sets**
- A **KNN classifier is implemented from scratch** without using any built-in KNN libraries
- Distance is computed between test images and training images
- Majority voting is used to assign the final class label

---

## ⚙️ Hyperparameter Experimentation

### 🔹 Values of K
- Multiple values of K are tested to analyze their effect on accuracy

### 🔹 Distance Metrics
- Euclidean Distance  
- Manhattan Distance  
- Minkowski Distance  
- Cosine Similarity  
- Hamming Distance  

---

## 📈 Evaluation Metrics
- **Testing Accuracy**
- **Confusion Matrix**
- **Precision**
- **Recall**

The best combination of **K value** and **distance metric** is selected based on maximum test accuracy.

---

## 📉 Visualizations
- Accuracy vs **K** plots for different distance metrics
- Comparative visualization of distance metrics
- Analysis of how the choice of distance metric affects performance

---

## 📌 Results & Inferences
- Identification of the optimal K and distance metric
- Performance trends across varying K values
- Strengths and limitations of KNN for image classification
- Insights derived from experimental results and plots

---

## ▶️ How to Run the Code
1. Clone or download this repository
2. Open `CIFAR10_KNN.ipynb` using:
   - Google Colab **or**
   - Jupyter Notebook
3. Ensure the CIFAR-10 dataset is available in the `data/` directory
4. Run all cells sequentially to reproduce results

---

It includes:
- Algorithm explanation
- Experimental setup
- Performance evaluation
- Plots and inferences
- Conclusion

---

## 🛠️ Tools & Technologies
- **Python 3**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Google Colab / Jupyter Notebook**
- **GitHub**

---

