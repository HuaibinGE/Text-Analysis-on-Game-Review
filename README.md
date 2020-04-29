# Final Project in Course Data Mining: Text-Analysis-on-Game-Review
This is the final project of COSC189
Author: Weiyi Wu, Boran Lu, Huaibin Ge, Mengdan Zhu
## Data
### Data Scrapting
Data was mainly scraped from [Steam Community](https://steamcommunity.com/app) and [Steam Database](https://steamdb.info/graph/)
### Data Preprocessing(Normalization and Tockenization)
* Conducted text normalization such as adding stop words, porter stemmer and removing punctuations and digits using regular expressions
* Tokenized and vectorized those words to sparse matrix
## Methods
### Sentiment Classification(1-gram, 2-gram and 3-gram language models)
* Logistic Regression
* Random Forest
* Support Vector Machine(SVM)
* Naive Bayes
### Predict Game Scores(Scores from Game Website Metacritic)
* Linear Model
* Support Vector Regression(SVR)
* Random Forest Regression
### Topic Modelling
* Latent Dirichlet Allocation(LDA)

More information in the [Report](https://github.com/HuaibinGE/Text-Analysis-on-Game-Review/blob/master/Final%20Report.pdf)
