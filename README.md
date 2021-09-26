# Credit-EDA-Case-Study

## Business Objective:

This case study aims to identify patterns which indicate if a client has difficulty paying their instalments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study. In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

## Approach Taken:

- In Application dataset there are 307511 rows and 122 columns.
- Columns that have missing values more than 50% are dopped as columns with that much of missing values may not be helpful to depict the insight. After dropping such columns, there are 81 columns in the dataset.
• It can be seen for days columns; the values are in negative so we those were converted into positive values.
• Few columns denotes Number of enquires, count of family members, no. of social media connects and no. of days. So, these columns can not be in float, so these columns were also converted in integers.
• There are few columns having integer types but contains categorical data. Converting these columns into data type object is required to perform univariate and bivariate analysis properly. We checked columns having less unique values (most of those are Flag columns) and converted those columns into object type.
• Columns having less than 14% Missing Values were analyzed and suitable imputation methods have been mentioned in next slide.
• Application data has been divided into two datasets one where TARGET=1 (client with payment difficulties) and one where TARGET=0 (Other clients).
• Then outlier detection, univariate analysis, bivariate analysis, correlation analysis are performed.
• For Previous Application data same analysis has been performed.
• At the end Conclusion, Important insights are provided.

## EDA Report / PPT:

https://github.com/anikch/Credit-EDA-Case-Study/blob/main/EDA_Case_Study.pdf

## Jupyter Notebook:

https://github.com/anikch/Credit-EDA-Case-Study/blob/main/Credit_EDA.ipynb
