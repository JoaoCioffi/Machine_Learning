COLAB DIRECT LINK:
<https://colab.research.google.com/drive/1z1pU5ujV4HwrzY-3rG70FO080efzMZTv?usp=sharing>



_______________________________________________
>>> Kickstarter Project - Crowdfunding Data
_______________________________________________

<https://www.kaggle.com/kemical/kickstarter-projects>

- Context: Kickstarter is a Crowdfunding platform. In this study we collected data using twitter.

- MetaData:

  - ID: internal Kickstarter id;
  - name: name of the project;
  - category: sub-category of the campaign;
  - main_category: general or "main" category of the campaign;
  - currency: currency used to support;
  - deadline: limit date stablished for the campaign;
  - goal: fundraising goal - The funding goal is the amount of money that a creator needs to complete the project;
  - launched: date campaign was launched;
  - pledged: total amount raised by "crowd";
  - state: current project status (i.e., canceled, successful, failed, etc);
  - backers: number of people donating to the project;
  - country: country where the capaign takes place;
  - usd_pledged: amount of money pledged converted to USD (according to Kickstarter's conversion) ;
  - usd_pledged_real: conversion in US dollars of the pledged column (conversion from Fixer.io API);
  - usd_goal_real: conversion in US dollars of the goal columns (conversion from Fixer.io API);


`Main Objectives:`
  - 1. Define the amount of data;
  - 2. What type(s) of variable(s) in each column?
  - 3. Describe numerical features:
    - (a) What are the total, the max, the min and the mean of the financial objective of all the Projects?
    - (b) What are the total, the max, the min and the mean of the raised money?
    - (c) What are the total, the max, the min and the mean of the Project Supporters?
  - 4. Describe the descriptive/categorical features:
    - (a) What is the most common 'category'? And how many unique values does it have?
    - (b) What is the most common 'Main_category'? And how many unique values does it have?
    - (c) What is the most common 'currency'? And how many unique values does it have?
    - (d) What is the most common 'country'? And how many unique values does it have?
  - 5. Verify Null values:
    - (a) How many null values are there in each category?
    - (b) What is the proportion of null values per non-null values in each feature?
  - 6. Graphical Analysis: Feature 'State' --> Barplot or Pie Chart that contains the quantity of each state
  - 7. Determine the percentage of each State present in the Dataset
  - 8. Graphical Analysis that contains the quantity of each state per 'main_category'
  - 9. From the previous graphic, select two 'main_category' to calculate the percentage of the state
  - 10. Analysis above the successful cases for the numerical features:
    - (a) What are the total, the max, the min and the mean of the financial objective of all the Projects?
    - (b) What are the total, the max, the min and the mean of the raised money?
    - (c) What are the total, the max, the min and the mean of the Project Supporters?
  - 11. Analysis above the successful cases for the categorical features:
     - (a) What is the most common 'category'? And how many unique values does it have?
     - (b) What is the most common 'Main_category'? And how many unique values does it have?
     - (c) What is the most common 'currency'? And how many unique values does it have?
     - (d) What is the most common 'country'? And how many unique values does it have?

`Extra Objective:`
- Build a model to predict (i) the amount of money pledged and/or (ii) if a project will be successful before it is released


---
# Main Libraries
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

<div style="display: inline_block"><br> 
    
</div>

---
