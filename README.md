# FakeNewsDetector

First, I discovered higher phrases that appear more frequently than others using Term Frequency (TF) and Inverse Document Frequency (IDF). I also used IDF to determine how essential a term is over the entire corpus. When the term appears in the search terms, we may claim the document is a good match. In addition, we used Passive Aggressive methods, which aid in making updates that fix the loss while generating very little change in the weight vector's norm.

On our dataset, we first create a TfidfVectorizer [tfidf v]. After that, we fitted the model with a PassiveAggressive Classifier. The accuracy score and the confusion matrix, in the end, tell us how well our model performs.

Dataset Used: https://drive.google.com/file/d/1o3RST8OYMXKoMLEOb_aLoZpqiuztw7z3/view?usp=sharing
(Total 7800 news used with random Fake-True Lables)
