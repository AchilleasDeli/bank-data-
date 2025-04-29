
# bank-data-


Data Description:
The file Bank.xls contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

Domain:Banking

Context:
This case is about a bank (Thera Bank) whose management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget.

Learning Outcomes:

Exploratory Data Analysis
Preparing the data to train a model
Training and making predictions using a classification model
Model evaluation
The classification goal is to predict if a  liability customer will buy personal loans.
About this file

Suggest Edits
Attribute Information:

ID : Customer ID

Age : Customer's age in completed years

Experience : #years of professional experience

Income : Annual income of the customer ($000)

ZIP Code : Home Address ZIP code.

Family : Family size of the customer

CCAvg : Avg. spending on credit cards per month ($000)

Education : Education Level.
1: Undergrad;
2: Graduate;
3: Advanced/Professional

Mortgage : Value of house mortgage if any. ($000)

10.Personal Loan : Did this customer accept the personal loan offered in the last campaign?

11.Securities Account : Does the customer have a securities account with the bank?

12.CD Account : Does the customer have a certificate of deposit (CD) account with the bank?

13.Online : Does the customer use internet banking facilities?

14.Credit card : Does the customer use a credit card issued by


##  Project Workflow
- Data Exploration & Cleaning
- Feature Selection & Encoding
- Logistic Regression Modeling
- Evaluation using accuracy and confusion matrix

##  Machine Learning Approach
- **Model Used**: Logistic Regression (binary classification)
- **Train/Test Split**: 70/30
- **Evaluation Metrics**: 
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1)



##  Tools & Technologies
- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook



### Prerequisites
You will need Python and the following libraries installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

##RUNNING THE PROJECT
git clone https://github.com/AchilleasDeli/bank-data-.git
cd bank-data-
jupyter notebook bank.ipynb


