<!--
{% if site.google_analytics %}
  <script>
    (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
    (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
            m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
    ga('create', '{{ site.google_analytics }}', 'auto');
    ga('send', 'pageview');
  </script>
{% endif %}
-->

<!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics 
{% include head-custom-google-analytics.html %}
-->

<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="{{ '/favicon.ico' | relative_url }}" -->

<!-- end custom head snippets -->

<!--# Kelsey Milo Green - Data Scientist-->

<!-- 
This is a multi-line comment.
It will not be displayed in the rendered Markdown.
Old profile picture linked to linkedIn seen on the line below:
[![milokgreen](https://user-images.githubusercontent.com/105948938/210701763-c42b2db9-5fb0-4d9a-a64a-57dbbb57a349.png)](https://mkgreen.github.io/milogreen.github.io/)
-->

<!-- 
Below is a square headshot only no banner with a link to LinkedIn.
[<a href="https://www.linkedin.com/in/kelsey-m-green/">
  <img src="https://media.licdn.com/dms/image/D5603AQE2DBoyEKtB9g/profile-displayphoto-shrink_800_800/0/1709790481553?e=1727913600&v=beta&t=8kM-F-hPN-rFbQQ3w8fL4aAn0N9_lO5SbqgjplU_zDI" alt="milokgreen" width="200"/>
</a>](https://www.linkedin.com/in/kelsey-m-green/)
-->
<!--new banner-->
[<img width="1438" alt="Screenshot 2024-08-02 at 8 47 04 PM" src="https://github.com/user-attachments/assets/9d9dec69-12d3-4d3f-92f9-09424e0af8af">](https://www.linkedin.com/in/kelsey-m-green/)

***email me: [green.milok@gmail.com](mailto:green.milok@gmail.com)***

***Find me on [LinkedIn](https://www.linkedin.com/in/kelsey-m-green/)***


# *Data Science Projects*

Here are some of my best Data Science Projects. I have explored various machine-learning algorithms for different real-world datasets. Please feel free to contact me to learn more about my experience working on these projects.

### [Diagnosis of breast cancer using a logistic classifier](https://github.com/mkgreen/Breast-Cancer-Classification)

[![breast-cancer](https://user-images.githubusercontent.com/105948938/210696322-7f632410-13c6-4aab-8e00-bf7552a32917.jpeg)](https://github.com/mkgreen/Breast-Cancer-Classification)


**Skills used:** Python, Pandas, SKlearn, Matplotlib

**Project Objective:** Identification of the type of Breast Cancer for quicker diagnosis. This assists professionals in the medical field to take appropriate measures to accurately diagnose, treat, and save lives. 

**Quantifiable result:** Types of tumors were successfully classified with [**96%** accuracy by using K-means algorithm](https://github.com/mkgreen/Breast-Cancer-Classification/blob/main/Breast_cancer_classification_algorithm.ipynb).

- Used logistic regression to identify a tumor as malignant or benign based on various attributes
- Classified tumors as benign or malignant by studying patterns in measured attributes of those tumors
- Used Logistic regression classifier & optimized the accuracy by using the ROC curve
- Explored a machine-learning approach to medical diagnosis

***
### [Amazon Fine Food Analysis using NLP](https://github.com/mkgreen/NLP-Amazon-Reviews/blob/main/README.md)

[![amazon](https://user-images.githubusercontent.com/105948938/214133955-1eba5605-2603-404a-864a-707892271c7b.jpeg)](https://github.com/mkgreen/NLP-Amazon-Reviews/blob/main/README.md)


**Skills used:** Python, Pandas, SKlearn, TfidVectorizer

**Project Objective:** Given a review, determine whether the review is positive or negative based on Amazon foods.

**Quantifiable result:** A rating of 4 or 5 could be considered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is neutral and ignored. This is an approximate way of determining the polarity (positivity/negativity) 

[**AUC** Score of 94%](https://github.com/mkgreen/NLP-Amazon-Reviews/blob/main/NLP_Project_Amazon_Reviews.ipynb) .
- Given a review, it is determined whether the review is positive or negative.
- Used NLP for this approach.
- A review of 1 or 2 could be considered negative. A review of 3 is neutral and ignored.

***
### [Identifying symptoms of orthopedic patients as normal or abnormal](https://github.com/mkgreen/Orthopedic-Patients-Classification-KNN-NB)

[![knee-brace-ortho](https://user-images.githubusercontent.com/105948938/210697291-f37f4d78-f7f5-48e8-b7fd-4375a9254df3.png)](https://github.com/mkgreen/Orthopedic-Patients-Classification-KNN-NB)

**Skills used:** Python, Pandas, SKlearn, Matplotlib,KNN,NB

**Project Objective:** In this project, the data provided multiple instances of orthopedic parameters and their classification as either Normal or Abnormal. I implemented K Nearest Neighbor to classify and diagnose the patients.

**Quantifiable result:** Successfully classified the orthopedic parameters as either Normal or Abnormal with an accuracy of **81%.**

- Used the K Nearest Neighbours algorithm to classify a patient's condition as normal or abnormal based on various orthopedic parameters
- Compared predictive performance by fitting a Naive Bayes model to the data
- Selected best model based on train and test performance

***

### [TalkingData Project on Bagging and Boosting ensemble model:](https://github.com/mkgreen/Fraud-Detection-DT-Ensemble/blob/main/Bagging_and_Boosting_Esemble_Project.ipynb)

[![Mobile](https://user-images.githubusercontent.com/105948938/210698301-3cab65b9-c084-47a4-915f-a092d8377d9e.jpeg)](https://github.com/mkgreen/Fraud-Detection-DT-Ensemble/blob/main/Bagging_and_Boosting_Esemble_Project.ipynb)


**Skills used:** Python, Pandas, SKlearn, Matplotlib, XGboost Classifier, BaggingClassifier

**Project Objective:** Predict fraud by using the data gathered from features associated with clicks, such as IP address, operating system, device type, time of click, etc.

**Quantifiable result:** Successful classification of people who did and did not download the app after watching an advertisement with an accuracy of 97%.

- Used the XGboost Classifier algorithm to classify the People who downloaded the app after watching the advertisement and identify the click fraud
- Compared predictive performance by fitting a BaggingClassifier model to the data
- Selected best model based on train and test performance

***
### [Prediction of user interest using bank data](https://github.com/mkgreen/Banking-Classification-Logistic-Regression/blob/main/Portugese%20Banking%20Classification.ipynb)

[![banking](https://user-images.githubusercontent.com/105948938/210697085-9f12b658-be7a-4493-afd1-10c9aaf397d5.jpeg)](https://github.com/mkgreen/Banking-Classification-Logistic-Regression/blob/main/Portugese%20Banking%20Classification.ipynb)


**Skills used:** Python, Pandas, SKlearn, Matplotlib

**Project Objective:** Using the real-world data of a Portuguese banking institution, predict if a client will subscribe to a term deposit (variable y).

**Quantifiable result:**

- The classification goal is to predict if the client will subscribe a term deposit (variable y).

***

### [Examining the effect of environmental factors and weather on demand of Bike rentals](https://github.com/mkgreen/Bike-Rental-Demand/blob/main/Linear_Regression_Project_Seoul_Bike_Data.ipynb)

[![seoul-bikes](https://user-images.githubusercontent.com/105948938/210696437-cb69d9ae-3f14-4792-a80c-0c6f938cac36.jpeg)](https://github.com/mkgreen/Bike-Rental-Demand/blob/main/Linear_Regression_Project_Seoul_Bike_Data.ipynb)


**Skills used:** Python, Pandas, SKlearn, Matplotlib

**Project Objective:** Predicting Bike rental demand based on weather and seasonal factors in advance to take appropriate measures which finally will result in bike utilization.

**Quantifiable result:** Successfully able to predict the Bike rental demand resulting in [**94%** accuracy](https://github.com/mkgreen/Bike-Rental-Demand/blob/main/Linear_Regression_Project_Seoul_Bike_Data.ipynb).

- Used Random Forest Regressor to predict the number of bikes rented in the city of Seoul
- The data had quite a few categorical variables which were encoded for use in the model
- Encoded categorical variables to numeric using Sklearn due to the presence of many string columns
- Cross-validation for validating the training data and model fit.
- Fit a Random Forest Regressor with high prediction accuracy through iteration
<!-- comment -->

***

# *Career Highlights, Education, & Credentials Continued:*

### Making a difference with data at the Brooklyn Public Library
<!-- BPL slide -->
[![6](https://github.com/user-attachments/assets/989a64ff-54e5-4605-8c6b-3e7fb26808ec)](https://www.linkedin.com/in/kelsey-m-green)

***

## What I am doing now
<!-- freelance work -->
[![7](https://github.com/user-attachments/assets/52506b86-c7a4-45b1-802d-97d800ca5217)](https://data-impact-solutions.b12sites.com/index#about)

<!-- dashboard work -->
[![10](https://github.com/user-attachments/assets/3ef0f8a9-6eb6-4088-82cf-5f10d9503e21)](https://data-impact-solutions.b12sites.com/index#services)

***

## Education & Certifications
<!-- educational background image: -->
[![5](https://github.com/user-attachments/assets/7f1a6b10-6afc-42cb-a6c1-2aad0ef31eb0)](https://www.linkedin.com/in/kelsey-m-green/details/honors/)

<!-- Credly certification image: -->
[![Data Science, Machine Learning   AI ISSUED TO Kelsey M  Green(1)](https://github.com/user-attachments/assets/d0107992-2c98-4231-8b65-b39e48975a47)](https://www.credly.com/badges/275a65fb-d6e4-4749-be9a-0b4d2db4ea36/)

***

