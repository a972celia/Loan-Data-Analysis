
<h1 align="center"> Lending Club Loan Analysis </h1> 

## Introduction
Typically, commercial and non-commercial banks are the main lenders for loans. In contrast of those, Lending Club (LC) is a peer-to-peer online lending  platform.  It  is the  world’s largest  marketplace connecting  borrowers and  investors, where consumers and small business owners lower the cost of their credit and enjoy a better experience than traditional bank lending, and investors earn attractive risk-adjusted returns.

## Data Source 
For companies like Lending Club correctly predicting whether or not a loan will be a default is very important. In this project, using the historical data from 2007 to 2015, you have to build a deep learning model to predict the chance of default for future loans. As you will see later this dataset is highly imbalanced and includes a lot of features that make this problem more challenging.


## Data Analysis

- Bad loans consist 13.14% of total loans but remember that we still have current loans which have the risk of becoming bad loans. (So this percentage is subjected to possible changes.)
- The <b> NorthEast </b> region seems to be the most attractive in term of funding loans to borrowers.
- The <b> SouthWest </b> and <b> West</b> regions have experienced a slight increase in the "median income" in the past years.
- Average interest rates have declined since 2012 but this might explain the increase in the volume of loans.
- Employment Length tends to be greater in the regions of the SouthWest and West
- Clients located in the regions of NorthEast and MidWest have not experienced a drastic increase in debt-to-income(dti) as compared to the other regions.



## Implementation

Feature Engineering and implement Neural Network model


### Summary:

- **Bad Loans Count:** People that apply for educational and small business purposed tend to have a higher risk of being a bad loan. (% wise) 
- **Most frequent Purpose:** The reason that clients applied the most for a loan was to consolidate debt.
- **Less frequent purpose:** Clients applied less for educational purposes for all three income categories.
- **Interest Rates:** In all reasons for application except (medical, small business and credi card), the low income category has a higher interest rate. Something that could possibly explain this is the amount of capital that is needed from other income categories that might explain why the low income categories interest rate for these puposes are lower.
- **Bad/Good Ratio:** Except for educational purposes (we see a spike in high income this is due to the reasons that only two loans were issued and one was a bad loan which caused this ratio to spike to 50%.), but we can see that in all other purposed the bad good ratio is lower the higher your income category.


