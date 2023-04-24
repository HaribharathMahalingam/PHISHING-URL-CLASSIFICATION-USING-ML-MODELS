# PHISHING-URL-CLASSIFICATION-USING-ML-MODELS
Performed data collection of 11000+ phishing URLs and cleaned them for data analysis using Python and machine learning techniques.  Trained Machine learning models like Logistic Regression, KNN, Decision Trees, Random Forest, and SVM classifiers. The best-performing model based on accuracy and important features influencing the models were found

INTRODUCTION:
Right from the birth of the modern era internet, people have had the opportunity to go to any website available and do as they like, but is it always safe to do so? Attacks on internet users have increased alarmingly and scams have become a common practice now. We all know someone known to us as being scammed using phishing websites or links. Phishing generally means performing a fraudulent task on anyone over the internet, text, or calls. Etc., mainly to collect sensitive information or lure money. Scammers will send you emails or texts to deceive you into providing them with your personal and financial information. They could be able to access your bank, email, and other accounts if they manage to obtain such information. Alternatively, they could sell your information to other scammers. Every day, scammers carry out tens of thousands of such phishing assaults, many of which are successful.

My specific questions are
•	How do we know whether a website URL we receive over my email, SMS, or any form is legitimate? 
•	Can we predict a suspicious URL just by looking at it and not visiting it?
•	What attributes from a URL can tell me that it is a phishing website? 
•	How does every URL text play an important role in determining its authenticity?
All these questions lead to finding a single dataset that has several samples of genuine and not genuine website URLs with features that define an authentic one.   


INFORMATION IN THE DATASET & STRUCTURE OF DATA:
•	There are a total of 11055 rows, where 6157 are legitimate URLs and 4898 are phishing websites.
•	This almost gives us 55% of good websites and 45% of bad websites. 
•	Each of these URLs has been collected from various sources like the PhishTank archive, Google search engine, and MillerSmiles archive. 
•	The last column “class” is the classification column. It has two values, -1 for phishing websites and 1 for legitimate websites.
•	The dataset can be used as a .csv or .txt file and the size is around 1.66 MB.
•	This dataset can be used to develop a binary classification model classifying if an URL is phishing or not.

DATA CLEANING FOR ANALYSIS:
Some of the problems that a dataset has to deal with are specified below,
•	Human error
•	Data overload
•	Incorrect data attribution
•	Missing or inaccurate data
•	Data duplication


The data was fairly clean and didn’t require hard cleaning. Now, that the data is clean and ready for analysis, the dataset can be used for exploring, analyzing, and visualizing different aspects of the dataset.

DATA ANALYSIS:

![image](https://user-images.githubusercontent.com/54590466/234070167-f231b1cd-450d-4de5-93ee-ab18075a02f0.png)


![image](https://user-images.githubusercontent.com/54590466/234070261-1cee578b-d6d8-4825-95b1-c21aed6d4228.png)


![image](https://user-images.githubusercontent.com/54590466/234070324-7ecaaf45-790f-416e-9b3d-0ee8fecdb8fc.png)


![image](https://user-images.githubusercontent.com/54590466/234070338-f7f50161-9b67-4a81-9bde-97fed39732b1.png)


![image](https://user-images.githubusercontent.com/54590466/234070462-6ac1a67a-7794-431f-b937-ebd623673981.png)


![image](https://user-images.githubusercontent.com/54590466/234070495-7ddca293-8674-46c7-9429-46a3184851c0.png)



