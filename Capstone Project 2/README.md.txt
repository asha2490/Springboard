## Capstone Project 2

## Literature Clustering of Covid-19 Related News Articles using NLP

### Personal Statement
The World Health Organization declared that COVID-19 was a global pandemic, indicating significant global spread of an infectious disease. COVID-19 outbreak was first reported in Wuhan, China and has spread to more than 50 countries. WHO declared COVID-19 as a Public Health Emergency of International Concern (PHEIC) on March 11, 2020. Naturally, a rising infectious disease involves fast spreading, endangering the health of large numbers of people, and thus requires immediate actions to prevent the disease at the community level. Lot of people around the world are trying to find as much information and news on this topic to stay up to date and also help society with their research and developments. With this project we hope to cluster all the research/news articles related to covid-19 to simplify the search of related articles.

The project is divided into three parts and is structured as following:

### 1. Data Extraction and Analysis
I have collected the news by requesting an external REST API called NEWSAPI. Using the free service I have extracted as many articles as possible and perfromed some data cleaning and exploratory data analysis

### 2. Data Pre-processing and Tokenization
Once the data is collected and stored, I converted it into a pandas dataframe. I first preprocessed the data using text preprocessing tokenization and the tfidf algorithm and extracted some important keywords/tokens

### 3. Clustering and Topic Modeling
I clustered the data using two algorithms: K-means and Latent Dirichlet Allocation (LDA) to extract topics from each document. Finally I visualized the news clusters using two interactive python visualization libraries called Bokeh and pyLDAvis.

To visualize the interactive Bokeh plot, please download the notebook.

To see the interactive pyLDAvis plot, please open the file\
https://htmlpreview.github.io/?https://github.com/asha2490/Springboard/blob/master/Capstone%20Project%202/pyLDAvis.html

Please find the full PDF report in the github - "Capstone Project 2_ Final Project Report.pdf"
