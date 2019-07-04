Exploratory Data Analysis of non-cash transactions data of banks for the month of February 2019

Reserve Bank of India uploads the data of non-cash transactions like ATM, POS, Card every month on its portal. 
Data Source - https://rbi.org.in/scripts/ATMView.aspx?atmid=98

The data columns  has been described below - 
1. Bank Name
2. ATMs Onsite - Number of ATM deployed on site by the bank. On site means ATMs deployed in a bank branch.
3. ATMs Offsite - Number of ATM deployed off site by the bank. Standalone ATMs deployed in areas like stations, shopping malls, etc. where there is no bank branch nearby.
4. POS Online - Number of POS deployed online by the bank. POS stand for Point of Sale, where you use your card for a purchase, eg. in restaurants, malls, when you pay the bill on a card machine with a card. For more details, visit https://en.wikipedia.org/wiki/Point_of_sale
5. Credits cards outstanding at the end of the month - Total number of credit cards issued outstanding (after adjusting the number of cards withdrawan/cancelled).
6. CC No. of transactions ATM - Total number of financial transactions done by the credit card issued by the bank at ATMs
7. CC No. of transactions POS - Total number of financial transactions done by the credit card issued by the bank at POS terminals
8. CC Amount of transactions ATM - Total value of financial transactions done by the credit card issued by the bank at ATMs
9. CC Amount of transactions POS - Total value of financial transactions done by the credit card issued by the bank at POS terminals.
10. Debits cards outstanding at the end of the month - Total number of debit cards issued outstanding (after adjusting the number of cards withdrawan/cancelled).
11. DC No. of transactions ATM - Total number of financial transactions done by the debit card issued by the bank at ATMs
12. DC No. of transactions POS - Total number of financial transactions done by the debit card issued by the bank at POS terminals
13. DC Amount of transactions ATM - Total value of financial transactions done by the debit card issued by the bank at ATMs
14. DC Amount of transactions POS - Total value of financial transactions done by the debit card issued by the bank at POS terminals.
15. Total ATMs - Total number of ATMs(onsite and offsite) deployed by the bank.
16. trans_per_atm - Total number of transactions per ATM for the bank.

Payments Bank - A payments bank is like any other bank, but operating on a smaller scale without involving any credit risk. In simple words, it can carry out most banking operations but can’t advance loans or issue credit cards. Eg., PayTM Payments Bank, Airtel Payments Bank, etc. For more details, visit https://en.wikipedia.org/wiki/Payments_bank

Small Finance Bank - The Small Finance Bank (SFB) is a private financial institution intended to further the objective of financial inclusion by primarily undertaking basic banking activities of acceptance of deposits and lending to un-served and underserved sections including small business units, small and marginal farmers, micro and small industries and unorganised sector entities, but without any restriction in the area of operations, unlike Regional Rural Banks or Local Area Banks. For more details, visit https://en.m.wikipedia.org/wiki/Small_finance_bank

CRISP - DM :
https://www.datasciencecentral.com/profiles/blogs/crisp-dm-a-standard-methodology-to-ensure-a-good-outcome

https://towardsdatascience.com/yet-another-full-stack-data-science-project-a-crisp-dm-implementation-2943cae8da09
