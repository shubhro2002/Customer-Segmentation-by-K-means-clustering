# Mall Customer Segmentation Using K-Means Clustering

## Objective
The objective of this project is to segment customers of a mall into distinct groups based on their demographic and spending behavior, enabling targeted marketing strategies and personalized customer experiences.

## Dataset
The dataset used for this project is the "Mall Customer Segmentation Data," which includes the following columns:
- **CustomerID**: Unique ID assigned to each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned by the mall based on customer behavior and spending nature.

## Steps Involved

### 1. Data Exploration and Preprocessing
- Loaded and inspected the dataset for initial understanding.
- Checked for and handled any missing values.
- Encoded categorical variables (Gender) and scaled numerical features (Age, Annual Income, Spending Score) using `StandardScaler`.

### 2. Exploratory Data Analysis (EDA)
- Performed EDA to understand the distribution of features and relationships between them.
- Visualized the distribution of age, annual income, and spending scores using histograms and KDE plots.
- Analyzed the correlation between features using a heatmap.
- Examined the presence of outliers using boxplots.

### 3. K-Means Clustering
- Determined the optimal number of clusters using the Elbow Method and Silhouette Score.
- Chose 5 clusters as the optimal number based on these evaluations.
- Applied K-Means clustering to the preprocessed data and assigned cluster labels.

### 4. Cluster Analysis
- Mapped the cluster labels back to the original dataset.
- Analyzed each cluster by computing statistics (mean, median) for age, annual income, and spending scores.
- Visualized the spending score distribution for each cluster.

### 5. Visualization
- Reduced the dimensionality of the data using PCA and visualized the clusters in 3D space.
- Created insightful visualizations to highlight the characteristics of each cluster.

## Findings
The analysis revealed distinct customer segments with unique characteristics. For instance:
- **Cluster 0**: Mean age is around 25 and gender is predominantly female. Low annual income, high spending
- **Cluster 1**: Mean age is around 56 and gender is predominanntly female. Moderate annual income, moderate spending
- **Cluster 2**: Mean age is around 41 and gender is predominantly male. High annual income, low spending
- **Cluster 3**: Mean age is around 27 and gender is predominantly female. High annual income, moderate spending
- **Cluster 4**: Mean age is around 32 and gender is predominantly female. High annual income, high spending
- **Cluster 5**: Mean age is around 45 and gender is perdominantly female. Low annual income, low spending

## Conclusion
This project demonstrates the effective use of K-Means clustering for customer segmentation, enabling businesses to understand their customers better and devise targeted marketing strategies. The comprehensive analysis and visualization provide actionable insights that can help improve customer satisfaction and business performance.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- PCA for dimensionality reduction

## Project Structure
- `Mall_Customers.csv`: The original dataset.
- `Preprocessed_Mall_Customers.csv`: The preprocessed dataset.
- `Mall_Customer_Segmentation.ipynb`: Jupyter notebook containing the full analysis.
- `README.md`: Project description and instructions.

This project showcases my ability to handle real-world data, perform advanced analytics, and derive meaningful insights, making it a valuable addition to my data science portfolio.
