Detailed explanation of K-means algorithm steps

Selection of step1.k value

The choice of K is generally determined according to the actual needs, or the value of K is directly given when implementing the algorithm.

Step 2. distance measurement

The nearest neighbor measurement strategy is required to divide the object points into the cluster closest to the cluster center. The Euclidean distance is used in the Euclidean space, the cosine similarity function is used in the processing of documents, and sometimes Manhattan distance is also used as the measurement. The measurement formula used in different situations is different.

Step3. Calculation of new centroid

For the K clusters generated after classification, calculate the point with the smallest mean distance from other points in the cluster as the centroid (for clusters with coordinates, calculate the mean value of each cluster coordinate as the centroid)

Step4. Stop K-means

The centroid is no longer changed, or given the maximum number of loops, looplimit
