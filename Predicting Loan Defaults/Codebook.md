### Feature description

- id: Unique ID of the loan application.
- grade: LC assigned loan grade.
- annual_inc: The self-reported annual income provided by the borrower during registration.
- short_emp: 1 when employed for 1 year or less.
- emp_length_num: Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years.
- home_ownership: Type of home ownership.
- dti (Debt-To-Income Ratio): A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.
- purpose: A category provided by the borrower for the loan request.
- term: The number of payments on the loan. Values are in months and can be either 36 or 60.
- last_delinq_none: 1 when the borrower had at least one event of delinquency.
- last_major_derog_none: 1 borrower had at least 90 days of a bad rating.
- revol_util: Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.
- total_rec_late_fee: Late fees received to date.
- od_ratio: Overdraft ratio.
- bad_loan: 1 when a loan was not paid.