# Stock_Analysis
VBA Challenge on refactored stock analysis code

## Overview of Project
Steve's parents are investing into Alternative Energy and they have invested all their funds into DAQO New Energy Corp without doing any research on the company or their stock prices, the DQ is what sold them since they met at a Dairy Queen. Steve has been tasked with reviewing the stock prices for DAQO since he is concerned about diversifying his parents portfolio. Using VBA we have assisted Steve in analysing not only DAQO stock prices, but also other green enerfy stocks. With the completion of our analysis, we have been tasked to assit Steve in expanding the research and looking into the entire stock market over the last few years and refactoring the code we wrote to run more efficiently using an expanded dataset. 
### Purpose
For this project, we have edited the code we have been working on to run more efficiently since we have now added more data to be analyzed. 
## Results
Upon refactoring the code, we ran it for the 2017 year and then ran it again for the 2018 year. 
The refactored code ran for .2460938 seconds for the 2017 year and all stocks reported a positive return expect TERP which reported a negative yearly return of -7.2%.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/101153028/159174804-297ef30d-3b52-416a-85b6-4a21b97244d9.png)

The code refactored code ran for .21875 seconds for the 2018 year and all stocks reported a negative return exceot for ENPH (which reported a positive 81.9% return) and RUN (which reported a positive 84.0% return).
With the orginial code, the analysis for 2017 ran for 1.375 seconds while the 2018 code ran for 1.370194 seconds.

![VBA_Challenge_2018](https://user-images.githubusercontent.com/101153028/159174827-1f29a49f-4d84-4b50-a46a-00493e8c8d8a.png)

## Summary
Refactoring/Editing Code
### What are the advantages and disadvantages of refactoring code?
#### Advantages of Refactoring code?
Refactoring code allows us the ability to take a code that is already working and tighten it up a bit to make it more a more efficient script to run.
It allows up to be able to clean up a code so that we can save time in the automation process. In some instances, saving time in running codes and also mean saving money for the individual/oraganization/company the code is for. 
In this case, we can also see that refactoring the code allowed for more data to be included in the analysis so it is more efficient for larger data sets. 
#### Disadvantages of Refactoring code?
While refactoring does have its clear advantages, there are also some things to consider while refactoring a code script. One disadvantage is that we are starting with an already working code and going in to refactor the code can be extermely time consuming and the outcome of a quicker run time is not always guaranteed. 
Another dissdvantage to refactoring code is that while it can potentially allow for larger data sets to be analyzed in a short amount of time, it it also may make it harder to clearly identfy errors when testing the code against those larger data sets. 
### How does these pros and cons apply to refactoring the original VBA script?
For this analysis, the biggest advantage in refactoring is that it did allow for a quicker analysis to be ran on the data set than the original code. For 2017 we went from a 1.375 second run time to a .2460938 run time and for 2018 we went from a 1.371094 run time to a .21875 run time. While this may seem too small to matter, that small differnece in time could save a company money and be able to provide better services to their clients. 
Refactoring gave us a cleaner and more efficient code and output when the code was applied. 
One disadvantage to this refactored code it that it took much longer to identify the errors when debugging. Since we started with an orginial code that already worked, it slowed down the refactoring process quite a bit.
