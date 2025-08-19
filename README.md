This project is about predicting stock prices of future dates .

columns of the data include 1.symbol 2.date 3.close 4.high 5. low 6. open 7.volume 8.adj.close 9.adjHigh
10.adjLow 11.adjOpen 12.adjVolume


We have only considered the close value and date and transformed the close value into furher four columns woth some computations like shift and rolling(mean)



Based on the above data our model will predict how much loan can be sanctioned to a customer.

Process of operations

1.	Loading the data into a dataFrame
2.	creating new columns by shifting 1 row of target,2 rows of targets , mean of 3 rows of target and mean of 7 rows of target
3.	seperating target and features
4.	seperating testing and training data
5.	Training the model with training set
6.	predicting the model
7.	evaluating the model
8.	making the model predict with new set of unseen data
9.	visualisation with actual and predicted data of both test and unseen data


The model has been tested with new set of datas and the prediction accuracy stands to 93 percentage approximately.

ERROR IS ALSO VERY MEAGRE IN THE UNSEEN DATA SAY 0.12