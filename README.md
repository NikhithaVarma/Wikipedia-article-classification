Provided a repository of Wikipedia articles, created a binaryclassification model to classify the articles as featured or non featured.

Preprocessing: Each article's datacontains its full history (in XML format). We need to extract the text from last revision. Used the wikipedia API to extract the details from the article name.

Feature Engineering: For each article, found the following and represented as features for applying the ML model:
                     1. Number of words in last revision
                     2. Total no. of revisions
                     3. Number of distinct users
                     4. Number of wikilinks in the last revision
                     
Created 4 ML models and compared the accuracy and also did the feature importance and found the most important feature.
ML models used are: 1. Logistic Regression
                    2. Decision Tree
                    3. Random Forest
                    4. Support Vector Machine
                    
Got the best accuracy score #92.66% with SVM model and found the number of words as the most important feature
