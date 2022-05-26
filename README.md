# VBA Stock Analysis
## Overview
### The purpose of this project was to analyze the performance of different stocks to identify trends.  It was meant to identify efficiencies in how to pull the data form the dataset.

## Results

### 2017 Analysis
#### 2017 Refactored Data with Formatting
<img width="254" alt="image" src="https://user-images.githubusercontent.com/104801614/170421475-ae4096e8-ec16-4aa8-b82c-736eb08fbc17.png">

#### In general, the stock market appears to have done very well in 2017.  Nearly all of the stocks recorded positive returns, with the exception of TERP.  DQ and SEDG had the largest positive returns by percentage, but they also had two of the smaller total trading volumes.  This could indicate that their performance could be more volatile in the future.  

### 2018 Analysis
### 2018 Refactored Data with Formatting
<img width="207" alt="image" src="https://user-images.githubusercontent.com/104801614/170421597-99bee6ec-0050-465f-bb2a-2a05da18cc3e.png">

#### In 2018, the market performed much worse than in 2017.  Nearly every stock recorded a negative return, with ENPH and RUN being the only two to have positive returns on the year.  It is also useful to know that those two tickers had two of the highest Total Daily Volume, which should give some confidence in their performance going forward.
### Comparison of Refactored Performance vs. Original Code
#### The performance of the script was greatly sped up by not sorting through the entire dataset when identifying the ending value.  For comparison, the new script ran in .119 seconds compared to .742 seconds for the 2017 data, and .121 vs. .702 seconds for the 2018 data.  

### 2017 non-refactored run time
<img width="256" alt="image" src="https://user-images.githubusercontent.com/104801614/170421427-6c93711a-5954-4512-b44c-332b00693aff.png">

### 2018 non-refactored run time
<img width="248" alt="image" src="https://user-images.githubusercontent.com/104801614/170421867-2c22906e-1417-4a1f-8c5c-7bef4f6c86a9.png">

## Summary
### The advantages of the refactored code is that the script will run nearly 5x faster than the orginal script.  It was also proofread to make sure that the code is performing the tasks that the user wants.  Because of the greater processing speeds, the refactored code could enable analysis of much larger datasets in a shorter amount of time.  A disadvantage of this particular refactored code is that there could be errors if the data is not sorted by stock ticker and date before the macros are run.  In both cases, the code also requires the user to input how many stock tickers there are in the dataset into an array, which is time consuming and should try to be automated
