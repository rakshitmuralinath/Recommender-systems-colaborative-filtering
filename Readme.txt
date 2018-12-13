# Recommender-systems-colaborative-filtering

With the increase in ecommerce and use of internet applications, recommender systems are used in hundreds of algorithms today to suggest products and services to customers and users around the world. There are several online retailers like Amazon, eBay, Netflix and Facebook who vigorously depend on recommender systems in determining similar customers and items that are likely to of interest of given user. Recommendation system helps in filtering the large amount of data generated and provide adequate information which can be used to increase sale or maintain current users’ interests. There are different approaches to implement recommender system like collaborative filtering, content-based filtering, rule-based filtering and hybrid approach. Collaborative filtering gives recommendation based on preference of similar users. Content based approach makes recommendation to user based on items with similar content in user profile or items that user preferred in the past. We are using collaborative filtering approach for building the recommender system for this project and recommend top N book recommendations to the users.

Collaborative filtering predicts user preference by analyzing relationships between different users, finding the most similar users, and suggesting items based on their ratings or preference. We are using collaborative filtering approach on Book crossing dataset to recommend books to users based on preference of similar users. 
The Book crossing dataset is an open source dataset, collected by Cai-Nicolas Ziegler from the Book Crossing community. Book Crossing is an act of leaving a book in public place to be picked up and read by others, who then do the same. The website bookcrossing.com is a free online book club which was founded with the intention to encourage reading. The dataset contains the information about 278,858 users (anonymized but with demographic information) providing 1,149,780 ratings about 271,379 books. 
Data source: http://www2.informatik.uni-freiburg.de/~cziegler/BX/ 
We choose this dataset as it has all the required attributes needed to build a recommender system.  
 
Steps followed and problems to be solved: 
--> Data Cleaning and filtering 
--> Data exploration 
--> Model building- Memory based approach: similarity between different users is calculated using KNN, based on similar users ratings, prediction is made. Build a simple recommender system using the best settings. 
--> Model building- Model based approach: using Single Value Decomposition SVD, and Negative Matrix Factorization machine learning algorithms to determine similarity. 
--> Comparing models 
--> Recommending top 10 items based on best model 
