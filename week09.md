# Visual Analytics for Comparing the Impact of Outliers in `k-Means` and `k-Medoids` Algorithm

Author: *Kanika, Kanchan Rani, Sangeeta, Preeti*

Link: https://ieeexplore.ieee.org/abstract/document/8701355


This paper compares the performance of clustering algorithms - `kMeans` and `kMedoids` - in the presence of outliers using the `iris` dataset. An interactive web application with visual analytics is developed to display the impact of outliers on these clustering algorithms. The application can be accessed through an internet browser using `Shiny`, providing better insight into the algorithms' performance.
`kMeans` is sensitive to outliers, while `kMedoids` uses medoids, the most centrally located values in cluster, making it less affected by outliers.

## Some contributions:
1. Comparison of kMeans and kMedoids.
2. Development of an interactive web application.
3. Evaluation using `iris` dataset.

## Results:
1. The web application demonstrates that kMedoids is less affected by outliers compared to kMeans.
2. Using the web apps, users can access the results of clustering in the form of an interactive Google bubble chart. Each data value can be accessed by moving the cursor over the data point.
3. The iris dataset is used for evaluation, and it is found that certain attributes, such as petal length and petal width, play an important role in accurately classifying the iris data.

## User Interface
![image](https://github.com/avivnur/reflections-research/assets/47585222/c980f788-0bb2-40e1-9536-79e1093b5c9f)

## KMeans
![image](https://github.com/avivnur/reflections-research/assets/47585222/fc4eb393-0d2e-4ef8-8e76-97eea7803c07)

## KMeans and outliers detection
![image](https://github.com/avivnur/reflections-research/assets/47585222/135b55e1-8953-4714-ae53-194ef066d06a)

## KMeans and after removal of outliers
![image](https://github.com/avivnur/reflections-research/assets/47585222/5f888593-4463-4336-a885-4656c6e78c47)

## KMedoids
![image](https://github.com/avivnur/reflections-research/assets/47585222/3009852c-1879-4d8c-b432-d2b2705a803c)

## KMedoids and outliers detection
![image](https://github.com/avivnur/reflections-research/assets/47585222/62f43436-c1ee-443b-a0a9-85b019be5df1)

## KMedoids and after removal of outliers
![image](https://github.com/avivnur/reflections-research/assets/47585222/502a1423-6c03-4e0f-bd25-6e0b1cb25a43)

## Accuracy Comparison
![image](https://github.com/avivnur/reflections-research/assets/47585222/b3e06f8d-82cb-46e8-97c1-96abb345bcab)

## References
Kanika, K. Rani, Sangeeta and Preeti, "Visual Analytics for Comparing the Impact of Outliers in k-Means and k-Medoids Algorithm," 2019 Amity International Conference on Artificial Intelligence (AICAI), Dubai, United Arab Emirates, 2019, pp. 93-97, doi: 10.1109/AICAI.2019.8701355. keywords: {Clustering algorithms;Iris;Anomaly detection;Visual analytics;Machine learning algorithms;Classification algorithms;User interfaces;clustering;k-means;k-medoids;outliers;visual analytics},
