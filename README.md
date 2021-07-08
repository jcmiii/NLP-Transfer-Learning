# NLP-Transfer-Learning
Study of NLP and Transfer Learning applying various ML algorithms (KNN, SVM, Deep Learning)

If you wanted to follow along with my study you would use the files in this order:
1. Data_Pipeline
2. NLP with KNN and SVM
3. DL (using movie reviews only)
4. Manual Scoring (add tweet sentiment to movie reviews)
5. DL (with tweets added to training data)

**Findings:** A NN trained on 2100 movie reviews did not perform well when classifying the sentiment of tweets. The tweets I examined had a 31% positive sentiment rate, while the NN classified 70% of the tweets as being positive. I.e. transfer learning was not effective. However, adding 100 labeled tweets to the training set helped quite a bit. The NN trained on this data classified 28% of the tweets as being positive.  
