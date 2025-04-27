# IS6812-Practice-Capstone
MSBA Practice Capstone Spring 2025 - Home Credit Default Risk

## Business Problem
Unbanked individuals struggle to get loans from trustworthy lenders which prevents them from owning property and establishing credit history. To properly serve this population, Home Credit needs to be able to predict their potential clients’ risk of defaulting. Accurately predicting the risk associated with each client will allow Home Credit to effectively serve an underserved population while increasing revenue and minimizing risk. 

## Project Objective
The project objective is to build a model using the available data that accurately predicts credit default in a vast majority of cases. Building a successful model will allow Home Credit to be able to confidently and safely extend loans to customers with non-traditional credit histories and thereby help the undercredited and unbanked population they aim to serve. 

## Project Difficulties
Our group faced several difficulties when approaching this problem. The first analytical challenge with this project was to take a highly-dimensional dataset and create a model that is not biased against the target underserved populations. To do this, it was important to use a combination of the provided credit scores and transactional data for those who do not have a credit score. Additionally, to decrease the dimensionality of the dataset, it was important to eliminate some of the columns and clean the data so that the remaining columns are an accurate representation of the sample. The final issue we ran into was some of our models did not perform well because of the highly imbalanced target variable. To combat this, we ended up downsampling and were able to build a robust gradient boost model that outperformed both our other models and the baseline logistic model we built. 

## Business Problem Solution
Our solution to the business problem was to build a robust gradient boost model that accurately predicts credit default in a vast majority of cases with a Kaggle AUC score of 0.74. This model is one that Home Credit can use to predict loan default given the customer's credit and transactional histories. This will allow them to safely extend loans to their target population - those with insufficient credit history for normal loan approval. 

## Solution Value
Our model will foster growth for Home Credit and allow them to safely extend loan opportunities to a previously underserved population allowing them to have access to the capital they need to thrive. The value of this endeavor for those underserved populations and their financial independence cannot be understated. Assuming the cost of a defaulted loan is about $190 USD and knowing that Home Credit extends an approximate 1.1 million loans each year, our model has the potential to save Home Credit about $61 million USD by accurately predicting credit default in 29% more cases than the baseline model. As a result, Home Credit can both increase their capital and provide needed financial services to individuals that might have otherwise been forced to turn to irreputable loan sources. 

## Conclusion
This project provided valuable experience in dealing with important real world problems, highly dimensional data, large numbers of missing values, and different modeling methods that had not yet been covered in my coursework. In particular, I was able to build RandomForest models for the first time which led to a greater appreciation for the power of black box modeling, decision trees, and the importance of hyperparameter tuning. This project also provided valuable professional group work experience as my group worked together to overcome the issues we encountered throughout the project. Overall, this project provided me with important learning experiences and improved my understanding of start to finish data analysis and the professional skills required to interpret and communicate actionable business insights. 
