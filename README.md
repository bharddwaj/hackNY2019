# Predicting Github Issue Piorities 
The purpose of this project was to develop a model that could accurately classify a github issue as low priority, medium priority, or high priority. Using TFIDF, we were able to pass text as features to the model. Important to note we only considered posts that explicity had high, medium, or low priority in our dataset and we assigned them 1,0,-1 respectively.

How to use this project:
run the model.py file

Possible Improvements:
Need to figure out how to pass both the title and the body as features. Right now I can only pass one of them. This is supposed to be a command-line tool, but due to time constraint and one of our member's having to leave early we couldn't implement that.

Accuracy:
The model is around 55% accurate; pretty significant considering random guess would yield 33%, but of course can be better.

[Link to pipeline design](https://docs.google.com/drawings/d/1t_DUcoo76UntM3K3sCGEEeblyhOuipmvnfuRM3uMMCI/edit?usp=sharing)
