# -Customer-Segmentation-using-K-Means-Algorithm
## Abstract
Customer segmentation is a separation of a market into multiple distinct groups of consumers who share the similar characteristics. Segmentation of market is an effective way to define and meet customer needs and gain lot of profit in the business world .We  use machine learning techniques and algorithms. Here, The customer segmentation using K-Means clustering helps to group the data with same attributes which exactly helps to business the best. We are going to use elbow method to find the number of clusters and at last we visualize the data.

 ## Introduction
Nowadays the competition is vast and lot of technologies came into account for effective growth and revenue generation. For every business the most important component is data. With the help of grouped or ungrouped data, we can perform some operations to find customer interests. 
Customer Segmentation is useful to divide the large data from dataset into several groups based on their age, demographics, spent, income, gender, etc. These groups are also known as clusters. By this, we can get to know that, which product got huge number of sales and which age group are purchasing etc. And, we can supply that product much for better revenue generation. 
Initially we are going to take  the old data. As we know that old is gold so, by using the old data we are going to apply K-means clustering algorithm and we have to find the number of clusters first. So, at lastly, we have to visualize the data. One can easily find the potential group of data while observing that visualization. 
Customer Segmentation depends on some factors or variables. Those square measure divided into four sorts as given below:
1)Geographic→ like location, population, density, climate.
2)Behavioral→ like previous purchases, payment ways used.
3)Demographics→ like age, gender, marital standing, annual financial gain, educational level, occupation.
4)Lifestyle→ like social values, community affiliations.
We have several blessings of client segmentation like ready to determine the foremost valuable and potential customers, we can higher the client service, we can improve revenue, and scale back the wastage of cash.
## Advantages of Customer Segmentation
•	Determine appropriate product pricing.
•	Develop customized marketing campaigns.
•	Design an optimal distribution strategy.
•	Choose specific product features for deployment.
•	Prioritize new product development efforts.
    ## The Challenge
You are owing a supermarket mall and through membership cards, you have some basic data about your customers like Customer ID, age, gender, annual income and spending score. You want to understand the customers like who are the target customers so that the sense can be given to marketing team and plan the strategy accordingly.
     K-Means Clustering
K-Means Clustering is an unsupervised learning algorithm that is used to solve the clustering problems in machine learning or data science. Unsupervised algorithms make inferences from datasets using only input vectors without referring to known, or labelled, outcomes.
The objective of K-means is simple: group similar data points together and discover underlying patterns. To achieve this objective, K-means looks for a fixed number (k) of clusters in a dataset.
A cluster refers to a collection of data points aggregated together because of certain similarities.


 ## IMPLEMENTATION
In this project, we tend to use python language with Online Google Colabatory In machine learning, we’ve got unsupervised learning. We implement the client segmentation exploitation k-means cluster algorithmic program.
To implement the client segmentation first, we must always import the required libraries and modules into the Google Colab.Read the information set as ‘df’ and that we perform some data visualization operations like shape() for knowing the number of rows and columns, info() for obtaining the main points of dataset attributes, and displaying the primary five rows with head().
A count plot() technique is employed on gender attributes that show the counts of observations in every categorical bin using bars. A pair plot permits us to see both distributions of single variables and relationships between two variables. Like that we tend to perform several operations like plots, graphs, etc. Later performing various data visualization operations, Now we focus on the k-means clustering algorithm.
  K-Means Clustering 
•	K Means algorithm in an iterative algorithm that tries to partition the dataset into K predefined distinct non overlapping sub groups which are called as cluster.
•	Here K is the total no of clusters.
•	Every point belongs to only one cluster.
•	Clusters cannot overlap.
 Steps of Algorithm
•	Arbitrarily choose k objects from D as the initial cluster centers. 
•	Repeat.
•	Assign each object to the cluster to which the object is the most similar, based on the mean value of the objects in the cluster. 
•	Update the cluster means, i.e. calculate the mean value of the objects for each cluster.
•	Until no change.
## Data
This project is a part of the Mall Customer Segmentation Data competition held on Kaggle. The dataset can be downloaded from the Kaggle website.
  Environment and tools
•	scikit-learn
•	seaborn
•	numpy
•	pandas
•	matplotlib
  
 ## Conclusion
From the above visualization it can be observed that Cluster 1 denotes the customer who has high annual income as well as high yearly spend. Cluster 2 represents the cluster having high annual income and low annual spend. Cluster 3 represents customer with low annual income and low annual spend. Cluster 5 denotes the low annual income but high yearly spend. Cluster 4 and cluster 6 denotes the customer with medium income and medium spending score.
## REFERENCES
[1] I. S. Dhillon and D. M. Modha, “Concept decompositions for large 
sparse text data using clustering,” Machine Learning, vol. 42, issue 1, 
pp. 143-175, 2001. 
[2] T. Kanungo, D. M. Mount, N. S. Netanyahu, C. D. Piatko, R. 
Silverman, and A. Y. Wu, “An efficient K-means clustering 
algorithm,” IEEE Trans. Pattern Analysis and Machine Intelligence, 
vol. 24, pp. 881-892, 2002. 
[3] MacKay and David, “An Example Inference Task: Clustering,” 
Information Theory, Inference and Learning Algorithms, Cambridge 
University Press, pp. 284-292, 2003. 
[4] Jiawei Han, Micheline Kamber, Jian Pei “Data Mining Concepts and Techniques”, Third Edition. 
[5] D. Aloise, A. Deshpande, P. Hansen, and P. Popat, “The Basis Of Market Segmentation” 
Euclidean sum-of-squares clustering,” Machine Learning, vol. 75, pp. 
245-249, 2009. 
[6] S. Dasgupta and Y. Freund, “Random Trees for Vector Quantization,” 
IEEE Trans. on Information Theory, vol. 55, pp. 3229-3242, 2009. 
[7]Puwanenthiren Premkanth, ―Market Segmentation and Its Impact on Customer Satisfaction with Especial Reference to Commercial Bank of Ceylon PLC.‖ Global Journal of Management and Business Research Publisher: Global Journals Inc. (USA). 2012. Print ISSN: 0975-5853. Volume 12 Issue 1

