User Behavior Analysis with Clustering and Predictive Modeling

Overview
This project aims to analyze user behavior by employing clustering techniques and predictive modeling. By examining various user engagement metrics, we can gain insights into how different user groups interact with the platform and predict their likelihood of making virtual merchandise purchases.
The dataset includes various metrics related to user engagement, such as:

Fan Challenges Completed
Predictive Accuracy (%)
Virtual Merchandise Purchases
Sponsorship Interactions (Ad Clicks)
Time on Live 360 (mins)
Real-Time Chat Activity (Messages Sent)
Technologies Used

Python: The primary programming language used.
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Matplotlib and Seaborn: For data visualization.
Scikit-Learn: For machine learning, including clustering and predictive modeling.

Clustering Analysis
K-Means clustering is applied to group users based on their engagement metrics. The data is first standardized to ensure that the clustering algorithm works effectively. A scatter plot is generated to visualize the clusters, helping to identify patterns in user behavior.

Predictive Modeling
A logistic regression model is developed to predict the likelihood of users making virtual merchandise purchases based on engagement metrics. The model is trained on a portion of the data and evaluated on a test set, providing insights into its accuracy.
Insights and Visualizations

The project includes various visualizations, such as:
Heatmaps to analyze the correlation between metrics.
Scatter plots to visualize user clustering.
Bar plots to showcase predictive accuracy against merchandise purchases.

To run:
Clone the repository.
Ensure you have the required libraries installed. You can install them using:
Copy code: pip install numpy pandas matplotlib seaborn scikit-learn

Place your dataset in the specified path in the script.
Run the script to perform analysis and visualize the results.

Conclusion
This analysis provides valuable insights into user behavior and engagement on the platform, guiding future strategies for enhancing user experience and increasing merchandise purchases.
