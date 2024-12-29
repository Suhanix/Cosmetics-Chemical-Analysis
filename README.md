# Cosmetic Product Ingredient Analysis and Visualization

This project aims to help consumers make informed decisions about cosmetic products by analyzing their ingredient lists. Specifically, it tackles the challenge faced by individuals with sensitive skin, who find it difficult to interpret the complex ingredient lists found on product packaging. By leveraging data science, this project creates a content-based recommendation system using the chemical components of cosmetics.

## Project Overview

Buying cosmetic products can be daunting, especially for those with sensitive skin. The ingredient lists on cosmetic packaging often seem incomprehensible unless you have a background in chemistry. This project uses data science to provide a solution by analyzing the chemical components of cosmetic products and visualizing ingredient similarities.

The steps involved in the project include:
- **Processing Ingredient Data**: A dataset of 1,472 cosmetic products from Sephora is processed, focusing on the ingredient lists.
- **Dimensionality Reduction**: A machine learning method called t-SNE is used to reduce the high-dimensional ingredient data into a two-dimensional space for visualization.
- **Interactive Visualization**: Bokeh is used to create an interactive scatter plot that allows users to explore products with similar ingredients.

By doing this, the project provides a scientific approach to selecting cosmetic products, which can help individuals with specific skin concerns choose products that may be best suited for them.

## Features

- **Data Preprocessing**: Filters and tokenizes ingredient lists to prepare the data for analysis.
- **Dimensionality Reduction with t-SNE**: Reduces complex ingredient data into a 2D space to make it easier to compare products visually.
- **Interactive Visualization with Bokeh**: Displays the reduced ingredient data as an interactive scatter plot, allowing users to explore product similarities based on their ingredients.
- **Ingredient Similarity Analysis**: Uses the proximity of products in the scatter plot to determine their ingredient similarities.

## Technologies Used

- **Python**: Programming language used for implementing the project.
- **Pandas**: Library used for data manipulation and cleaning.
- **NumPy**: Used for numerical computations, especially in matrix operations.
- **Scikit-learn**: Implements t-SNE for dimensionality reduction.
- **Bokeh**: Interactive visualization library used to display the data and allow users to explore the results.

## Dataset

The dataset used in this project consists of ingredient lists from 1,472 cosmetic products sourced from Sephora. The data is processed and tokenized, and each product's ingredients are analyzed for similarities using dimensionality reduction techniques.
