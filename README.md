# Capstone-Project: Web and Social Media Analytics

## Mobile Phone Industry Analysis

### Business Understanding
With the increasing trend towards digitization and the widespread use of mobile phones and internet access, understanding consumer opinions is crucial for product-based companies, especially in the B2C sector. This project focuses on solving a problem within the US mobile phone industry, a major market globally. The goal is to assist a mobile phone manufacturer in gaining insights to optimize product development and devise effective marketing strategies.

### Project Overview
In this capstone project, we will analyze a dataset related to the US mobile phone market. The dataset encompasses reviews and sentiments from consumers, providing valuable information for companies to enhance their products and marketing approaches. By understanding consumer preferences and sentiments, the mobile phone manufacturer aims to improve market share and brand value.

### Applications of Data Analysis
Feature Improvement: Analyzing sentiment in reviews helps identify features that lead to positive or negative sentiments. This information guides the inclusion or enhancement of specific features in new product development.

- **Ad Campaign Design**:Companies can design effective ad campaigns by highlighting features that are widely discussed among consumers, improving overall marketing strategies.

* **Competitor Analysis**:Comparing competitors' pricing and market shares assists in determining optimal product pricing, avoiding mistakes made by rivals, and estimating market share.

+ **Market Share Estimation**:Higher review counts may indicate higher sales. Analyzing review data helps companies gauge the market share of competitors and understand their position in the market.

+ **Competitor Identification**:Understanding the landscape of similar products helps companies identify their major competitors in the market.

### Problem Statement
The mobile phone manufacturer, a relatively new entrant in the US market, seeks to understand competitors and user preferences. The objective is to refine marketing strategies, add value to the brand, and bridge the demand-supply gap. As a data analytics provider, the task is to provide insights into the mobile phone industry, enabling the client to develop an optimal new product and implement effective marketing strategies.

### Data Dictionary :
- **Phone data as the .csv file**:Contains the consumer activity information
- **Phone metadata as zipped .json file**: This data contains the product information and is independent of the consumer/reviewer activity and includes description, price, sales-rank, brand info, and co-purchasing links etc.
- **pos_words.txt** : This is a text file that contains a corpus of positive words. This file can help you in extracting some features out of the review text. There are multiple sources available online that gives you a corpus of positive negative words. You can also customise it based on your application.
- **neg_words.txt** : Similar to the corpus of positive words, this text file contains a list of words that can be a part of the negative reviews of the users.
- **Stop_words_long.txt**: In the previous modules, you had learnt to remove stopwords using the NLTK library. One drawback of it is, the negation words like nor, not, never are considered as stopwords. Remove those words may not affect a spam/ham classification, but it will definitely affect the sentiment classification. Hence, we have provided you with a customised list of stop words which you can use it for the analysis. 
