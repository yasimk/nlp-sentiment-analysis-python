# nlp-sentiment-analysis-python
Leveraging NLP to do sentiment analysis in Python. Read about the background here - https://medium.com/@yasimk_87248/using-data-science-in-everyday-life-f9b58f1f74af

Using NLP and Python libraries, measure the satisfaction from the data collected from a google survey. The background about the project is published in my Medium blog. 


1) Leveraged pandas data frame to read the CSV file and to do data transformations (Adding columns, measuring correlation etc.)
2) Used the NLTK - FreqDist and NLTK Word tokenize to count the most frequent words used in various survey questions 
3) Used matplotlib.pyplot to draw histograms, bar charts for various satisfaction metrics
4) Used regular expressions (re) and Lambda to cleanse the data and to do transformations
5) Used TextBlob to measure the sentiment (positive or negative) using Polarity and measured subjectivity using subjectivity
6) Used WorldCloud to generate the WordClouds for unstructured data
7) Used seaborn library to plot heat map for correlation matrix, bar plot
