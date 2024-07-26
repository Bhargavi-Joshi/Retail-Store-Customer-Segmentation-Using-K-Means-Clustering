# Retail-Store-Customer-Segmentation-Using-K-Means-Clustering

This project focuses on segmenting customers of a retail store using the K-Means clustering algorithm. By leveraging customer data, including purchase history and demographic information, we aim to identify distinct customer groups. These segments can then be used to tailor marketing strategies and improve customer relationship management.

## Dataset Description

The dataset used in this project contains transactional records from a retail store. Key attributes include:
- **Invoice Number**: Unique identifier for each transaction.
- **Stock Code**: Unique identifier for each product.
- **Description**: Description of the product.
- **Quantity**: Number of units purchased.
- **Invoice Date**: Date of the transaction.
- **Unit Price**: Price per unit of the product.
- **Customer ID**: Unique identifier for each customer.
- **Country**: Country where the customer resides.


## Methodology

1. **Data Collection**: Collecting data on customers' purchase history and demographics.
2. **Data Cleaning and Preprocessing**: Handling missing values, outliers, and creating new features such as `TotalCost`.
3. **Feature Engineering**: Extracting relevant features for clustering.
4. **Defining the Number of Clusters**: Using the Silhouette Score to determine the optimal number of clusters.
5. **K-Means Clustering**: Applying the K-Means algorithm to segment the customers.
6. **Evaluation and Interpretation**: Analyzing the resulting clusters to identify distinct customer segments.


## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter


## Usage

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/Retail-Store-Customer-Segmentation.git
   cd Retail-Store-Customer-Segmentation
   ```
2. **Install Dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebooks**:
   Open and run the `customer-segmentation.ipynb` and `exploratory-data-analysis.ipynb` notebooks to reproduce the results.


## Results

- **Customer Segmentation**: Customers were classified into distinct clusters based on their purchase behavior and demographics.
- **Visualization**: t-SNE visualization was used to display the clusters.
- **Model Accuracy**: Various models were tested for customer classification, with Random Forest achieving the highest accuracy.

  
## Authors

Developed by:
- **Bhargavi Joshi** - bhargavijoshi86@gmail.com
- **Pranjal Gautam** - pranjalgautam1103@gmail.com
