#Loan Evaluation
Banking transactions of existing few bank customers are taken into consideration.
Following evaluations are performed before applying for loan such as-
Account is present in existing customer list or not. If not, then need to open an account.
Age should be less than 60.
Credit score should be greater than 5.
Occupation should not be ‘NA’
Last 3 transactions of the customer should be greater than or equal to atleast initial amount(i.e. $7000)
If the above conditions are satisfied then the customer is eligible for loan.

#Loan Amortization
When the customer is eligible for loan, amortization has its condition such as-
After taking loan, 20% of the balance atleast, should be kept in the bank.
If 20% of the balance is less than $7000, then the customer should reduce the loan amount.
If the above condition is satisfied, verify as to which criteria the loan amount fits into using the “Bank Details” spreadsheet.
As per Bank norms, the rate of interest, no. of years are taken and evaluation of Principal amount and monthly payment is done.

#Datasets
Bank Customer Transaction Dataset is not easily available, hence I have created a new dataset of customer transactions and bank details.
Few test cases are considered.(We can add more if needed).At the end a loan calculation dataset is created monthwise.

#Other Technical Terms
In loan amortisation, few inbuilt functions are used to calculate the principal amount, interest calculation, monthly balance.
Inbuilt functions such as –
pmt
ipmt
pv
ppmt
Link for reference-[https://docs.scipy.org/doc/numpy/reference/index.html](https://docs.scipy.org/doc/numpy/reference/index.html)

#Graph Plotting
There are three graphs plotted
Scatter Chart - Customer Transaction History(Yearly)
Line graph- Showing the ending balance with the increasing year
Bar chart – Showing the ratio between principal and interest. 

