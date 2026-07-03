## Data Understanding

### Overview

The dataset contains customer demographic, financial, employment, and contact information collected during the credit card application process. Each record represents one applicant and includes attributes that can influence the credit card approval decision.

### What the Dataset Helps Us Analyze

* Customer demographics
* Income distribution
* Employment status
* Education level
* Family status
* Housing type
* Property ownership
* Vehicle ownership
* Occupation
* Family size
* Communication details
* Factors affecting credit card approval

### Types of Variables

#### Customer Information

* ID
* Gender
* Age
* Occupation

#### Financial Information

* Annual Income
* Income Type

#### Family Information

* Marital Status
* Number of Children
* Family Members

#### Property Information

* Car Ownership
* Property Ownership
* Housing Type

#### Employment Information

* Employment Days
* Occupation Type

#### Contact Information

* Mobile Phone
* Work Phone
* Personal Phone
* Email

### Initial Observations

* The dataset contains both **categorical** and **numerical** variables.
* Customer age and employment duration are stored as **negative day values**, which need to be converted into readable years during data cleaning.
* Some columns use **binary values (0/1 or Y/N)** that can be transformed into user-friendly labels.
* Contact-related columns (phone, email, mobile) indicate customer communication availability.
* Income and employment information are expected to play a significant role in understanding applicant profiles.

### Business Questions We Will Answer

1. Which income group has the highest number of applicants?
2. What is the gender distribution of applicants?
3. Which occupation has the highest number of applications?
4. Which education level is most common?
5. Which housing type has the highest number of applicants?
6. How many applicants own a car?
7. How many applicants own property?
8. Which family status is most common?
9. What is the age distribution of applicants?
10. Which customer segments appear more suitable for credit card approval?

