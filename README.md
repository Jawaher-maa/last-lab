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

7. Based on the cluster summary table, describe each customer segment in your own words.
High-value customers, cash-advance-heavy customers, low-activity customers, and moderate customers.

8. Which cluster may represent high-value customers?
The cluster with the highest balance, purchases, and credit limit.

9. Which cluster may represent customers who rely more on cash advance?
The cluster with the highest cash advance values and cash advance frequency.

10. How can a company use these clusters for marketing strategy?
The company can give each group different offers, such as rewards for high-value customers and promotions to increase activity for low-usage customers.

