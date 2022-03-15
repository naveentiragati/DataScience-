# ICP-6

#### Complete the following:
```
Name: Naveen Tiragati
Email: ntdpm@umsystem.edu
```
---
```
Partner Name: Sunny Sood 
Partner Email: sks6nv@umsystem.edu
Partner ICP-Link: https://github.com/UMKC-APL-PythonDeepLearing/icp_6-SunnySood80
```

```
Video Link: (if not submitting in class)
```
### SUBMIT PYTHON NOTEBOOK FILE (ipynb files)

<br/>
 
# Write brief explanation here:

<h1> house dataset </h1>

 - We learned how to exlpore the data and it's atribute fields using the <b>describe()</b> function
 - We then started preproccessing on the data:
         1. We checked for skewness of our target feature and learned how to use the <b> log() </b> function on <b> SalesPrice </b> and brought down the skewness to <b> 0.1 </b>
         2. We found the most positive and most negative correlation in our dataset and learned how to use the <b> corr() </b> funcntion to do so.
         3. We then found that our data contains NULL values, and we learned to handle them using the <b> interpolate() </b> function for numeric values
         4. We then learned how to wrangle the non-numeric features, for street type we changed the non-numeric features to numeric features by replacing the type with 1 or 2, then for RoofStyle we learned how to convert the non-numeric features to numeric features using the <b> astype() </b> function, finally for kitchenQuality we learned how to use <b> LabelEncoder </b> to convert from non-numeric to numeric
-  We then did a scatter plot of <b> GarageArea </b> & <b> SalesPrice </b> and found some <b> anomolies </b> then we cut off those outliers in our data
-  We then did a <b> train_test_split() </b> on our dataset
-  We then learned how to create a linear regression model and we learned how to plot the regression line between two features
-  We learned how to apply <b> PCA (Principal component analysis) </b> on the top 5 most positive correlated features against our target <b> SalesPrice </b>
-  We then evaluated our regression model after applying <b> PCA </b> and we learned how to find our <b> MAE (using mean_absolute_error), MSE (using mean_sqaured_error), RMSE (using mean_sqaured_error) & R2 SCORE (using r2_score) </b>

<h1> credit card dataset </h1>

 - We learned how to remove the NULL values in our dataset by replacing the NULL values with the mean using <b> fillna </b>
 - We then learned how to use the elbow method to find a good number of clusters with the k-means algortihm by the <b> kMeans() </b> function and found that 3 is the optimal number of clusters for our dataset
 - We learned to calculate the silhouette score using <b> silhouette_score </b> and found a score of <b> 0.46 </b>
 - We learned how to do feature scaling on our data using <b> standardScaler </b> and then applied our K Means algorithm on our sccaled data, then found a new sihlouette score of <b> 0.34 </b>
 - We then applied PCA on our feature scaled dataset, and applied K Means algorithm and calculated a new sihlouette score of <b> 0.45 </b>
 - we then visualized the clustering of our dataset.
