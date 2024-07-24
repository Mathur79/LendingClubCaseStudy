**#LendingClubCaseStudy **

**Problem Statement:**  Analyze the banking and financial services data (prior history) and derive insights to minimize the risk of losing money while lending to future customers. The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.
When a person applies for a loan, there are two types of decisions that could be taken by the company:

    Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

	Fully paid: Applicant has fully paid the loan (the principal and the interest rate)	Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.	Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

    Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company

**Objective**:  
Company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.

**Findings**

a) Most of the Loans were given for the purpose of Purpose

b) Per Data: The Company Started giving loans from 2007 and we see an increasing trend year on year on the count of loans given until 2011 (data provided is until 2011). 2011 saw the highest number of loans given

c) 70% of the Loans given over a 36 Month Installment compared to 60 Months

d) Grade A,B, C were given the highest number of Loans (by count)


**Conclusions**
a) Higher the Loan Amount, greater the risk for being charged off (we see this esp with high amounts that fall in outlier category) (Refer Chart: "Loan Amount VS Loan Status")

b) Loans with 36 Months Duration have high chance of getting paid back compared to 60 Months (Refer Chart: "Loan Duration VS Loan Status")

c) High Loan Amounts have higher probability of tetting Fullpaid. Loan Amounts in the range 5000 to $10000 have high risk of getting into ChargedOff State (Refer Chart: "Loan Amount Trend VS Loan Status")

**Important Conclusions**
a) Loans given Sub Grade F4 and G4 Customers, have ~40% Chance of getting charged off (Refer Chart: "Charged off % by SubGrade")

b) Customers who are not providing their Employment Length have highest probability of getting their loan Charged off (~25% Chance) (Refer Chart: Charged off % by Grade) (Refer Chart: "Charged off % by Employment Length")

c) Cusotmers with more than 1 pub_rec_bankruptcies are likely to get their loan charged off (~30% Chance) (Refer Chart: "Charged off % by pub_rec_bankruptcies"

