# Image Segmentation using K Means Clustering - PYTHON PROGRAMMING


In my project, I'm working on image segmentation, a technique that divides an image into multiple parts or segments. This is beneficial as it allows me to focus on significant segments of an image while disregarding areas that lack useful information. The process involves grouping together similar pixels, which results in a detailed and granular understanding of the objects in the image.

For this task, I'm utilizing K-Means Clustering, an unsupervised learning algorithm. This algorithm identifies different classes or clusters in the data based on the similarity of the data. Here's how I'm implementing it:

- I start by deciding on the number of clusters, denoted as 'k'.
- I then randomly assign data points to these k clusters.
- I calculate the center of these clusters.
- I compute the distance of each data point from the center of each cluster.
- Based on these distances, I reassign the data points to the nearest clusters.
- I then calculate the new cluster center.
- I repeat the last three steps until the data points no longer switch clusters, or until I reach a predetermined number of iterations.

Through this method, I'm able to gain a comprehensive understanding of the objects in the image.
