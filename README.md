<h1 align="center">Topic-modeling-on-News-Articles</h1>

<h4 align="center"> Colab Link :- https://colab.research.google.com/drive/1IgQ1qgBEAj7zNepZjjTGQ6Z3rQihTTzI?usp=share_link </h4>

![topic_model](https://user-images.githubusercontent.com/121340232/227875293-defdba92-0c30-44f9-a141-7e6cc5fa9555.png)


# **Problem statement :-**

- In this project, task involves analyzing the content of the articles to extract key concepts and themes that are discussed across the articles to identify major themes/topics across a collection of BBC news articles.


# **Project Summary :-**

- The objective is to create an aggregate dataset of news articles across business, entertainment, politics, sports, and technology and perform topic modeling on this dataset. The purpose is to determine the best segregation of documents based on their topics. This can be useful for topic labeling or for understanding the characteristics of a large text dataset.
- Topic modeling can be done using clustering algorithms such as Latent Dirichlet Allocation (LDA) or Latent Semantic Analysis (LSA). The resulting topics can be compared with the different tags available for the news articles to verify their correspondence.
- Once the topics have been identified, they can be used for a variety of purposes, such as content analysis, document clustering, and recommendation systems. By analyzing the topics in a corpus of news articles, we can gain insights into the underlying trends and themes in the news. This can be useful for journalists, researchers, and anyone interested in understanding the news media.


## **Dataset Info :-**

* Number of records: 2225

* Number of features: 2  (**News Articles**  &  **Type Of Topic**)

<BR/>

# **Project Work flow :-**

- **Importing Neccessary Libraries**

- **Data Wrangling**

```
      ▪ Gathering Dataset
      ▪ Assessing and cleaning Dataset
```

- **EDA**

```
      ▪ Univariate Analysis
      ▪ Bivariate Analysis 
```

- **Text preparation**

```
      ▪ Text-Cleanup
      ▪ Removing Stopwords
```

- **Text pre-processing**

```   
      ▪ Text-Tokenize
      ▪ stemming or lemmatization
      ▪ POS tagging
```

- **Text Vectorization**

```
      ▪ BOW
      ▪ TfIdf
```

- **Model implementation**

```
      ▪ using different algorithms
```

- **Model Evaluation**

- **Conclusion**

<BR/>

# **Model implementation :-**

* **`Latent Dirichlet Allocation model`**
* **`Latent Semantic Analysis model`**
* **`Gensim's implementation of the Latent Dirichlet Allocation model`**

<BR/>

# **Best Models to Achieve our Objective :-**

#### 🥇 Gensim's implementation of the Latent Dirichlet Allocation model 🥇

`Coherence Score : 0.54`

![coherence_score_topics_graph](https://user-images.githubusercontent.com/121340232/227881438-4ef7dd0c-4434-4bd9-a258-485f5b944d48.png)

<BR/>

# **Final Summary of Conclusion :-**

- In this project, we performed topic modeling on the BBC news articles dataset using three different techniques: LDA, LSA and Gensim's implementation of the LDA. After comparing the results, we found that Gensim LDA produced the best performance in terms of coherence score and interpretability of the generated topics.
- The top five topics generated by Gensim LDA were sports, business, entertainment, politics and technology. We identified the most significant keywords associated with each topics, which can be used to understand the major themes of the news articles.


## **What are the major themes ?**

- the major themes that emerge from the BBC news articles are sports, business, entertainment, politics and technology. These themes are quite broad, so it might be useful to further refine them based on specific sub-themes or topics that are frequently discussed within each category.
- For example, within the sports category, you might identify sub-themes such as football, basketball, tennis and so on. Within the technology category, you might identify sub-themes such as artificial intelligence, cybersecurity, social media and so on.


## **How can stakeholders use this information ?**

- Stakeholders such as media companies, advertisers, and content creators could use this information to better understand the types of news articles that are popular with different audiences.

- For example, media companies could use this information to tailor their content to specific audiences and improve engagement. Advertisers could use this information to better target their ads to specific audiences. Content creators could use this information to identify popular topics and develop content that is likely to be well-received.

- Stakeholders can use this information in various ways. For example, if a stakeholder is interested in investing in a particular industry or sector, they can use this information to understand the latest news and trends related to that industry. They can also use this information to keep track of their competitors and identify potential business opportunities.

- Moreover, stakeholders can use this information to understand the public perception and sentiment towards a particular topic or issue. For instance, if there is a political issue that is affecting a company's reputation, stakeholders can use this information to gauge public opinion and sentiment towards the issue.


## **What are the applications of this project in the industry ?**

  News organizations can use this project to automatically categorize news articles into different topics and improve their content curation process. This can help them to provide personalized news feeds to their users and increase user engagement. and businesses can use this project to analyze news articles related to their industry and identify potential business opportunities and threats. It can also help them to monitor their competitors and stay updated with the latest trends and news in their industry.

▪ Content optimization: Media companies could use topic modeling to analyze their existing content and identify topics that are popular with their audience. They could then use this information to optimize their content and improve engagement.

▪ Ad targeting: Advertisers could use topic modeling to better understand the interests and preferences of their target audience. They could then use this information to develop targeted ads that are more likely to be effective.

▪ Competitor analysis: Media companies and advertisers could use topic modeling to analyze the content produced by their competitors. This could help them identify gaps in the market and develop content that is more competitive.

▪ Trend analysis: Topic modeling could be used to identify emerging trends and topics that are likely to become popular in the near future. This could help media companies and advertisers stay ahead of the curve and produce content that is relevant to their audience.

<BR/>

### **click [here](https://colab.research.google.com/drive/1IgQ1qgBEAj7zNepZjjTGQ6Z3rQihTTzI?usp=share_link) To access the solution of the Capstone Project Topic-modeling-on-News-Articles Unsupervised Learning, which includes the usage of 3 different algorithms of topic modelling with detailed explanations and conclusions.**

<BR/>

Apologies for the inconvenience caused. Due to some technical issues with the github and .ipynb file, I have attached a Google Drive link of .ipynb file and also atteched pdf file of google colab for you to view the file. Thank you.



