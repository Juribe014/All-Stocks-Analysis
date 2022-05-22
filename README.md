# All-Stocks-Analysis
Refactor VBA Code and Measure Performance

# Overview of the Project:

The purpose of this analysis is to refactor the Module 2 solution code. By doing so the code should be more efficient or improve the logic of the code for future users  to read the code easier. 

# Results

## Efficiency
The refactored code and the module code had the same time differantial. As shown by the comparison below. However, it can be stated that the refactored code is more efficient. The refactored code does more for the readeability of the analysis. First the numerical data is formated in such a way that it can be more easily read. Secondly, the Return column is color coded to identyfy the stocks with the passable returns. Finally, the column titles were bolded and underlined to differentiate between the headers and the data.      
![VBA_Challenge_2017](https://user-images.githubusercontent.com/104809098/169717268-aaf494dd-5d47-4e87-822c-f09bf0cec12b.pngwidth) ![VBA_Module_2017](https://user-images.githubusercontent.com/104809098/169717280-336da3f3-aa6d-4e78-9c3c-2b891ab05286.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/104809098/169717294-e525e570-3f6f-447b-ba13-06f3e5604768.png) ![VBA_Module_2018](https://user-images.githubusercontent.com/104809098/169717297-cf0b3ae4-308c-4fc7-8737-ddb0941fb274.png)

## Code Readability
The refactored code is easiers to read. The variables used have greater significancs to the data they are being refered to as shown below(tickers, tickerVolumes, tickerStartingPrices, and tickerEndingPrices) Vs (tickers, totalVolumes, startingPrices, and endingPrices).  Furthermore by using tickerIndex instead of ticker, you reduce the probability of getting an error in the code. This is due to having a clear differance between the indexing variable and the array variable.  
![VBA_Challenge_Code](https://user-images.githubusercontent.com/104809098/169717993-27cac0fa-62b9-4d52-8885-b00b924d9dd7.png)
![VBA_Module_Code](https://user-images.githubusercontent.com/104809098/169717997-10127671-5a1b-4b23-8f8b-24da078902e0.png) 


# Summary
While the reformated code has the same functionality as the Module code, it's overall better when it comes to Efficiency (By accounting for formatting)  and Code Readablity. This meets the requirements for this project.   
