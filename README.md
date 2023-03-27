# Lead_Score_CaseStudy-Logistic_Regression
Build a logistic regression model to assign a lead score to each of the leads which can be used by the company to target potential leads.

# Problem Statement
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.
When these people fill up a form providing their email address or phone number, they are classified to be a lead. By making calls, writing emails, etc, some of the leads get converted while most do not. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance.

# Goal
Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate questions pdf file.

# Dataset 
'Lead.csv' dataset has been provided from the past with around 9000 data points along with a data dictionary. The dataset consists of various attributes including the target variable, in this case, is the column ‘Converted’ wherein 1 means it was converted and 0 means it wasn’t converted.

