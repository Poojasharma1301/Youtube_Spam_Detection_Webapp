# Youtube_Spam_Detection_Webapp
A Web Application integrated with Machine Learning to classify YouTube Comments as Spam or Not-Spam.Combination of 5 youtube video comments for train our model.
## Dataset Information:-
UCI Machine Learning Dataset
## Dataset Features:-
Comment-id , Author , Date , Content , Class
## Steps Follow for solving this problem :-
1.Importing all Neccesary Libraries<br>
2.Importing the Dataset<br>
3.Spliting dataset into train and test dataset<br>
4.Tokenizing comments in training set and applying TF-IDF vectorizer on training set<br>
5.Training the multinomial Naive Bayes model<br>
6.Generate predictions on test set<br>
7.Generate model performance metrics<br>
8.Deploy the model <br>
## Libraries Used:-
1.Pandas<br>
2.Zipfile<br>
3.Pickle<br>
4.Scikit-learn<br>
## Model Used:-
MultinomialNB
## Best Model Accuracy : 90%
## Deployment :
Heroku
## Heroku Deployment Link: https://youtube-spam-detection-pooja.herokuapp.com/
## Sample video Link : https://drive.google.com/file/d/17frOFQlbGzwqcci-YzsPfNXKO_--jdMg/view?usp=sharing
