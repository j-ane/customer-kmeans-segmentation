# customer-kmeans-segmentation

A local fast casual restaurant is interested in expanding their business with a new store in the area. The decision alternatives for this analysis are whether to expand in one of two locations or not to open at either location and look into other options. The restaurant issued two surveys, one to customers and another to non-customers located in each of the potential new locations.

K-means segmentation was performed on the customer survey data to identify distinct clusters based on their survey responses. However, the k-means applied to the original data didn’t come up with interpretable results that could initiate store-opening strategies from. Alternatively, a factor analysis narrowed down the dimensions of clustering analysis in an effort to identify a clearer interpretation of the results. The scree plot indicated that three components is the proper amount for our factor analysis. After transforming the selected variables with three factors, we ran a k-means clustering algorithm again and successfully identified three segments for our customers.

After analyzing each cluster's factor importance (or sorted attributes) and looking at the demographic distribution, the three clusters can be identified as the following: <br>
- Cluster 1 (Cheap Eaters): Mid-to-low income millennials with no family <br>
- Cluster 2 (Health Seekers): Middle-aged, higher income females with a family (most likely Moms) <br>
- Cluster 3 (Value Seekers): Young, mid-to-low income males without a family (most likely students or young workers)

For non-customers surveyed at the potential locations, crosstabulation tables investigated how non-customers perceived the importance of healthy food, value provided, and convenience. Based on the segmentation analysis, the optimal choice to open the new location would be in area 2. 
