## Customer Churn in Telecom Industry : Basic Data Analysis
What is customer churn? As per Wikipedia definition, customer churn, also known as customer attrition, customer turnover, or customer defection, is the loss of clients or customers. Customer churn rate is a key business metric in any industry and company providing services to end customers, because the cost of retaining an existing customer is far less than acquiring a new one.

In a highly competitive business landscape, the ever increasing rate of customer churn or attrition is a big challenge in front of telecom service providers today. It takes subtantial effort and investment to lure in new customers, while the danger of losing existing customers to competitors is always lurking. Hence, the importance to analyze and understand the reasons of customer's churn had never been felt more. The more the CSPs are able to retain their existing customer base, the better they will perform in the long run.

In this notebook, we will try to analyze the factors which contribute to the possibility of customer's churn. This analysis is performed based on the publicly available dataset from IBM.

## Telco Churn Prediction
The data set on telecom customer churn includes information about a fictional telecommunications company providing home phone and internet services to 7,043 customers in California during the third quarter. It indicates which customers have left the services, stayed, or signed up for the services.

## Business Problem
The development of a machine learning model that can predict customers likely to churn from the company is expected.

## Variables
CustomerId
Gender
SeniorCitizen: whether the customer is old (1, 0)
Partner: Whether the customer has a partner (Yes, No)
Dependents: Whether the client has dependents (Yes, No)
tenure: Number of months the customer stayed with the company
PhoneService: Whether the customer has phone service (Yes, No)
MultipleLines: Whether the customer has more than one line (Yes, No, No phone service)
InternetService: Customer's internet service provider (DSL, Fiber optic, No)
OnlineSecurity: Whether the customer has online security (Yes, No, No internet service)
OnlineBackup: Whether the customer has an online backup (Yes, No, no Internet service)
DeviceProtection: Whether the customer has device protection (Yes, No, No Internet service)
TechSupport: Whether the customer has technical support (Yes, No, No Internet service)
StreamingTV: Whether the customer has TV broadcast (Yes, No, No Internet service)
StreamingMovies: Whether the customer is streaming movies (Yes, No, No internet service)
Contract: Customer's contract period (Month to month, One year, Two years)
PaperlessBilling: Whether the customer has a paperless invoice (Yes, No)
PaymentMethod: Customer's payment method (Electronic check, Postal check, Bank transfer (automatic), Credit card (automatic))
MonthlyCharges: Monthly amount collected from the customer
TotalCharges: The total amount collected from the customer
Churn
