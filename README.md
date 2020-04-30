# COVIDResearch-LatentDirichletAllocation

The data used for this project can be found at https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge. 

In this code, the research papers are cleaned so that their text contain no punctuations and only the nouns present in the content. 

Using Latent Dirichlet Allocation, the texts are analyzed and topics are created, based on the nouns found in each paper. The number of 
topics can be altered by changing the value assigned to the "number_topics" variable, and the "number_words" variable can be altered based
upon how many of the top words in each topic you wish to print. 

Another note: Currently, the results in the notebook are only those of the first 100 papers in the DataFrame, due to processing power and time. The code, however, has been changed so it would run through all the papers. 
