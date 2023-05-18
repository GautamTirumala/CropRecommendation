# CropRecommendation
This is part of my major project in BTech. The main aim of this project is to help farmers now which crop can be best to grow
in there fields, considering the chemicals and other parameters of soil.

In this project we consider 7 parameters they are :
- Nitrogen
- phosphorus
- pottasium
- Average Rainfall
- Average Temparature
- Humidity
- PH Level of soil

The dataset which you see crop.xlsx is taken from Kaggel.

This project uses ***KNN*** algorithm to identify the most nearest crop.
Working of KNN algorithm is as follows :



How does K-NN work?

The K-NN working can be explained on the basis of the below algorithm:

- Step-1: Select the number K of the neighbors

- Step-2: Calculate the Euclidean distance of K number of neighbors

- Step-3: Take the K nearest neighbors as per the calculated Euclidean distance.

- Step-4: Among these k neighbors, count the number of the data points in each category.

- Step-5: Assign the new data points to that category for which the number of the neighbor is maximum.

- Step-6: Our model is ready.

for more detail explanation of KNN Algorithm visit
https://www.javatpoint.com/k-nearest-neighbor-algorithm-for-machine-learning
