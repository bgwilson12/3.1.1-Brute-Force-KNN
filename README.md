# 3.1.1-Brute-Force-KNN (and 3.1.2 Drill!!!!)
In this assignment, I will build a simple brute force k-nearest neighbors classifier.


3.1.2 DRILL!!!! ATTENTION!!! I'm adding the 3.1.2 drill assignment to this readme. Thanks, and sorry for yelling.

We could use the four spending categories to set up a four dimensional space, and map each person's spending onto that space. Since this is supervised learning, we would have a binary class indicating if the individual pays their bills on time or not. This "on_time" variable will be the class we are attempting to classify. Our classifier would then find the euclidian distance of a new point to all other points, and give us the closest "n" individuals. These "n" individuals would be counted, and their votes could be scaled based on how far away they are.

Since this is in 4-dimensional space, it would be difficult to visualize the clusters of points and should maybe only be used as a baseline test for other, more powerful algorithms.
