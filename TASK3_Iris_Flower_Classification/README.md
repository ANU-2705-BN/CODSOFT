🌸 Iris Flower Classification using K-Means Clustering
📌 Project Overview

The Iris Flower Classification project demonstrates how unsupervised machine learning can be applied to group iris flowers into different species using the K-Means clustering algorithm.

The model learns patterns from petal and sepal measurements and clusters the flowers into groups that closely resemble the original species:

🌼 Setosa

🌷 Versicolor

🌺 Virginica

This project is ideal for beginners to understand clustering, visualization, and model evaluation.

📊 Dataset Information

📁 Dataset Used: Iris Dataset (loaded using Seaborn)

🧾 Features

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

🎯 Target (for evaluation only):

Species (encoded using factorization)

🎯 Project Objectives

✅ Perform clustering using K-Means
✅ Visualize data in 2D and 3D
✅ Determine optimal number of clusters using the Elbow Method
✅ Compare predicted clusters with actual species
✅ Evaluate clustering performance using a confusion matrix

🧠 Machine Learning Approach

🔹 Algorithm Used: K-Means Clustering
🔹 Type: Unsupervised Learning
🔹 Number of Clusters: 3
🔹 Features Used for Clustering:

Petal Length

Petal Width

📈 Visualizations Included

📊 3D Scatter Plots

Petal Length vs Petal Width vs Species

Sepal Length vs Sepal Width vs Species

📉 Elbow Method Plot

Used to find the optimal number of clusters

🎨 2D Scatter Plots

Petal features with species hue

Sepal features with species hue

📦 Confusion Matrix

Compares true species labels with predicted clusters

🛠️ Technologies & Libraries Used

🧑‍💻 Programming Language

Python 🐍

📚 Libraries

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

🔍 Workflow Summary

1️⃣ Load the Iris dataset
2️⃣ Encode species labels numerically
3️⃣ Explore and clean the dataset
4️⃣ Visualize feature relationships
5️⃣ Apply Elbow Method to select K
6️⃣ Train K-Means model
7️⃣ Predict clusters
8️⃣ Evaluate using confusion matrix

✅ Results

🎯 The K-Means algorithm successfully grouped iris flowers into three clusters.
📊 The confusion matrix shows strong alignment between clusters and actual species.
🌟 Petal features provided better clustering compared to sepal features.
