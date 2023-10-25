# Test_may

## Task 1 (Coffee)

A company engaged in wholesale coffee bean supplies has requested a report on monthly sales. They are interested in sales that did not have delivery: the number of such transactions per month, the percentage of negative reviews, and the profitability of such transactions, segmented by sales with and without customer-promo code input. There is a data export of all sales since the company's establishment.

You need to write Python code that reads the data export, performs the necessary calculations, and writes the result table to an Excel file.

Fields in the final table:

"Month" - "Promo Code Entered" - "Number of Transactions" - "Bad Reviews, %" - "Profitability, %."


## Task 2 (Optimal Mobile Operator Tariff)

A subscriber wants to optimize their communication expenses by changing their current tariff plan. Three mobile operators have sent their offers, and descriptions of all tariff plans are aggregated in a single document. There is also an export of the subscriber's outgoing calls for the last 6 months.

You need to analyze the nature of the subscriber's outgoing calls and suggest the optimal tariff, justifying your recommendations with analytical calculations.


## Task 3 (Landing Page Stat Test)

The marketing department has developed a new design for a landing page. Users of the website have evaluated the new design, and the results of the overall assessment are recorded in a quantitative variable called "Overall Score." The average score for the old design from the results of the previous study is 30 points.

You need to determine if the new landing page design has significantly improved, and whether there is an impact of age on the evaluation of the new design. You should answer these questions using statistical methods and provide recommendations to the marketing department based on the analysis.

## Task 4 (Model Building)

Description:

Build a model that predicts the probability of a customer defaulting on their payment in the next month.

You need to describe all the steps involved in building the model, such as data preprocessing, normalization, predictor selection, evaluation of model results, comparison of different models, and so on.

Input data:

The dataset contains information about default payments, demographic factors, credit data, payment history, and bill statements of customers with credit cards in Taiwan from April 2005 to September 2005. The name of the data file is "UCI_Credit_Card.csv."

Description of variables:

A total of 25 variables:

ID: ID of each customer

LIMIT_BAL: The amount of credit given in Taiwanese dollars (including individual and family/supplementary credit)

SEX: Gender (1 = male, 2 = female)

EDUCATION: (1 = graduate school, 2 = university, 3 = high school, 4 = others, 5 = unknown, 6 = unknown)

MARRIAGE: Marital status (1 = married, 2 = single, 3 = others)

AGE: Age in years

PAY_0: Repayment status in September 2005 (-1 = on time, 1 = one-month delay, 2 = two-month delay, ... 8 = eight-month delay, 9 = nine months or more delay)

[... The list continues for other variables ...]

default.payment.next.month: Default payment in the next month (1 = yes, 0 = no)
