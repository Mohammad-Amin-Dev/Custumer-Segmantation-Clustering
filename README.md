# 🛍️ Customer Segmentation using Clustering

[![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange.svg)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)

An unsupervised machine learning project to segment customers into distinct groups based on their characteristics. This repository applies clustering techniques to a customer dataset, enabling targeted marketing strategies and personalized customer insights.

---

## 📌 Overview

This project focuses on **customer segmentation**, a crucial task for businesses to understand their audience. By identifying groups with similar behaviors or profiles (like spending habits or income), companies can tailor products, services, and marketing campaigns more effectively. The analysis is performed using clustering algorithms on a provided customer dataset.

## 📂 Repository Structure
Custumer-Segmantation-Clustering/
│
├── main.ipynb # Main Jupyter Notebook with full clustering analysis
├── customer_segmentation.csv # The primary dataset for customer segmentation
├── .gitignore # Specifies intentionally untracked files
└── README.md # Project documentation (you are here)
📊 Dataset

The file customer_segmentation.csv contains the customer data used for this analysis. While the exact columns are best viewed in the notebook, typical features for such a project often include:
- Id : Unique identifier for each customer .

- Year_Birth : The birth of each customer . 

- Education : The highest level of education each customer .
##### !!! After label encodeing >> (2n Cycle = 0 , Basic = 1, Graduation = 2, Master = 3, PhD = 4)

- Marital_Status : The marital status of the customers . 

- Income : The annual income of the customers . 

- Kidhome : The number of young children in the household . 

- Teenhome : The number of teenagers in the household .

- Dt_Customer : The date when the customer was first enrolled or became a part of the company's database .

- Recency : The number of days since the last purchase or interaction . 

- MntFruits : The amount spent on fruits .

- MntMeatProducts : The amount spent on meat products .

- MntFishProducts : The amount spent on fish products .

- MntSweetProducts : The amount spent on sweet products .

- MntGoldProducts : The amount spent on gold products .

- NumDealsPurchases : The number of purchases made with a discount or as part of a deal .

- NumWebPurchases : The number of purchases made through the company's website .

- NumCatalogPurchases : The number of purchases made through catalogs .

- NumStorePurchases : The number of purchases made in physical stores .

- NumWebVisitsMonth : The number of visits to the company's website in a month .

- AcceptedCmp3 : Binary indicator (1 or 0) whether the individual accepted the third marketing campaign .

- AcceptedCmp4 : Binary indicator (1 or 0) whether the individual accepted the fourth marketing campaign .

- AcceptedCmp5 : Binary indicator (1 or 0) whether the individual accepted the fifth marketing campaign .

- AcceptedCmp1 : Binary indicator (1 or 0) whether the individual accepted the first marketing campaign .

- AcceptedCmp2 : Binary indicator (1 or 0) whether the individual accepted the second marketing campaign .

- Complain : Binary indicator (1 or 0) whether the individual has made a complaint .

- Z_CostContact : A constant cost associated with contacting a customer .

- Z_Revenue : A constant revenue associated with a successful campaign response .

- Response : Binary indicator (1 or 0) whether the individual responded to the marketing campaign .

(Note: This table is a common example. Please update the features based on the actual columns present in your customer_segmentation.csv file.)
📈 Results & Key Insights

(This section should be updated with your specific findings from main.ipynb.)

    Optimal Number of Clusters (K): Based on the Elbow Method, K = [e.g., 5] clusters were identified as optimal.

    Segment Profiles:

        Cluster 0 (e.g., "High Income, Low Spend"): Description of their characteristics.

        Cluster 1 (e.g., "Average Income, Average Spend"): Description.

        Add profiles for all your identified clusters.

    Visualization: The notebook includes 2D/3D scatter plots showing the distinct customer segments.

🔮 Future Work

    Experiment with other clustering algorithms (e.g., Hierarchical Clustering, DBSCAN).

    Apply dimensionality reduction techniques like PCA (Principal Component Analysis) for better visualization.

    Build a simple recommendation system based on the identified segments.

    Deploy the segmentation model as a small web application or API.

🤝 Contribution

Contributions are welcome! To contribute:

    Fork the repository.

    Create a new branch (git checkout -b feature/improvement).

    Commit your changes (git commit -m 'Add some feature').

    Push to the branch (git push origin feature/improvement).

    Open a Pull Request.

📜 License

This project is open source and available under the MIT License.
(Note: It is recommended to add a LICENSE file to your repository.)
📬 Contact

Developer: Mohammad-Amin-Dev
Project Link: https://github.com/Mohammad-Amin-Dev/Custumer-Segmantation-Clustering
