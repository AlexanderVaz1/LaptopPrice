# LaptopPrice
Laptop Price Analysis - Data Science Individual Project
Project Overview
This project explores the factors that influence laptop prices using multiple datasets. The goal is to uncover patterns and relationships between laptop specifications (such as RAM, CPU brand, GPU, screen size, and storage types) and their impact on pricing. The analysis leverages regression, clustering, and visualization techniques to provide insights that could benefit consumers, retailers, or manufacturers.

Objectives
Understand how different hardware features affect laptop price.

Identify which brands and specs are most strongly associated with high or low price points.

Group laptops into price tiers using clustering.

Explore relationships between key features like CPU, GPU, and screen resolution.

Tools & Methods
Libraries used: Pandas, Seaborn, Matplotlib, Scikit-learn

Techniques:

Data Cleaning & Feature Engineering

Regression Modeling

Clustering (KMeans)

Visual Analysis (boxplots, heatmaps, pairplots)

Datasets
Three datasets (df1, df2, df3) were used, each containing different combinations of laptop specs and prices. Columns include company, RAM, weight, GPU brand, storage types (SSD, HDD), screen resolution, CPU details, and price in euros.

Summary of Findings
RAM, SSD size, and CPU brand are strong predictors of price.

Apple and gaming-focused brands tend to have higher price averages.

KMeans clustering revealed natural groupings of laptops by price tier.

Visualizations helped confirm and communicate these patterns clearly.

Future Work
Future improvements could include:

Applying classification to predict price ranges

Incorporating real-time market data for more current insights

Using deep learning models for more complex feature interactions
