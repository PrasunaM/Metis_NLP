## NLP on Ted Talks

The goal of this project is to come up with topics that are being promoted the most. The first step of this project was data cleaning and selecting only talks greater than 100 words. 
Talk transcripts were preprocessed by using RegexpTokenizer, removing stop words, lemmatized and stemmed. The preprocessed data was then vectorized using tfidf vectorizer and modeled on NMF. This was my first attempt and i was happy with the result. 
I realized that 10 topics with 20 words in each was summerizing the data clearly. Please see below topics- 

<img src="Screen Shot 2021-06-22 at 2.21.22 PM.png" alt="Topic Modeling" width="800" height = "600"/>  

Next, I will be working on creating a dataframe with topics mapped to the talks and no. of views for each talk to fit into a linear regression.  

