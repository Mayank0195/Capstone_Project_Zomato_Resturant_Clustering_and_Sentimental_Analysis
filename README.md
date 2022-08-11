# Capstone_Project_Zomato_Resturant_Clustering_and_Sentimental_Analysis

## Problem Statement:

Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato
provides information, menus, and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.
The Project focuses on Customers and companies, you have to analyze the sentiments of the reviews given by the customer in the data and make some useful conclusions in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is visualized as it becomes
easy to analyze data in an instant. The Analysis also solves some of the business cases that can directly help the customers find the Best restaurant in their locality and for the company to grow up and work in the fields they are currently lagging in.
This could help in clustering the restaurants into segments. Also, the data has valuable information about cuisine and costs which can be used in cost vs. benefit analysis
Data could be used for sentiment analysis. Also, the reviewers' metadata can be used to identify the industry's critics.

## Approach:

The approach followed here is to first check the sanctity of the data and then understand the features involved. The events followed were in our approach:

●	Understanding the business problem and the datasets

●	Data cleaning and preprocessing- Both datasets required little cleaning; all that was required was to remove certain null values, convert values to acceptable data types, and select only the most significant features. Features like Link, Collections, and Timing, for example, don't help distinguish across instances.

●	Feature Engineering: 
The process of selecting, modifying, and transforming raw data into meaningful numerical features that machine learning algorithms can exploit is known as feature engineering. 

●	Exploratory data analysis- of categorical and continuous variables against our target variable.

●	Restaurant Clustering: Clustering is done based on the two approaches 
1.	K-mean 
2.	Principal Component Analysis
3.	
●	Sentiment Analysis: Sentiment analysis is done using a different machine learning model. The selected model should be able to predict a False positive that is the sentiment is actually negative but the model predicted it as a positive one.

## Conclusion:

Clustering is the process of identifying unique groupings or "clusters" within a data set. The program constructs groups using a machine language algorithm, and items in a comparable group will have similar features in general.
One of the challenges that organizations have is figuring out how to arrange the massive volumes of data accessible into usable structures. Alternatively, divide a large heterogeneous group into smaller homogenous groupings. Cluster analysis is an exploratory data analysis tool that seeks to group things so that the degree of relationship between two objects is greatest if they belong to the same group and minimal if they don't.
This enables businesses to assist their clients in quickly locating the information they require. This analysis included all of the essential subjects in both the business and technological domains.
Some important insights to draw from the analysis include:

●	The best restaurants in Hyderabad are
AB's - Absolute Barbecues, B-Dubs, and 3B's - Buddies, Bar & Barbecue.

●	The most popular cuisines are the cuisines that most of the restaurants are willing to provide. The most popular cuisines in Hyderabad are North Indian, Chinese,
Continental, and Hyderabadi.

●	The restaurants in Hyderabadi have a flexible per person cost of 150 INR to 2800 INR. The cheapest is the food joint called Mohammedia Shawarma and the costliest restaurant is Collage - Hyatt Hyderabad Gachibowli.

●	Upon conducting a basic cost-benefit analysis on Zomato with a few
assumptions one basis of the little business understanding that could be gathered, it can be concluded that it is important to separate out the restaurants with the lowest rating in order to improve its overall customer experience. These restaurants were small food joints or restaurants with high prices according to the food they were serving. Efforts should
be made to advertise more and analyze the reviews, especially for these restaurants, and work on them. Mohammedia Shawarma seems to be profitable.

●	Restaurant Clustering was done in two approaches. First with just two features and then with all of them. K means
Clustering worked well in the first approach but as we increase the
dimensions, it isn't able to distinguish the clusters hence principal component
analysis was done and then clustered into 6 clusters. The similarities in the data points within the clusters were pretty great.

●	Critics in the Industry were identified by grouping the customers with a good number of followers who have given more reviews with constantly low ratings. Sumit, D.S, and Ram Raju are the top three critics.

●	Sentiment Analysis was done on the reviews and a model was trained in order to identify negative and positive
sentiments. Even though the number of false negatives is lower in the case of Multinomial NB and Logistic Regression than in Light GBM, it is performing better in terms of   reducing False positives. This indicates that Multinomial NB and Logistic Regression is penalizing False positives more just as we want.

## Challenges:

●	Because the data was provided in a raw format in string format, the project's main problem was extracting key information from the dataset in numerical form.

## Recommendations:

●	Negative reviews should be approached to reach a win-win solution.

●	Ratings should be gathered according to categories, such as packing, delivery, taste, quality, amount, and service. This would aid in identifying and addressing lagging fields.

