# machine_learning_trading_bot.ipynb

## Background

For this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

## What You're Creating
You’ll combine your new algorithmic trading skills with your existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

In a Jupyter notebook, you’ll do the following:

Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.

Adjust the input parameters to optimize the trading algorithm.

Train a new machine learning model and compare its performance to that of a baseline model.

As part of the README.md file in your GitHub repository, you’ll also create a report that compares the performance of the machine learning models based on the trading predictions that each makes and the resulting cumulative strategy returns.

## Technologies

Pandas, Jupyter Lab, PyVizlot, SciKit Learn, Numpy

## Project analysis and report

## Baseline SVM Model

 ![baseline](Image/baseline.png)

 ![baseline svm](Image/baseline svm.png)

 ## SVM DateOffset 4 months ##

  ![4 months](Image/4 months.png)

![4 months svm](Image/4 months svm.png)

## SVM DateOffset 6 months ## 

  ![6 months](Image/6 months.png)

![6 month svm](Image/6 month svm.png)

## Linear Regression Model ## 

  ![lr model](Image/lr model.png)

![lr graph](Image/lr report.png)


## Conclusions ##

When comparing the baseline SVM models, the version with the DateOffset parameter set to 6 months was more exact but still had the same accuracy as the 4 month offset. Compared to the baseline, the 4-month SVM was more accurate but not as exact. Compared to the baseline, the six-month period was more exact and accurate. All things considered, the most useful version of the SVM among those examined is the one with the DateOffset set to six months. The 6-month SVM exhibits greater accuracy when compared to the Linear Regression model. Both models were equally accurate, though. The six-month offset SVM is the model that I would advise using. 
