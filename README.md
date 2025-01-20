# data-quality-pipeline

In this repository, I have implemented some of the Snowflake Notebooks to perform Data Quality Analysis on the REST data.

## Objective
The main goal of these Snowflake Notebooks is to identify trends of the known issues identified on the data collected by our front-end. Working with these notebooks helped us improve the data quality, minimizing discrepancies of missing data. These Notebooks can be used as daily monitors that can be automated and sent via email to the main stakeholders.

The notebooks are customized to the specific data collection implemented in the company

- **DQP User Engagement Summary**
  - File: "DQP - UES.ipynb"
  Description: Here, we have a set of functions that analyze the data collected on the exit events triggered and their attributes.
 
- **DQP Video View Ended**
  - File: "DQP - VVE.ipynb"
  - Description: Here we have a set of functions that analyze the data collected on the exit event triggered when the video ended playing or the user closed the player.

- **DQP Marketing Processing Rules**
  - File: "DQP - MKT Rules Validation.ipynb"
  Description: Based on the different UTM attributes collected, we classify the user to track and understand the behavior of the company's different marketing campaigns. The goal of this Notebook is to validate the data collected (at REST) and verify if the rules applied on the front end are working as expected.
  - This monitor provides quick insights into any incidence based on the values of the UTM attributes.

