# last-lab
1. Why is this an unsupervised learning problem?

Because the dataset does not include labeled target classes, and the goal is to group similar customers into clusters based on their behavior.

2. Why did we remove the CUST_ID column?

Because it is only an identifier and does not contain behavioral information useful for clustering.

3. Which columns had missing values?

CREDIT_LIMIT and MINIMUM_PAYMENTS.

4. How did you handle the missing values?

I filled the missing values with the mean of each column.

5. Why is scaling important before applying K-Means?

Because K-Means is distance-based, and scaling ensures that all features contribute fairly instead of large-value columns dominating the clustering.

6. Which K value did you choose and why?

I chose K = 4 because it gave a reasonable balance between the elbow method and the silhouette score, and it produced meaningful customer segments.

7. What patterns do you notice in the clusters?

The clusters represent different customer behaviors, such as customers with high balances and purchases, customers with frequent cash advances, and customers with lower overall activity.

8. Did PCA show perfectly separated clusters?

No. The PCA plot did not show perfectly separated clusters, which is normal because the data was reduced from many dimensions into only two components.
