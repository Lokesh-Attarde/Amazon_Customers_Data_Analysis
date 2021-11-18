
# Amazon Customers Data Analysis Project 🔥🍁

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
  
  ![GitHub stars](https://img.shields.io/github/stars/Lokesh-Attarde/Amazon_Customers_Data_Analysis)
  ![GitHub forks](https://img.shields.io/github/forks/Lokesh-Attarde/Amazon_Customers_Data_Analysis)
  [![GitHub contributors](https://img.shields.io/github/contributors/Lokesh-Attarde/Amazon_Customers_Data_Analysis.svg)](https://GitHub.com/Lokesh-Attarde/Amazon_Customers_Data_Analysis/graphs/contributors/)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
</p>  

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/142349256-b8571a8e-d75e-42e8-a9c0-8d1af09a7d73.jpg">
</p>

# 📝Problem Statement

- To perform Sentiment Analysis on Amazon Customers data, EDA for the Positive & Negative Sentences. Secondly, Find-out To What Users Amazon can recommend more Products?
- Next, Analyse Length of Comments whether Customers are prefer to give Lengthy Comments or Short one and Analyzing Score.
- Furthermore, Analyzing Behaviour of the Customers.

# ⏳ Dataset
Download the dataset for this project from following Link -
* [Amazon Customers Dataset](https://drive.google.com/file/d/1AIkvkTer9OoomvER69RSLol16k7A4xZ6/view?usp=sharing)

# 📚 Data Analysis
The data is in the form of **"SQLite" Database** where we are provided with 10 columns(Features) of data.

* **ProductId** : Unique Product ID's given to each products.
* **UserId** : Unique Customer ID given to each user.
* **Score** : Avg. Rating given by the Customer to each product.
* **Summary** : Short Summary given by the Customer to each product.
* **Text** : Detailed feedback given by the Customer w.r.t. each product.

Out of the 10 features given in the datasets, 05 are Continuous and 05 (including the target variable) are Categorical features.

# 🖥️ Technologies:
## 🛠️ Tools Used
* Jupyter Notebook is used as IDE.
* Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
* For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
* WordCloud is used to representing the text data.
* NLTK.corpus is used to process the StopWords.
* TextBlob is used to perform Sentiment Analysis.
* GitHub is used as version control system.

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/142146950-3081ea19-cd90-4999-8f67-728ceb57ac8a.png">
</p>

# 🎉 Tasks performed under Sentiment Analysis:
<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/142443073-646c4a34-ed77-460b-becf-3b6976201339.gif">
</p>

* Extracted the **"Polarity"** of each and every YouTube Comments using ***TextBlob*** Library.
* Pre-process the ***Textual Data***, eliminate the **'StopWords'** using ***NLTK.corpus***. 
* Perform variety of Analysis on different ***Use Cases*** and Visualize it using **"WordCloud"**. 

For more details, please go through the [Jupyter Notebook](https://drive.google.com/file/d/1eTKLGeFMZR2IJij8V3qjMSuO9PnCvsHG/view?usp=sharing) attached above and following Glimpses -

# 🌱 Some Exciting Glimpse of the Visuals:
![Glimpse 1](https://user-images.githubusercontent.com/84115928/142457948-9626a04a-4e51-4f47-a5f9-4c2a0564d700.gif)
![Glimpse 2](https://user-images.githubusercontent.com/84115928/142457991-11f27fb1-8ced-49e7-bd12-10893373cecd.gif)
* Behaviour of Customers
<p align="center">
  <img width="600" height="300" src="https://user-images.githubusercontent.com/84115928/142458029-9bbf8b08-b6a2-47b5-b44e-516afba8acb5.JPG">
</p>

# 💡 Conclusions
* In terms of Positive Summary - "Good", "love", "Delicious", "Best", "Great Product", "Excellent", etc. All these kinds of 'Positive Keywords' has a 'Higher Priority' than all other Words.
* In terms of Negative Summary - "Disappointed", "bad", "taste", "little", "expensive", "horrible", "terrible", "expected", "flavor", "little", etc. are these kind of Negative Keywords "Customers" are going to prefer.
* Almost "50%" Users were prefered to give their "feedback" almost in "50 Words", whereas there are only few Users who are going to give a "Lengthy Feedback's".
* Most of the Customers are going to give "5" Score on most of the Product.
* In terms of Behavior of the Customers - Most of the time our "Customers" are going to prefer all these "Keywords" such as - "chip", "flavor", "like", "good", "great", "one", and many more.

# 🎉 Help Me Improve
Hello Mr. Reader, if you find any bug or anything else that could add more value in this project then please consider raising it to me I will address them asap.
  
# 📫 Feedback
If you have any feedback, please reach out to me via [LinkedIn](https://www.linkedin.com/in/lokesh-attarde-145086141/)
