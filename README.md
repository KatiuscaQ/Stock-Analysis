# Stock-Analysis

## Overview of Project
The purpose of this analysis is to refactor the code already created for Steven in order to make it more efficient. Since Steven wants to do a little more research for his parents, and he wants to expand the dataset to include the entire stock market over the last few years, he will need a “cleaner” code that will take less time in performing and outputting results than the original.

## Results: 
If we compare the stock performance between 2017 and 2018 is like comparing day and night. The stock performance in 2017 was 92% positive while the stock performance in 2018 was 83% negative. See images of each year below:
![All_Stocks_2017](https://github.com/KatiuscaQ/Stock-Analysis/blob/master/Resources/All_Stocks_2017.PNG)

![All_Stocks_2018](https://github.com/KatiuscaQ/Stock-Analysis/blob/master/Resources/All_Stocks_2018.PNG)
  
It can be seen in the images that there is no relationship between the behavior of each stock in 2018 with the behavior of each stock in 2017. If we see, not all of the-top-three best-performance stocks of 2017 are the positive stocks of 2018. The best stock of 2017 was DQ, while DQ was the worst stock during 2018.
With this simple comparison Steve can show his parents that they should not take the decision of putting all their money in one stock based on how that stock did in one year, they will need more years of data to make an accurate decision about what stock has done better through the years. Also, it will be more informative to his parents and they will (hopefully) base their decision on data trends and not on sentimental values.

Now that Steven has a more efficient macro, he will be able to run more data in less time.
The next images show the times the refactored code takes to run through each year:
![VBA_Challenge_2017](https://github.com/KatiuscaQ/Stock-Analysis/blob/master/Resources/VBA_Challenge_2017.PNG)

![VBA_Challenge_2018](https://github.com/KatiuscaQ/Stock-Analysis/blob/master/Resources/VBA_Challenge_2018.PNG)
  
Each year takes about 8 seconds to run. 

## Summary: 
To summarize, this module refactoring can have its advantages and disadvantages. 

The big _**advantage of refactoring**_ comes down to how efficient the code becomes, also, refactoring makes a code easier to maintain in the future. In the case of the _**VBA script**_, refactoring it made the code way cleaner and easier to run, now the code even when is outputting the same result than before is doing it in less steps.

The _**disadvantage**_ is to go through a working code and try to figure out what commands are not being use in the right place, and with this a lot of re-testing that could become frustrating. When _**refactoring the VBA script**_, it was challenging to go through each index that needed to be changed and running the code to find out that there was another index that was being missed.

