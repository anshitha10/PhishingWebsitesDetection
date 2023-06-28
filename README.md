# PhishingWebsitesDetection
A phishing website is a popular approach that imitates reliable URLs and web sites. The goal of this research is to use the dataset obtained to predict phishing websites using machine learning models and. In order to create a dataset from which the necessary URL- and website content-based attributes are extracted, both phishing and harmless URLs of websites are collected. Each model's performance level is assessed and evaluated.
# Data Collection
The list of phishing URLs was coleected using the open-source PhishTank  website. This site offers a collection of phishing URLs that are updated hourly in a variety of formats, including csv, json, etc. Visit https://www.phishtank.com/developer_info.php to download the data.
The authentic URLs were extracted from the University of New Brunswick's open datasets at https://www.unb.ca/cic/datasets/url-2016.html. This dataset contains a collection of URLs that aren't malicious, spammy, phishing, or defacement. The harmless url dataset is taken into consideration for this study out of all of these types. 
The dataset comprises of approximately 12,000 phishing urls and 10,000 harmless urls.
# Feature Extraction
Feature extraction from these urls are categorised into two:
1.Address based features: Features taken from the content of the url
2.HTML and Javascript based : Features taken from html & javascript tags and code
# Machine Learning Model
Classification is a supervised machine learning process of categorizing a given set of input data into classes based on one or more variables.
As it is a classification problem classification models are used:
>> Decision Tree
>> Random Forest
>> XGBoost
>> LightGBM
>> SVM
>> Naive Bayes
# Results
According on the above models' results, Random Forest has the highest model performance at 86.4%. Consequently, the model is stored in the file "random_forest_model.pickle.dat."

