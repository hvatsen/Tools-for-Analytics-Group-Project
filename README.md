# Tools-for-Analytics-Group-Project
By Andree and Harish

This is Group 25's submission for the TFA Group Project. This github contains 2 notebooks, Top10.ipynb and Parking.ipynb.


Authors
-------------------
1. Andree Makahinda (abm2203)
2. Harish Vatsen (hv2228)



Top10.ipynb
-----------------------
In this notebook, we analyzed the top 10 causes of calls to 311 in 10025 area. The steps to do that are as follows.
- Reading the csv files and storing it to a variable called df
- Having a quick look at the df with df.info()
- Checking the first couple of rows of the df with df.head()
- Finding out all the columns in the df with df.columns
- Defining the zipcode (zipcode = 10025)
- Filtering the original df so that it only contains rows equals to the zipcode
- Defining the top 10 causes of the call in the filtered df using groupby function, count() method, loc identifier, and sort_values() method
- Assigning the results to a variable called top10
- Confirming the type of top10 variable where we expected it to be a pandas.Series
- Showing and checking the labels and values of the top10 pandas.Series



Parking.ipynb
-----------------------
In this notebook, we analyze whether illegal parking incidents are a larger fraction of total 311 incidents in the 10025 area than they are in general. The steps are as follows:
- Reading the csv files and storing it to a variable called df
- Checking whether the column 'Complaint Type' has null value or not
- Defining the zipcode as 10025
- Filtering the original df with zipcode= 10025, and creating a new filtered df
- Counting the total number of illegal parking, and the total number of complaints in the filtered df
- Counting the proportion of illegal parking vs the total number of complaints in the filtered df
- Counting the total number of illegal parking, and the total number of complaints in the original df
- Counting the proportion of illegal parking vs the total number of complaints in the filtered df
- Assigning the answer to whether the proportion in the filtered df is higher than that of original df

We find that the illegal parking incidents are _**not a larger fraction**_ of total 311 incidents in the 10025 area than they are in general.