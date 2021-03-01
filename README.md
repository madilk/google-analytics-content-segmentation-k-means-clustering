# google-analytics-content-segmentation-k-means-clustering
Website Content Segmentation Via K Means Clustering in R
I did a blog post explaining the same 
https://analyticslog.com/blog/2021/2/20/google-analytics-content-segmentation-via-k-means-clustering-in-r-programming
but the TL;DR version is here:

Main components of this whole R script are:
1. API call to Google Analytics extract data
2. Data wrangling to clean up, group page title data from Google Analytics and prepare the data
3. Prepare distance matrix
4. Compare K-means visually
5. Decide on optimal # of clusters

Wherever I have used help from other sites in working through the solution, I have referenced them, including StackOverflow links.
The main piece on k means (factoextra package) was from here: https://uc-r.github.io/kmeans_clustering 

If you'd like to suggest ways to improve the script [I'm sure there are], feel free to let me know. I'd love to improve my own understanding of R.

Thanks for reading,
Adil
