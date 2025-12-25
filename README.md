# Country Clustering using K-Means

## 📌 Project Overview
This project demonstrates the use of **unsupervised machine learning (K-Means clustering)** to group countries based on their **geographical coordinates (latitude and longitude)**. The objective is to identify natural geographic clusters and visualize them on a 2D plot.

---

## 📂 Dataset
The dataset contains the following columns:

- **Country** – Name of the country
- **Latitude** – Geographic latitude
- **Longitude** – Geographic longitude
- **Language** – Primary language spoken (not used for clustering)

Only **latitude and longitude** are used for clustering.

---

## ⚙️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook / Google Colab

---

## 🔍 Methodology
1. Loaded and explored the dataset using Pandas
2. Selected latitude and longitude as features
3. Applied **K-Means clustering** with predefined number of clusters
4. Assigned cluster labels to each country
5. Visualized clusters using a scatter plot

---

## 📊 Visualization
- Countries are plotted on a 2D graph (Longitude vs Latitude)
- Different colors represent different clusters
- Visualization helps understand geographical grouping of countries

---

## 🚀 Results
- Successfully grouped countries into clusters based on location
- Clear visual separation of geographic regions
- Demonstrates practical use of unsupervised learning

---

## 📁 Project Structure
country-clustering-kmeans/
│
├── data/
│ └── country_clusters.csv
│
├── notebooks/
│ └── Country_Cluster_KMeans.ipynb
│
├── README.md

---

## 🧠 Key Learning Outcomes
- Understanding of K-Means clustering
- Feature selection for unsupervised learning
- Data visualization for cluster interpretation
- Practical ML workflow using real-world data

---

## 🔮 Future Improvements
- Use Elbow Method to find optimal number of clusters
- Include more features (population, GDP, etc.)
- Interactive visualization using Plotly or Folium

---

## 👤 Author
**Sandesh Duduskar**  
Aspiring Data Scientist | Machine Learning Enthusiast
