Predict if the client will subscribe a bank term deposit (정기예금).

Data size

• train.csv: 32,950 rows × 21 columns (= 20 input variables + 1 output variable)

• test.csv: 8,238 rows × 20 columns (without output variable) • Missing values

• There are several missing values in some categorical attributes, all coded with the unknown label.

 Main metric: F-1 score

  Input variables: 
  
• Bank client data:

• 1 - id: client ID 

• 2 - age (numeric) 

• 3 - job : type of job (categorical: "admin.","blue-collar","entrepreneur","housemaid","management","retired","self-employed","services","student","technician","unemployed","unknown") 

• 4 - marital : marital status (categorical: "divorced","married","single","unknown"; note: "divorced" means divorced or widowed) 

• 5 - education (categorical: "basic.4y","basic.6y","basic.9y","high.school","illiterate","professional.course","university.degree","unknown") 

• 6 - default: has credit in default? (categorical: "no","yes","unknown") 

• 7 - housing: has housing loan? (categorical: "no","yes","unknown") 

• 8 - loan: has personal loan? (categorical: "no","yes","unknown") 

• Related with the last contact of the current campaign: 

• 9 - contact: contact communication type (categorical: "cellular","telephone") 

• 10 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec") 

• 11 - day of week: last contact day of the week (categorical: "mon","tue","wed","thu","fri") 

• Other attributes: 

• 12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
 
• 13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

• 14 - previous: number of contacts performed before this campaign and for this client (numeric)

• 15 - poutcome: outcome of the previous marketing campaign (categorical: "failure","nonexistent","success") 

• Social and economic context attributes 

• 16 - emp.var.rate: employment variation rate - quarterly indicator (numeric)

• 17 - cons.price.idx: consumer price index - monthly indicator (numeric) 

• 18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric) 

• 19 - euribor3m: euribor 3 month rate - daily indicator (numeric) 

• 20 - nr.employed: number of employees - quarterly indicator (numeric) 


• Output variable (desired target): 
• 21 – y: has the client subscribed a term deposit? (binary: "yes","no")
