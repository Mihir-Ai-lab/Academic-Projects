---
# **Introduction**

Company Introduction - E-Corp

Our client for this project is a multinational technology company.

- ECorp is an American multinational technology company that focuses on e-commerce, cloud computing, digital streaming, and artificial intelligence.
- They are spread across the globe with hundreds of thousands of employees in these domains.
- When an employee at any company starts working, they first need to obtain the resource access necessary to fulfill their role.
- Employees passing certain criteria regarding their primary and secondary roles are granted access to the requested resources.
- This efficient system has helped the company maintain background checks of its employees and usage of allocated resources.

Current Scenario

A group of employees has been invited to test the automated system. An auto-access model seeks to minimize the human involvement required to grant or revoke employee access.

---

# **Problem Statement**

The current process suffers from the following problems:

- If an employee discovers that they need access to certain resources, they are supposed to contact a knowledgeable supervisor.
- The supervisor takes time to manually grant the needed access to the requesting employee.
- As employees move throughout a company, this access discovery/recovery cycle wastes a non-trivial amount of time and money.

They want to automate the process of approving or revoking access to a resource according to their role in the company.

<p align="center"><img src="https://raw.githubusercontent.com/Mihir-Ai-lab/Academic-Projects/main/Images/Access%20Control.gif"></p>

# **Project Details**

- Our Role: To build a binary-class classification model using the dataset.
- Project Deliverables: Employee Access Classification.
- Machine Learning Task: Classification
- Target Variable: ACTION
- Win Condition: N/A (best possible model)
- Evaluation Metric: The model evaluation will be based on the Accuracy Score.

---
# **Data Acquisition & Description**

We are given a dataset containing the ACTION (ground truth), RESOURCE, and information about the employee's role at the time of approval.

The model will take an employee's role information and the requested resource in the form of a resource code and will determine if an employee should be given access or not.

The dataset contains all the necessary information about an Employee like their ID and roles in the company, their Manager’s ID, RESOURCE id, and the ACTION.

The data consists of real historical data collected from 2010 & 2011. Employees are manually allowed or denied access to resources over time.

The dataset is divided into two parts: Train, and Test sets.

- Train Set: The train set contains 24576 rows and 11columns.

- Test Set: The test set contains 8193 rows and 10 columns.

- The Dataset contains the following columns:

|Id|Feature|Description|
|:--|:--|:--|
|01|RESOURCE|	An ID for each resource.|
|02|MGR_ID|	The EMPLOYEE ID of the manager of the current EMPLOYEE ID record; an employee may have only one manager at a time.|
|03|ROLE_ROLLUP_1|	Company role grouping category id 1 (e.g. US Engineering).|
|04|ROLE_ROLLUP_2|	Company role grouping category id 2 (e.g. US Retail).|
|05|ROLE_DEPTNAME|	Company role department description (e.g. Retail).|
|06|ROLE_TITLE|	Company role business title description (e.g. Senior Engineering Retail Manager)|
|07|ROLE_FAMILY_DESC|	Company role family extended description (e.g. Retail Manager, Software Engineering)|
|08|ROLE_FAMILY|	Company role family description (e.g. Retail Manager).|
|09|ROLE_CODE|	Company role code; this code is unique to each role (e.g. Manager)|
|10|ID|	ID of the Employee|
|11|ACTION|	ACTION is 1 if the resource was approved, 0 if the resource was no.|

---
# **Data Profiling & Pre-Processing**

- [Jupyter Notebook](https://github.com/Mihir-Ai-lab/Academic-Projects/blob/main/ML%20Projects/E-corp/Automatic%20Access%20Authorization.ipynb "Jupyter Notebook")
- [Presentation](https://raw.githubusercontent.com/Mihir-Ai-lab/Academic-Projects/main/ML%20Projects/AE%20Corp/AEcorp_preprofile_report.html "Presentation")
 
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
 
