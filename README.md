# sentiment_analysis
Sentiment Analysis of customer reviews in eCommerce

The work contain five different experiments saved in jupyter notebooks.

The data is loded and then different pre-processing techniques are applied to the data to remove unwanted noisy data.
Porter stemming and removal of stpwords are some of the preprocessing techniques used. After preprocessing, the data is converted to vector forms using different vectorization methods. This data is then trained with various models used for prediction.
The first three experiment find out the best model for sentiment anlaysis classification in electronics products customer reviews using different vectorization methods and machine learning algorithms.

1. Count vectorizer with Random forest, XGBoost, Logistic Regression and SVM : The SVM provides the best classifier in this model
2. TF-IDF with SVM and XGBoost: In this case also SVM provides better prediction model
3. Word2vec with LSTM and CNN: LSTM provides the better performance measures

Analysing these three experiments it is found out that LSTM using Word2vec provides the best predictive model and can be classified as the efficient model for predicting sentiment analysis. Also, it shows that the performance of the model changes in according to the vectorization methods.

Next experiment is done to check the accuracy change while incresing the dataset using pseudolabelled data.

4. Pseudo labelling: Here LSTM model is first used to predict the values for unseen data and combining this pseudo labelled data with original dataset increases the size of data. The newly formed data is then trained and modeled with LSTM. The output plots shows that there is an increses in the performance measures when the dataset increases.

Final experiment is done with data from multiple domains.

5. Multi domain: Data is taken from four different domains. As a result the data size is larger then it is used in the first three experiments. This data is also trained with deep learning models. Comparing the results obtained with the result of single domain, it is obatained that there is a huge lower rate in the performance measures in the study even after the dataset increased.
