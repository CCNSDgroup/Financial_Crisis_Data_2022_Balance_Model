# Financial_crisis_data_2022_model_balance
This is the repository for Data and results used in the paper (Financial Crisis in the Framework of Non-zero Temperature Balance Theory). The Data have been downloaded from www.yahoofinance.com.

The first folder provides the raw data that includes the time series of all 40 companies that have been selected randomly from distinct industries, in the time periods of 2005 to 2022, in the .csv format. These are the data that have been used in this study and downloaded from www.yahoofinance.com.

The fig-1 folder includes data that the first figure in the paper has plotted based on, the file has two columns the first one is Time ( x-axis values ) and the second one is S&P500 Index (y-axis values).
In figure 2 in the manuscript, we have plotted the probability distribution of the correlation matrices of stocks. Since we are considering the behavior of stocks in the 4 different periods of time, two near crises Great Recession 2005, COVID-19 Recession, and two far from crises off-crisis 2005, off-crisis 2019, then we have four different correlation matrices that we have plotted the probability distribution of these four matrices. These matrices are available here.

The fig-3 illustrates the heat-map of the correlation matrices and provides a visual vision of the communities inside of them; we have used community detection through the dendrogram representation. We build the dendrogram and heatmap by using the clustermap() function of the seaborn library of Python programming language. This function plots a matrix dataset as a hierarchically-clustered heatmap. The four matrices required for this figure are available.

Figure 4 demonstrates the changes in order parameter, Q, (weighted two-stars), the standard deviation (std) of the weighted two-stars ( ), and energy changes versus the temperature. For each panel in the figure, we have uploaded the data points related to each curve in the figure.

Figure 5 indicates the pattern of the energy-energy landscape between triads that have a shared link. The uploaded data is two columns of data in which each row represents two values corresponding to the energy values of two triads that have a common link. The color scale illustrates the frequency of triads which their energies are within a specific bin. We have used the matplotlib.pyplot.hist2d() function.

The fig-6 folder consists of data related to figure 6 of the manuscript, Critical temperature versus Time.
n the fig-7 folder, to clarify the importance of our proposed order parameter in detecting the structure of the network, we spare the two near crisis correlation matrices. We consider a moving window that moves from almost 50 days before the critical point (crisis) to 50 days after and we calculate the critical temperature in each interval of the moving window. In panel a, the sparse matrices of the Great Recession and its Gaussian counterpart have been uploaded and the resulting points which show the critical temperature of each interval of the moving window for this crisis have been provided in the plot folder. The same has been done for the other crisis, the COVID-19 Recession.
