
# Customer Segmentation using K-Means Clustering

## Project Overview

This project demonstrates customer segmentation using the K-Means clustering algorithm. The analysis focuses on grouping customers based on their annual income and spending score, which can be valuable for targeted marketing and customer understanding.

## Project Goals

- Segment customers into distinct groups based on their spending and income patterns.
- Visualize and interpret the characteristics of each customer segment.
- Provide actionable insights for targeted marketing strategies and customer relationship management.

## Data Source

The project utilizes a dataset containing customer information, including:

- **CustomerID:** Unique identifier for each customer.
- **Gender:** Customer's gender (Male/Female).
- **Age:** Customer's age.
- **Annual Income (k$)**: Customer's annual income in thousands of dollars.
- **Spending Score (1-100)**: Score assigned to customers based on their spending behavior.

## Methodology

1. **Data Loading and Exploration:**
   - Import the necessary libraries (pandas, numpy, matplotlib, seaborn, sklearn.cluster).
   - Load the customer dataset from a CSV file using pandas.
   - Explore the data structure and characteristics using functions like `info()`, `describe()`, and visualization techniques.

2. **Data Preprocessing:**
   - Handle missing values, outliers, and data type conversions if necessary.
   - Select the relevant features for clustering (Annual Income and Spending Score).

3. **Determining Optimal Clusters:**
   - Apply the Elbow method to find the optimal number of clusters.
   - Fit the KMeans model with varying cluster numbers and calculate inertia scores.
   - Plot the inertia scores and identify the "elbow" point for cluster selection.

4. **K-Means Clustering:**
   - Initialize the KMeans model with the chosen number of clusters.
   - Fit the model to the selected features (Annual Income and Spending Score).
   - Assign cluster labels to each customer in the dataframe.

5. **Cluster Visualization:**
   - Extract cluster centers and plot them on a scatter plot.
   - Visualize the data points, colored by their assigned cluster, using seaborn's `scatterplot`.
   - Enhance the visualization with labels, titles, and a legend.

6. **Cluster Analysis and Interpretation:**
   - Analyze cluster characteristics using descriptive statistics (mean, median, etc.).
   - Compare clusters based on demographics (age, gender) and spending patterns.
   - Interpret the findings to gain insights into customer behavior and preferences.

## Results and Insights

- The analysis reveals distinct customer segments with varying spending and income patterns.
- Each cluster is characterized by a unique combination of age, gender, income, and spending score.
- These insights can inform targeted marketing strategies, customer segmentation, and personalized product recommendations.

## Conclusion

This project demonstrates the effectiveness of K-Means clustering for customer segmentation. The findings provide valuable insights for businesses to understand their customer base and tailor their strategies for better customer engagement and business outcomes.


## Future Enhancements

- Explore alternative clustering algorithms for comparison.
- Incorporate additional customer features for more comprehensive segmentation.
- Develop interactive visualizations for deeper exploration of the clusters.

## Repository Contents

- `customer_segmentation.ipynb`: Google colab Notebook containing the project code and analysis.
- `Mall_Customers.csv`: Dataset used for the analysis.
- `README.md`: This file providing project documentation.

## How to Run

1. Clone the repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open and run the `customer_segmentation.ipynb` notebook using Goole Colab,Jupyter Notebook or JupyterLab .


