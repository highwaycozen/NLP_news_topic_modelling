# NLP_news_topic_modelling
Using news setscraped from major news publishers, perform topic modelling using LDA and NFM approaches.
Steps taken:
Cleaning the data, applying LDA and NFM for different values of K. Using pyLDAvis to visualize topic models.
  Results:
Top terms for the topics are related, which suggest that the topics make sense. NFM has argubly easier to classify topics based on the top terms. However, LDA was faster, as you could calculate optimal number of topics k with perplexity and log liklihood. For NFM word embedding is required, and it takes a while depending on the size of the corpus.
