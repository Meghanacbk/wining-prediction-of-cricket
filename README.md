# wining-prediction-of-cricket
Cricket is a sport that contains a lot of statistical data. There is data about batting records, bowling records, individual player records, scorecard of different matches played, etc. According to these data try predict wining result of the match
Cricket is a sport that contains a lot of statistical data. There is data about batting records, bowling records, individual player records, scorecard of different matches played, etc. This data can be put to proper use to predict the results of games and so this problem has become an interesting problem in today’s world. Most of viewers nowadays try to do some sort of prediction at some stage of the tournaments to see which team will eventually win the upcoming matches and thereby the tournament. This report aims at solving the problem of predicting the results of games by identifying the important attributes from the data set and using the data mining algorithms. I have limited my area of study to the domestic Twenty 20 tournament which is held in India every year during the summer i.e. the Indian Premier League. The previous work that I read and used as a reference were either predicting game results for all sports in general or sports like Basketball, Soccer, etc. My report describes in detail the different attribute selection techniques as well as the data mining algorithms used to solve this problem of result prediction in cricket. I have also used accuracy as the evaluation criteria to evaluate how well the prediction performs. Some future work is also suggested in this report in case some other student in the future is interested in continuing the study of this problem and improving upon my results


Advantages

The model which is used to predict the results of the matches was built successfully with an accuracy rate of about 60% to 70%. The list of attributes was cut down to 10 important ones out of the 21 attributes available in the data set by using the attribute selection algorithms. The 4 data mining algorithms that were performed on the model were J48, Random Forest, Naïve Bayes and KNN. The prediction results were better when K-Fold Cross Validation method was used as compared to the Percentage Split. The accuracy of the Random Forest algorithm was the best with 71.08%



Disadvantages

Although the accuracy was between 60% and 70% but it was still low because of the fact that the total number of instances in the data set was 574 and the total number of classes were 11. We need at least 100 instances per class to identify the patterns in the data set and perform a prediction with a high accuracy rate. So, with 11 classes in the data set we needed at least 1100 instances to perform a prediction with a high accuracy rate.
