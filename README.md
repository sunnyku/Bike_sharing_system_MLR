# Bike Sharing System
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


## Table of Contents
* [Problem Statement](#problem-statement)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Approach and Analysis
- Understanding and Data cleaning
  -  Understanding what each columns represents
  - Dropping columns which cannot be used, having null values, no variation etc.
  - imputing missing values, removing duplicates, and correcting inconsistencies.
- Analysing the data
  - Univariate Analysis
  - Bivariate Analysis
  - Multivariate and segmented Analysis
- Conclusion
  - Drawing observations and recommendations based on the data  


##  Recommendation and Conclusions
- The following segments seem to have strong influence on defaults :
  - purpose (small business is more likely to default)
  - grade (lower grades are more likely to default)
  - addr_state (some states are more likely to have high defaults)
  - delinq_2yrs (higher values seem to have more)
  - inq_last_6_months (probability of default increases with number of inq)
  - term (36 month loan has high probability of full payment)
  - pub_rec_bankrupcies/pub_rec (individuals reporting higher values can lead to defaulting)
  - loan_amnt (Higher rates can increases the probability of person defaulting)
  - int_rates(majority of the interest rate is in the range of 5% to 15%  and the Very High interest rates are in more likely to default which is greater than 15%)
- The following segments seem to have Low/No influence on loan defaults :
  - verfication_status
  - emp_length
  - home_ownership
  - installments
  - issue_d
  - total_acc
  - total_rec
  - dti
  - home_ownership


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python - Version 3.12.3](https://www.python.org/download/releases/3.0/)
- [numpy - Version 1.26.4](https://github.com/numpy)
- [pandas - Version 2.2.2](https://github.com/pandas-dev/pandas)
- [matplotlib - Version 3.9.0](https://github.com/matplotlib)
- [seaborn](https://github.com/seaborn)
- [Jupyter Notebook - Version 7.2.0]()
- 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Team
- Sunny Kumar
## Contact
Created by [@sunnyku] - feel free to contact me


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
