# 🧪 K-Means Clustering Visual Explorer

An interactive Python learning tool designed to demonstrate synthetic data generation, K-Means clustering, label alignment, and model evaluation in 2D space. 

This notebook allows students and practitioners to experiment with spatial parameters—such as cluster distance, dispersion (variance), and sample size—to visually inspect how unsupervised clustering models perform under varying conditions.

---

## 🚀 Open directly in Google Colab

No local software installation or environment configuration required. Click the badge below to run the notebook instantly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

---

## 🔑 Key Concepts Covered

* **Synthetic Data Generation:** Utilizing `numpy.random.normal` to generate 2D Gaussian clusters.
* **Unsupervised Learning:** Applying `sklearn.cluster.KMeans` to group unlabeled feature matrices.
* **Cluster Label Alignment:** Resolving the unsupervised label-switching problem by mapping assigned cluster IDs to ground-truth labels using `np.bincount`.
* **Accuracy Measurement:** Calculating model classification accuracy following label alignment.
* **Data Visualization:** Rendering 2D scatter plots with `matplotlib` to compare ground-truth labels against model predictions.

---

## 🛠️ Tech Stack & Requirements

* **Python 3.x**
* **NumPy**
* **Matplotlib**
* **Scikit-Learn**

*(Note: Pre-installed automatically within the Google Colab runtime environment.)*

---

## 💻 How to Run

### Option 1: Google Colab (Recommended)
1. Upload the `.ipynb` file to your Google Drive.
2. Open with **Google Colaboratory** and click **Run All** (`Ctrl + F9`).

### Option 2: Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/kmeans-clustering-lab.git](https://github.com/your-username/kmeans-clustering-lab.git)
