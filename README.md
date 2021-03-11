# Loan-Delinquency-Prediction-Intermediate
Loan default prediction is one of the most critical and crucial problem faced by financial institutions and organizations as it has a noteworthy effect on the profitability of these institutions. In recent years, there is a tremendous increase in the volume of non – performing loans which results in a jeopardizing effect on the growth of these institutions.  Therefore, to maintain a healthy portfolio, the banks put stringent monitoring and evaluation measures in place to ensure timely repayment of loans by borrowers. Despite these measures, a major proportion of loans become delinquent. Delinquency occurs when a borrower misses a payment against his/her loan.  Given the information like mortgage details, borrowers related details and payment details, our objective is to identify the delinquency status of loans for the next month given the delinquency status for the previous 12 months (in number of months).

<img src="https://user-images.githubusercontent.com/51187449/110749915-bbdd0a80-8267-11eb-96a5-df96df1daa4a.PNG" width="400">

## Find attached a Powerpoint Presentation explaining in detail the approach taken to solve this use case.
The various Banking terms are explained in the Presentation.

### Approach:
>This was a project which gave me the maximum opportunity to experiment with Binary classification and has now given me the confidence to further deal with other classification problems. 
>I experimented with:
- different feature processing,
>1. Normalization VS Standardization
>2. Dropping columns and checking its effect on the model
>3. One-Hot-Encode VS LabelEncode
- different methods of sampling the imbalanced dataset,
>1. RandomUnderSampler
>2. RandomOverSampler
>3. SMOTE Oversampling
>4. ADASYN Oversampling
- different train and validation split methods,
>1. Hold-Out Method
>2. StratifiedKFold 
- and different models
>1. Logisticregression
>2. DecisionTrees
>3. Random Forest
>4. XGBoost
>5. AdaBoost
>6. LightGBM 
#### After having scrutinized the problem and the different approaches, I boiled down to this single approach presented in the jupyter notebook uploaded in this repository. I am open to feedback and discussions on this repository on my [LinkedIn](https://www.linkedin.com/in/manpreet777/)

### Evaluation Metric Submissions for this problem statement were evaluated on F1-Score between the predicted class and the observed target.
