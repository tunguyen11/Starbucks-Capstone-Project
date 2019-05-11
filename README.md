# Starbucks-Capstone-Project

## Project Overview 
Starbucks data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app that includes the transactions and offers events. This project's objective is analyzing data to optimize the promotion offer sending to customer. 

## Installation 
This project need the following libraries to be installed: 
* pandas
* sklearn
* pandasql
* matplotlib 
* seaborn 
* json 

## Files
### Jupyter Notebook 
Jupyter Notebook: The project contains a Jupyter notebook where all the technical sides of the project have been conducted. I follow the CRISP-DM method for, preparing, analyzing, model and visualizing data. 

### Data 
Three JSON files that show profiles of customers, promotional deals that are offered, and the transaction history of customers.

portfolio.json: contains Information about the promotional offers that Starbucks can send to customers including the promotional type, duration of promotion, reward, and how the promotion was distributed to customers
id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - UNKNOWN
channels (list of strings)

profile.json: Contains customer information including their age, salary, and gender
age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income
transcript.json:  Including all event happend including promotional offers that a customer received, viewed, and completed, and the transaction that customer made during the period of 30 days.
event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record

