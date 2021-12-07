# stock-analysis

# Overview of Project
## Background
### The green stocks dataset contains stock data for companies that use green energy. We are using this dataset to analyse which stocks are best to invest in, meaning they have a positive return rate. From the green stocks data set, we will use the data to condense information into Ticker's name, Total Daily Volume, and Return Rate, so that we can analyze which stocks are optimal for investing. 

## Purpose
### The purpose of our stock analysis is to analyze the stock markets fluctiations to chose which stock to invest in. We used VBA to execute an analysis that will execute more quickly and provide us with prompter results. Our VBA code will be able to provide an analysis on any year that we have data on, and provide an ouput that includes Ticker, Total Daily Volume, and Return Rate, which we will analyze. 

## Results 
### From the photos below, our first assumption is that the stock market performance is more favorable than the one in 2018. In particular, nine different stocks shifted from a positive return rate in 2017 to a negative return rate in 2018: AY, CSIQ, DQ, FLSR, HASI, JSK, SEDG, SPWR, VSLR. We can conclude that ENPH and RUN continued to provied a positive return rate from 2017 to 2018, whereas TERP stayed with a negative return rate. From this year to year analysis, the top two optimal green energy stocks to invest in would be RUN and ENPH.
<img width="322" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/94096530/144967807-79c8e7eb-5083-4d26-aee5-7aeaa1b2a544.png">
<img width="316" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/94096530/144967811-c40f0ded-635c-4bf9-91b7-3e245283fb79.png">
### You can also see that our execution for the year 2017 was done in 0.1015625 seconds and in the year 2018 it was executed in 0.09375 seconds. Our code was executed much faster when it was refactored. 

## Summary 
### In summary, the pros of refactoring code in general are faster execution, ability to catch bugs that are in the original coe, and improvement of structure of the design code to be more easily read. Faster execution is important because we are able to get our results faster and in less steps. Ability to catch bugs is helpful in finding errors and simplifying code compared to the original version. However, refactoring code can be risky when it is not refactored correctly. This can cause bugs in the code which leads to an incorrect execution of our data.

### For the dataset we used in this analysis, we were able to improve the speed of execution by refactoring our code and maintaining the same output. However, if we were to loop through the data multiple times and there was a bug, that would allow for potential erros in our execution and overall analysis. We did not run into this issue, however, since we only had a single loop.  
