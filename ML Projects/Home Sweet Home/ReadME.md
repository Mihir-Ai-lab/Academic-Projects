---
# **Introduction**

Company Introduction - Home Sweet Home

Our client for this project is an online marketplace for lodging, primarily home stays for vacation rentals, and tourism activities.Home Sweet Home (HSH) allows hosts to rent their homestays to other people as guests.

The company acts as a mediatory service for the same and has more than 80,000 hosts across 19 cities. Their goal is to provide the best hospitality service to their customers in a more unique and personalized manner.

Current Scenario

The company is planning to introduce a new system that will help to easily monitor and predict the rental prices of homes across various cities.

---

# **Problem Statement**

The current process suffers from the following problems:

- The company monitors and validates the prices set by the hosts.
- The process of validation is based on various factors such as city, neighborhood, neighborhood group, location on map, availability, and reviews.
- It is time-consuming, resource-consuming, and sometimes inaccurate to estimate the proper price based on so many factors.
- They want to supplement their analysis and prediction with a more feasible and accurate approach.


<p align="center"><img src="https://raw.githubusercontent.com/Mihir-Ai-lab/Academic-Projects/main/Images/House-price-prediction.gif"></p>

# **Project Details**

- Our Role: To build a regression model using the dataset.
- Project Deliverables: Predict the rental price of accommodation.
- Machine Learning Task: Regression
- Target Variable: Price
- Win Condition: No machine learning model in the company for this currently, therefore no quantifiable win condition. We just need to build the best possible model.
- Evaluation Metric: The model evaluation will be based on the RMSE score.

---
# **Data Acquisition & Description**

The dataset has columns describing features such as host id, hostname, listing id, listing name, latitude and longitude of listing, the neighborhood, room type, minimum number of nights, number of reviews, last review date, reviews per month, availability, host listings, and city.

Also included in the dataset is the column price which has the price of the rented accommodation.

The dataset is divided into two parts: Train and Test sets.

Train Set: The train set contains 137023 rows and 17 columns. The last column price is the target variable.

Test Set: The test set contains 34257 rows and 16 columns. The test set doesn’t contain the price column.

The Dataset contains the following columns:

|Id|Column Name|Description
|:--|:--|:--|
|1|host_id|	unique host Id|
|2|host_name|	name of the host|
|3|neighbourhood_group|	group in which the neighbourhood lies|
|4|neighbourhood|	name of the neighbourhood|
|5|latitude|	latitude of listing|
|6|longitude|	longitude of listing|
|7|room_type|	type of room|
|8|minimum_nights|	minimum no. of nights required to book.|
|9|number_of_reviews|	total number of reviews on the listing|
|10|last_review|	the date on which listing received its last review|
|11|reviews_per_month|	average reviews per month on listing|
|12|calculated_host_listings_count|	total number of listings by host|
|13|availability_365|	number of days in the year the listing is available for rent|
|14|city|	region of the listing|
|15|price|	price of listing per night|

---
# **Data Profiling & Pre-Processing**

- [Jupyter Notebook](https://github.com/Mihir-Ai-lab/Academic-Projects/blob/main/ML%20Projects/Home%20Sweet%20Home/Price%20Predictor.ipynb "Jupyter Notebook")
- [Pre-profile report](https://raw.githubusercontent.com/Mihir-Ai-lab/Academic-Projects/main/ML%20Projects/AE%20Corp/AEcorp_preprofile_report.html "Pre-profile report")
- [Post-profile report](https://raw.githubusercontent.com/Mihir-Ai-lab/Academic-Projects/main/ML%20Projects/AE%20Corp/AEcorp_postprofile_report.html "Post-profile report")
- [Presentation](https://raw.githubusercontent.com/Mihir-Ai-lab/Academic-Projects/main/ML%20Projects/AE%20Corp/AEcorp_postprofile_report.html "Presentation")

---
# **Submission**

The Client requested the Submission file with below mentioned conditions - 

- The submission file should be in the csv format.
- It should have 2031 rows.
- It should only have 2 columns, 1st column: REF_NO values, and 2nd column: predicted Revenue_Grid values.
- The submission file should not have column names in the first row.

Based on the requirments, the file was generated whichcan be viewed [here](https://github.com/Mihir-Ai-lab/Academic-Projects/blob/main/ML%20Projects/AE%20Corp/submission.csv "here")

---
# **Thank you**

- To look at other projects please [Click Here](https://github.com/Mihir-Ai-lab/Academic-Projects/tree/main "Click Here")
