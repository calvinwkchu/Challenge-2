# Stock Analysis & Refactoring
## Overview of Project
The purpose of the analysis is to attempt at highlighting performance of various stocks in the dataset using VBA coding. The initial code is able to provide the analysis, while the refactored code provides upscalability & reusability for larger datasets.
## Results
Both codes were able to function as required for the analysis using different algorithims; it was found however, that the refactored code provided superior computing performance. The initial code uses a lookup of tickers and runs loops for each conditionals to match tickers based on the specified conditions provided. Below is a snapshot of the key logic in the code i.e. the ticker array & the loops to run the conditionals based on the ticker, and the computing time required to run the script. 

<img src="Resources/VBA_Challenge_Original.png"> 
<img src="Resources/VBA_Challenge_2017(original).png"> 
<img src="Resources/VBA_Challenge_2018(original).png"> 

The refactored code essentially runs the entire dataset once by assigning a unique value for each ticker and is used to separate that information. Below is the key logic in the code and the computing time.

<img src="Resources/VBA_Challenge_Refactored.png"> 
<img src="Resources/VBA_Challenge_2017.png"> 
<img src="Resources/VBA_Challenge_2018.png"> 

## Summary
In general, code refactoring provides benefits to making the script cleaner and more efficient to run. The disadvantage is the code may not be as easy to decipher as the initial logic is lost, leading to less understanding of what the code is achieving i.e. we only see the results, but we might not be able to easily figure out what we were trying to solve. For this exercise, the refactored code provided superior performance as we can see from the computing time differences. The downside of the refactored code is the logic isn't as easy to follow as the initial code, where the initial code walks you step by step as to what is being achieved.