# basic-steps-in-data-science
Steps of data science, those are being practiced by experienced data scientist in the industry

1. Understand the requirement i.e.  
	1. For a financial institution like a bank, the objective would be credit risk modeling i.e.  
		1. Find out bank should give the loan to a person or not, if yes than what should be the loan amount, interest rate, tenure, etc.  
		2. If the person will default or not  
		3. Sometimes we refer it as a hypothesis generation  
2. Data collection  
	1. Though this is a part of the research design, but sometime as a data scientist, you might have to collect the data, mostly through surveys and questionnaires.  
	2. It uses different sampling methodologies to do the surveys and fill the questionnaire. Through the sampling methods, one will decide the correct consumer base to get the data.  
	3. In most of the cases, data will be readily available.  
	4. In the case of a bank, it will have the data of past customers who have taken the loan.  
3. Understanding of data
	1. Once you have data, the next step is to understand the data i.e.  
		1. How many columns (variables) are there?  
		2. The data type of every variable, i.e. numeric, float, character, categorical  
		3. What each variable explain? i.e.  
			1. Age shows a person's age, which can be a deciding factor in providing the loan amount i.e. lower the age higher the amount and higher the age lower the amount.  
			2. Credit/Debit shows credit to debit ratio, which indicates a person's ability to repay the loan. Higher the ratio higher the credit and thus eligible to have more loan amount, lower the 					ratio lower the credit and thus not eligible to have the loan or might get the small loan amount.  
			3. Thus each variable has its own importance, which is a deciding factor of the model's performance.  
4. Descriptive Analysis of the data  
	1. This step provides insight into the data i.e.  
		1. Importance of each variable  
		2. Missing values if any in each variable  
		3. Outliers if any in each variable  
		4. The probability distribution of each variable [i.e. Normal, Binomial, Poisson, etc.]  
 		5. If a variable is categorical than how many categories are there in a variable  
		6. Is there any correlation between the different variables or not  
	2. It provides minute details of how the data is distributed and how much data required cleaning, how much data is important. 
5. Data Cleaning, Subsetting, and Manipulation  
	1. After having the knowledge of entire data and deciding the number of variables next step is to perform data cleaning, subsetting and manipulation task i.e.  
		1. Remove variables having missing values > 50%  
		2. If missing values are < 50% than impute missing values by mean, mode, median or by regression or random forest methods.  
		3. Remove outliers  
			1. Not in every case outliers are bad, sometimes they provide very useful information, so the decision of removing outliers can be very  
		4. In textual data, the steps can convert text to lower case, remove stop words, etc.  
	2. Data subsetting examples could be, 
		1. Select the data having "Age" below 45 years  
		2. Select the data having "Income" > 100K  
6. Exploratory Analysis / Predictive Analysis / Visual Analytics  
	1. Based on the requirement perform exploratory analysis or predictive analysis  
	2. The visual analysis will be mainly for reports presentation, KPI charts, and other BI charts presentation  
	3. Predictive analysis will be used to find out future events based on the data of past events  
		1. Here we will train the model on past data and based on this learning model will predict future events  
7. Model evaluation, validation  
	1. After model building, the next step is to find out how well is model performing? If the model is able to perform well that is if the model is able to predict the future event well than finally put it 			in the production and if not than again start with step-2 or step-3.  
	2. The main reason for a model not performing well is either the case of underfitting or overfitting. We will discuss these later but for now underfitting means model has not understood the data very 		well and overfitting means the model has learned more about data than it requires which is being called as noise  
8. Production and Report Preparation  
	1. The final step is to put the model in production and prepare reports with the help of visualization i.e. different charts.  
