# Financial_crisis_data_2022_model_balance
This is the repository for Data and results used in the paper (Financial Crisis in the Framework of Non-zero Temperature Balance Theory). The Data have been downloaded from www.yahoofinance.com. 

All Data that we used in the paper has been uploaded to this repository.

The threshold matrix has been used in fig-7 a,b. To plot this figure we move the threshold window. it means (for example) that for -40 (In X-axis) we consider 50 days that started from 40 days before the crisis until 10 days after the crisis. So, for any dot in the plot, we have one correlation matrix. For example, we have uploaded the correlation matrix of two crises, but you can reconstruct the matrices as follow:
1- consider the window of any crisis.
2- before construction of the correlation matrix,(for shift 10 days later) shift the 50 days window to 10 days later and get the data of each company in this period.
3- construct the correlation matrix.
4- set a threshold of 0.50 on each element of the matrix that is constructed.
