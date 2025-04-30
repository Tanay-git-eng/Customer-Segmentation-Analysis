# Customer-Segmentation

A KMeans Clustering model for Market Segmentation of Mall Customers.

This project performs **customer segmentation** using unsupervised machine learning techniques. It involves loading and preprocessing mall customer data, performing exploratory data analysis (EDA), and then segmenting customers into clusters using the KMeans algorithm. The resulting clusters help businesses identify target audiences based on spending behavior and income, thereby enabling data-driven marketing strategies and customer retention efforts.

---

## Benefits of Customer Segmentation

1. **Personalized Marketing Campaigns**:
   - Helps businesses tailor product recommendations and offers based on customer behavior, improving ROI on advertising spend.

2. **Customer Retention and Loyalty**:
   - Identifies high-value or at-risk customers to build loyalty programs or proactive retention strategies.

3. **Product Development and Inventory Planning**:
   - Aligns product features and stock levels with the needs of distinct customer groups.

4. **Strategic Business Decision Making**:
   - Empowers sales and management teams with data-driven insights to make decisions on promotions, store layout, and service improvements.

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

---

## Features

- 📊 Exploratory Data Analysis (EDA)
- 📈 Unsupervised Clustering using KMeans
- 📉 Dimensionality reduction with PCA (optional)
- 🧮 Elbow method to find optimal clusters
- 📌 Visualizations: scatter plots, pair plots, box plots, heatmaps
- 🎯 Customer group identification based on income and spending score

---

## Installation

### Prerequisites

To run this project, ensure you have:

- Python 3.x
- Jupyter Notebook or compatible IDE

### Install Dependencies

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
   cd customer-segmentation

2. Install required packages:
   
   pip install -r requirements.txt


**Usage**
**Load and Preprocess Dataset**
1. Place Mall_Customers.csv in the /data directory.
2. Run the Jupyter Notebook Customer_Segmentation.ipynb.

**Steps Performed**

 -- Load dataset using pandas
 -- Clean and preprocess the data (if necessary)
 -- Visualize feature distributions (income, spending, age, gender)
 -- Perform clustering using KMeans from scikit-learn
 -- Visualize resulting clusters using matplotlib and seaborn
 -- Analyze customer characteristics in each cluster

**Example Visuals**

 -- sns.kdeplot() to analyze income distribution
 -- plt.plot(range(1, 11), inertia) to determine optimal clusters
 -- sns.scatterplot() to visualize clustered customers


 **Project Structure**
 customer-segmentation/
│
├── data/
│   └── Mall_Customers.csv        # Dataset file
│
├── notebook/
│   └── Customer_Segmentation.ipynb  # Full ML pipeline in Jupyter Notebook
│
├── models/
│   └── kmeans_model.pkl          # Saved KMeans model (optional)
│
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation

**Features**

 -- Easy-to-follow notebook with comments
 -- Visual representation of customer clusters
 -- Gender and age distribution comparisons across clusters
 -- Summary tables using pd.crosstab()

 **Example Use Cases**
 
 -- Retail mall businesses analyzing customer behavior
 -- E-commerce platforms for personalized recommendations 
 -- Financial services segmenting clients for product targeting

 **Acknowledgments**
 
 -- Dataset Source: Kaggle - Mall Customers Segmentation Data
 -- Visualization inspiration from Seaborn and Matplotlib documentation

 



