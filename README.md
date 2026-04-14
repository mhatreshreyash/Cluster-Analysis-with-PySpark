# 📊 Clustering Analysis

## 📌 Project Description
This project focuses on **Clustering Analysis**, an unsupervised machine learning technique used to group similar data points.  

The main goal is to evaluate how clustering performance changes when the dataset is divided into multiple parts and then analyzed both individually and collectively.

---

## 🧠 Objective
To evaluate the performance of clustering when:
- Data is divided into **10 equal parts**
- Each part is analyzed independently
- Accuracy and performance trends are observed
- All data is combined to evaluate overall model performance

---

## 🧪 Methodology

### 📂 Dataset
- CSV format dataset

### 🔁 Steps
1. Split the dataset into **10 equal parts**
2. Apply clustering algorithm (unsupervised learning)
3. For each part:
   - Calculate accuracy score
   - Record observations
4. Store results in an Excel table:
   - Column 1: Data Range  
   - Column 2: Accuracy  
   - Column 3: Insights / Comments  
5. Remove outliers and compute **average accuracy**
6. Combine all parts and evaluate final model performance

---

## 📊 Summary Table (Example)

| Data Range        | Accuracy | Comment                     |
|------------------|---------|-----------------------------|
| Part 1 (0–100)   | 84.2%   | Consistent clusters         |
| Part 2 (101–200) | 72.5%   | Slight overlap observed     |
| Part 3 (201–300) | 88.7%   | Clean separation of data    |
| ...              | ...     | ...                         |
| Combined Data    | 90.3%   | Highest accuracy achieved   |
| Avg (Excl Outlier)| 86.5%  | Stable model across groups  |

---

## 🚀 Features
- Data segmentation into multiple parts
- Independent clustering analysis
- Accuracy tracking and comparison
- Outlier detection and removal
- Final combined model evaluation

---

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- Excel (for result tracking)

---

## 📈 Results & Insights
- Clustering performance varies based on data distribution
- Some partitions showed overlapping clusters (lower accuracy)
- Other partitions showed well-defined clusters (higher accuracy)
- Combined dataset produced the best performance

---

## 📚 Key Learnings
- Clustering performance depends heavily on data distribution
- Data segmentation impacts model accuracy
- Larger datasets improve clustering quality
- Outlier handling is essential for reliable results

---

## 🎯 Conclusion
This project demonstrates the importance of:
- Data segmentation
- Model evaluation in unsupervised learning
- Understanding clustering behavior across datasets

It highlights that not only the model but also how data is structured significantly impacts performance.

---

## 🧭 Future Work
- Compare clustering algorithms:
  - K-Means
  - DBSCAN
  - Agglomerative Clustering
- Apply dimensionality reduction:
  - PCA
  - t-SNE
- Extend analysis to high-dimensional datasets

---

## 🙌 Author
Shreyash Mhatre
