---
# **Introduction**

Company Introduction - AE Corp

Our client for this project is a retail banking institution.

- They are going to float a stock trading facility for their existing customers.
- The idea is to use data to classify whether a customer belongs to a high net worth or low net worth group.
- They will have to incentivize their customers to adopt their offerings.
- One way to incentivize could be to offer discounts on the commission for trading transactions.

Current Scenario

The company rolled out this service to about 10,000+ of its customers and observed their trading behavior for 6 months and after that, they labeled them into two revenue grids 1 and 2.

---

# **Problem Statement**

The current process suffers from the following problems:

- Only about 10% of the customers do enough trades for earnings after discounts to be profitable.
- The company wants to figure out, which are those 10% customers so that it can selectively offer them a discount.

# **Project Details**

- Co-ordinating with - The marketing department to supplement their campaigns with a more proactive approach.
- Our Role - To build a classification model using the datasets.
- Project Deliverables - Predict whether a customer belongs to a high net worth or low net worth group.
- Machine Learning Task: Classification
- Target Variable: Status (high net worth (1) / low net worth (2))
- Win Condition - No machine learning model in the company for this currently, therefore no quantifiable win condition. We just need to build the best possible model.
- Evaluation Metric - The model evaluation will be based on the F1 Score score.

---
# **Data Acquisition & Description**

We are provided with a dataset containing all the necessary information about the customers like their occupation, family income, gender, region, balance transfer, children, etc.

Also included in the dataset is the column Revenue_Grid which classifies the customers into high net worth customers (1) and low net worth customers (2).

This is the data that we have to predict for future customers.

- Train Set: The train set contains 8124 rows and 32 columns.The last column Revenue_Grid is the target variable.

- Test Set: The test set contains 2031 rows and 31 columns.The test set doesn’t contain the Revenue_Grid column which need to be predicted

- The Dataset contains the following columns:


|Id|Feature|Description|
|:--|:--|:--|
|01|REF_NO| Reference Number of the customer.|
|02|children|Number of children each customer has.|
|03|Age_band|Age Group to which the customer belongs.|
|04|status|Marital Status of the customer.|
|05|occupation|Job or profession of the customer.|
|06|occupation_partner|Job or profession of the customer's partner.|
|07|home_status|Home Status of the customers.|
|08|family_income|Income Range of the customer's family.|
|09|self_employed|Whether self-employed or not.|
|10|self_employed_partner|Whether the partner self-employed or not.|
|11|year_last_moved|Moving Year from the last location of the customer.|
|12|TVarea|Television Region of the customer.|
|13|post_code|Postal Code of the customer.|
|14|post_area|Postal Area of the customer.|
|15|Average_Credit_Card_Transaction|Average Credit Card Transaction per year by the customer.|
|16|Balance_Transfer|Transfer of the Balance in an account to another account by the customer.|
|17|Term_Deposit|Cash Investment Help at Financial Institute provided to the customer.|
|18|Life_Insurance|Basic Life Insurance Coverage of the customer.|
|19|Medical_Insurance|Medical Insurance Coverage of the customer.|
|20|Average_A/C_Balance|Average Balance in the account of the customer.|
|21|Personal_Loan|Amount of Personal Loan taken by the customer.|
|22|Investment_in_Mutual_Fund|Amount Invested in Mutual Funds by the customer.|
|23|Investment_Tax_Saving_Bond|Amount Invested in Tax Saving Bond by the customer.|
|24|Home_Loan|Amount of Home Loan taken by the customer.|
|25|Online_Purchase_Amount|Amount spent by the customer on online purchases.|
|26|gender|Gender of the customer.|
|27|region|Religion of the customer.|
|28|Investment_in_Commudity|Amount Invested in Commodity by the customer.|
|29|Investment_in_Equity|Amount Invested in Equity by the customer.|
|30|Investment_in_Derivative|Amount Invested in Derivatives by the customer.|
|31|Portfolio_Balance|Balanced Investment Strategy of the customer.|
|32|Revenue_Grid|Grid report of the customers.|

---
# **Data Profiling & Pre-Processing**

- [Jupyter Notebook](https://github.com/Mihir-Ai-lab/Insaid/blob/main/ML%20Projects/AE%20Corp/Customer%20Classification.ipynb "Jupyter Notebook")
- [Pre-profile report](https://raw.githubusercontent.com/Mihir-Ai-lab/Academic-Projects/main/ML%20Projects/AE%20Corp/AEcorp_preprofile_report.html "Pre-profile report")
- [Post-profile report](https://raw.githubusercontent.com/Mihir-Ai-lab/Academic-Projects/main/ML%20Projects/AE%20Corp/AEcorp_postprofile_report.html "Post-profile report")

---
# **EDA & Summarization**

- [Power Point Presentation status WIP](https://docs.google.com/presentation/d/1CsFG0YeROn1KKJ1SeQewDlud5mIkT2N/edit?usp=drivesdk&ouid=105176624273780999067&rtpof=true&sd=true "Power Point Presentation")
- [Presentation Video status WIP](https://youtu.be/pVU2uqi4Kw "Presentation Video")

---
# **Thank you**

- To look at other projects please [Click Here](https://github.com/Mihir-Ai-lab/Academic-Projects/tree/main "Click Here")
 
