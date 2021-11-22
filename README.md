## **Amazon_Vine_Analysis**

## Overview of the analysis: 

The main goal is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Software: 

PySpark (Python), Pandas(Jupyter Notebook), PostgreSQL (PgAdmin), Amazon Web Services (RDS) and Google Colab Notebooks.

## Results:

The first part of the analysis was conducted through Google Colab Notebooks and Amazon Web Services (AWS) using PySpark and PgAdmin. The code can be found here: [Deliverable 1](https://github.com/chocoplace/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb). From the process we were able to export a table later use for deliverable 2 (Vine Table). 

The second part of the analysis was conducted on Pandas. Check the code here: [Deliverable 2](https://github.com/chocoplace/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)  A dataframe was created and later analyze to find the following results:

  - How many Vine reviews and non-Vine reviews were there? 39,376 total votes 
  - How many Vine reviews were 5 stars? 65 were 5 star reviews from the Vine program 
  - How many non-Vine reviews were 5 stars? 20,612 were 5 star  reviews from the non-Vine program 
  - What percentage of Vine reviews were 5 stars? 38.23% reviews were from the Vine program
  - What percentage of non-Vine reviews were 5 stars? 54.47% reviews were from the no-Vine program

![Deliverable 2](https://github.com/chocoplace/Amazon_Vine_Analysis/blob/main/Resources/Deliverable%202.png)


Summary: The results reflect a higher porcentage of participants from the no-Vine program that could be beneficial to the providers since their product is getting positive attention for free. 

--End
