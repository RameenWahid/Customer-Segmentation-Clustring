# Customer Segmentation using Clustering

## 📌 Project Overview

This project uses **Machine Learning Clustering techniques** to divide customers into different groups based on their:

* Age
* Annual Income
* Spending Score

The main goal is to identify customers with similar characteristics and understand their behavior.

Since there is **no predefined target variable**, this is an **Unsupervised Learning** project.

---

## 🎯 Objectives

* Explore and understand customer data
* Clean and prepare the dataset
* Apply feature scaling using `StandardScaler`
* Find suitable customer groups
* Apply **K-Means Clustering**
* Determine the appropriate number of clusters using:

  * Elbow Method
  * Silhouette Score
* Interpret the resulting customer segments
* Apply **Hierarchical Clustering**
* Create an interactive customer segment prediction interface

---

## 🧠 Machine Learning Techniques

### 1. K-Means Clustering

K-Means groups customers into clusters based on similarity between their features.

### 2. Hierarchical Clustering

Hierarchical clustering is used to understand the relationships between customers and visualize how they can be grouped together.

### 3. Feature Scaling

`StandardScaler` is used before clustering so that features with different scales have a balanced effect on the clustering algorithm.

---

## 📊 Features Used

| Feature                | Description                        |
| ---------------------- | ---------------------------------- |
| Age                    | Customer's age                     |
| Annual Income (k$)     | Customer's annual income           |
| Spending Score (1-100) | Customer's spending behavior score |

---

## 🔍 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Feature Scaling
   ↓
K-Means Clustering
   ↓
Elbow Method + Silhouette Score
   ↓
Cluster Interpretation
   ↓
Hierarchical Clustering
   ↓
Customer Segment Prediction
```

---

## 💡 Customer Segmentation

After clustering, customers are grouped according to similarities in their age, income, and spending behavior.

The clusters can then be interpreted as different customer types, such as:

* High-income / Low-spending customers
* Lower-income / High-spending customers
* Medium-income / Medium-spending customers

The exact characteristics of each segment depend on the trained clustering model.

---

## 🖥️ Interactive Segment Prediction

The project also includes an interactive interface where a user can enter:

```text
Age
Annual Income
Spending Score
```

The system then determines the customer's closest cluster and displays the corresponding customer segment.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* IPyWidgets

---

## 📁 Project Structure

```text
Customer Segmentation/
│
├── Customer_Segmentation.ipynb
├── dataset.csv
├── README.md
└── ...
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd "Customer Segmentation"
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib scikit-learn ipywidgets
```

### 4. Open the notebook

```bash
jupyter notebook
```

Open the `.ipynb` file and run the cells.

---

## 📈 Results

The clustering model successfully divides customers into groups with different patterns of:

* Age
* Income
* Spending behavior

These segments can help demonstrate how unsupervised machine learning can be used for **customer analysis and segmentation**.

---

## 📚 Learning Outcomes

Through this project, I practiced:

* Data preprocessing
* Exploratory Data Analysis
* Feature scaling
* Unsupervised Machine Learning
* K-Means Clustering
* Elbow Method
* Silhouette Score
* Hierarchical Clustering
* Cluster interpretation
* Interactive ML applications

---

## 👩‍💻 Author

**Rameen Wahid Rajput**

Software Engineering Student | Machine Learning Learner

GitHub: `RameenWahid`
