
![1_dGX0zZK67_c1dVFAJ0cHHA](https://github.com/GoppyKrishna-77/AI_8138_CSE_TEAM9/assets/83293163/35c7a599-8f51-4183-8118-21713bcd1bea)

# Sentiment analysis for marketing
### Team Leader : GoppyKrishna M 
### Team Members : Gokul S, Hariharan T, Hari Prasath R B

___

**Dataset :** https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment

**Documentation :** https://github.com/GoppyKrishna-77/TwitterSentimentAnalysis/blob/main/Project_Documentation.md

**Source Code :** https://github.com/GoppyKrishna-77/TwitterSentimentAnalysis/blob/main/model.ipynb

**Predicted Dataset :** https://github.com/GoppyKrishna-77/TwitterSentimentAnalysis/blob/main/Tweets_Input.csv

**Dashboard Code :** https://github.com/GoppyKrishna-77/TwitterSentimentAnalysis/blob/main/dash.py

___

### **Problem Definition:** 

The problem is to perform sentiment analysis on customer feedback to gain insights into competitor products. By understanding customer sentiments, companies can identify strengths and weaknesses in competing products, thereby improving their own offerings. This project requires utilizing various NLP methods to extract valuable insights from customer feedback.

### **Project Outcomes:** 
The Project helps companies Visualize and Understand:
-	**Customer satisfaction**
-	**Product feedback**
-	**Brand perception** 
-	**Competitive Intelligence**
-	**Market Trend Analysis** 
  
This information helps the Companies to improve their products and services by observing the performance of Competitor's products among the Public. Thus, improving the Brand’s perception among the Public leads to Profit and Growth of the Company.

### **Dependancies :** 
**Data Loading and Visualization**
- **Pandas** ```pip install pandas```
- **Numpy** ```pip install numpy```
- **Matplotlib** ```pip install matplotlib```
- **Seaborn** ```pip install seaborn```

**Text Processing**
- **Demoji** ```pip install demoji```
- **Unicode** ```pip install unicode```
- **Html** ```pip install html```
- **string**
- **re**
- **NLTK** ```pip install nltk```
- **WordCloud** ```pip install wordcloud```
- **Collections**

**Model Training**

- **Sklearn** ```pip install scikit-learn```
- **PyTorch** ```pip install torch```
- **Transfomers** ```pip install transformers```

**Deployment**

- **Streamlit** ```pip install streamlit```
- **Vega-Altair** ```pip install altair```
- **Ipython** ```pip install ipython```

### **How to Execute?**

1. Install the required Dependancies and Dataset.
2. Execute the [Source Code](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment) file (AI_Phase5/AI_Phase5.ipynb) to Pre-process the data, Train Data Models and Generate a Input dataset for Visualizing in the Dashboard.
3. Execute the [Dashboard Code](https://github.com/GoppyKrishna-77/TwitterSentimentAnalysis/blob/main/dash.py) file (AI_Phase5/dash.py), using the following:
   ```streamlit run dash.py```
to create a Dashboard Using Streamlit.

### **Key Features**

- **Context Based Stop Words Identification** - Performed by taking Top-25 frequently used words in all the Sentiment Categories.
- **Negation Handling** - Identifying and Reversing negation statements in the text.
- **Robust Model** - Used a RoBERTa Deep-Learning Model for higher prediction accuracy.
- **Interactive Dashboard** - Ability to target specific a Company in the Dashboard.

### **Dashboard**

![dashboard](https://github.com/GoppyKrishna-77/TwitterSentimentAnalysis/blob/main/dashboard.png)

