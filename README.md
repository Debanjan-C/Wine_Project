# <div align="center">Someone Call Wine-Wine-One!
![alt text](https://github.com/Sandeep-Bansal1/Data_Analysis_ML/blob/master/wine%20cover.png?raw=true)

<pre>
Contrubuter  : Sandeep Bansal
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda
Libraries    : pandas, matplotlib, numpy, sklearn, seaborn
</pre>

<pre>
Assignment Submitted     : September 2020
</pre>

<pre>
Dataset: https://archive.ics.uci.edu/ml/datasets/wine+quality

</pre>
## Buisness Objective:
The goal is to predict quality of wine amongst the list of red wines using Linear Regression. The dataset consists of the information about physicochemical tests on the different varieties of wines. Various variables present in the dataset includes data of fixed acidity, volatile acidity, citric acid, ph, alcohol etc. The dataset comprises of (red wine - 1599 observations with 12 columns. Below is a table showing names of all the columns and their description.

This work was inspired by Àngela Nebot, Francisco Mugica1 Antoni Escobet in an attempt to predict wine preferences from physicochemical properties tests that are available at the wine quality certification step.

Research Article: https://www.scitepress.org/Papers/2015/55519/55519.pdf


## Data Dictionary:
| Column Name           | Description                                              |
| -------------         |-------------                                             | 
| fixed acidity         | Fixed acidity content                                    | 
| volatile acidity      | Volatile acidity content                                 |  
| citric acid           | citric acid content in ml                                | 
| residual sugar        | Residual sugar content                                   |   
| chlorides             | Chlorides content                                        |
| free sulfur dioxide   | Free sulphur dioxide content                             |
| total sulfur dioxide  | Total Sulphur dioxide content                            |
| density               | Density                                                  |
| pH                    | pH value                                                 |
| sulphates             | sulphate content                                         |
| alcohol               | alcohol content in ml                                    |
| quality               | Output Variable - score between 0 and 10                 |

## Primary findings

- After calculating the $R^2$ value it shows 37.8 % of the variability in wine quality can be explained by x features which is not a relaiable indicator of the y variable The graph above shows a non-linear relationship of the model in comparison to the data points. 


## Next steps

- My next steps would be to analyze and reduce the outliers in the data. Outliers can disrupt results and skew data. I would also like to try increasing the quantitative number in which the features were picked.Above I used a threshold of 0.05. I ponder if increasing this value would have an impact on the model.  
