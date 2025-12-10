<h1>Advanced SQL Techniques</h1>
<img width="410" alt="SQL Project 1" src="https://github.com/jciwilliams/SQL_Techniques/assets/152811710/0cd14067-3a89-44f3-84d1-e1396f436c7d">

### SQL projects demonstrate comprehensive skills like: 
 - <b>Retrieving Data from a Multiple Tables</b>
 - <b>Filtering, Calculating Data, Group By, Having, Left, Inner, and Full Joins</b>
 - <b>Unions and Subqueries</b>
 - <b>Summarizing the Data</b>

<h2>SQL Project 1</h2>
The Revenue Cycle Manager is preparing a Q1 2022 report on specific PR (Patient Responsibility) adjustment codes. She wants to see total payments received each month where the Reason_Code starts with 'PR'.
<br />

###
<p align="center">
Left Join, Filtering Data, Date Functions and Group by: <br/>
<img width="328" height="290" alt="Image" src="https://github.com/user-attachments/assets/f4f2f15d-70fb-4d41-af31-35be3c5c9770" />
<br />
<br />

<h2>SQL Project 2</h2>
For all active Endocrinology providers whose NPIs start with 7 who have not completed a procedure or Dermatology providers whose NPIs start with 1 or 2 who have not completed a procedure but have visits recorded, may you let us know how long each of these providers have been active providers with us? 
<br />

###
<p align="center">
Left Join and Filtering Data : <br/>
<img width="554" height="195" alt="Image" src="https://github.com/user-attachments/assets/c31b1c2f-c6af-4ddb-b1c3-f7f126430851" />
<br />
<br />

<h2>SQL Project 3</h2>
For all EDI claim submissions that were submitted with an E primary diagnosis code that took at least 30 days to be adjudicated, we need the provider who submitted these claims as long as the providers have been active with us for at least 5 years.
<br />

###
<p align="center">
Left Join, Filtering Data, and Date Functions: <br/>
<img width="542" height="134" alt="Image" src="https://github.com/user-attachments/assets/262e890a-6db7-4557-b53d-3cebc506298c" />
<br />
<br />

<h2>SQL Project 4</h2>
Thanks for providing us with this, but which two insurance providers billed the most for these claims where the average billing amount was at least $1,000.
<br />

###
<p align="center">
Left Join, Filtering Data, Date Functions Calculated fields, Group by and Having: <br/>
<img width="546" height="169" alt="Image" src="https://github.com/user-attachments/assets/ce36c799-db23-480b-9cb9-9811209b12ef" />
<br />
<br />

<h2>SQL Project 5</h2>
For all Z primary diagnoses UnitedHealthcare paid claims for urgent care visits or J45 primary diagnoses Aetna paid claims for annual visits, we need to know the patient’s name and place of residence as well as their enrollment date. 
<br />

###
<p align="center">
Left Join, Filtering Data, Date Functions Calculated fields, Group by and Having: <br/>
<img width="546" height="169" alt="Image" src="https://github.com/user-attachments/assets/ce36c799-db23-480b-9cb9-9811209b12ef" />
<br />
<br />

<h2>SQL Project 6</h2>
Identify all customers in our market who registered in person at a physical branch location and extract the fields necessary to evaluate member engagement through face-to-face channels. We need this for individuals who have at least a 700 credit score, didn’t require a co-signer, and have had their account for at least 7 years OR customers who are younger than 65 years old who have had their account for at least 10 years. Your output should include:
Member ID
First and Last Name
Method of Sign-Up (branch enrollment)
Credit score
Email address (if they have one on record)
Consider how analyzing in-person registration volume can provide insight into branch effectiveness, staffing needs, and the balance between digital and traditional onboarding strategies.
<br />

###
<p align="center">
Left Join, Date Functions (Query 1 to Project 7): <br/>
<img width="664" height="295" alt="Image" src="https://github.com/user-attachments/assets/cc0acfa7-d278-487f-a6b1-ed336603e23f" />
<br />
<br />

<h2>SQL Project 7</h2>
Thanks, but may you provide this into a compiled list?
<br />

###
<p align="center">
Union - Full Join, Left Join, and Date Functions (Query 2, 1st Query Project 6): <br/>
<img width="415" height="383" alt="Image" src="https://github.com/user-attachments/assets/a0a82af9-71e0-4168-a920-b057fd2dbbc7" />
<br />
<br />

<h2>SQL Project 8</h2>
Identify all order numbers that were not returned and contained SKUs belonging to the 2-family product group.
This analysis will help determine whether specific product families are associated with higher fulfillment success rates and may support inventory planning or supplier negotiations. We only need to see the order numbers listed.


Identify B2C customer orders that were returned as duplicates during Q1 2023, where the order included product keys beginning with 3 or 7.
Your goal is to isolate patterns related to duplicate shipments and evaluate whether specific product categories are driving operational or fulfillment inefficiencies.

Thanks, but with the lists you provided for the non-returned orders and the returned orders, we need a consolidated list in order for Supply Chain to complete a comparative analysis to identify trends in product performance and operational accuracy.
<br />

###
<p align="center">
Union - 3 Joined Queries (Original Query to Project 9): <br/>
<img width="329" height="314" alt="Image" src="https://github.com/user-attachments/assets/e202b979-2aae-4e7e-9d2d-0b285a206ab3" />
<br />
<br />

<h2>SQL Project 9</h2>
From the following consolidated list that you provided a few days ago, may you provide the number of orders?
The consolidated list that you provided included the following groups:
Identify all order numbers that were not returned and contain SKUs belonging to the 2-family SKU group.
Identify B2C customer orders that were returned as duplicates during Q1 2023, where the order included product keys beginning with 3 or 7.
Identify B2B and Government non - standard customer orders that were not returned and placed by customers who are active and have been customers for at least 5 years.

<br />

###
<p align="center">
Subquery (Orignal Query from Project 8): <br/>
<img width="421" height="356" alt="Image" src="https://github.com/user-attachments/assets/beecba4e-604e-4d1b-ba78-f295dac57f6c" />
<br />
<br />

<h2>SQL Project 10</h2>
The credit union is evaluating opportunities to improve member growth and streamline the onboarding pipeline. To support decision-making, you have been asked to develop a consolidated list of both customers and applicants.
Please include the following:
Unique Identifier (ID)
First and Last Name
Status (Applicant vs Customer)

Identify all applicants who completed online registration and determine the core attributes required to analyze digital engagement. We need this for applicants who have at least a 750 credit score and reside in the Southwest region OR applicants who are not located in NY, CA, and/or HI. Your output should include:
Member ID
First and Last Name
Method of Sign-Up (channel of enrollment)
Credit score
Email address (if they have one on record)
Consider how isolating online sign-ups could help the credit union assess digital adoption trends and improve member acquisition strategies.

Identify all customers in our market who registered in person at a physical branch location and extract the fields necessary to evaluate member engagement through face-to-face channels. We need this for individuals who have at least a 700 credit score, didn’t require a co-signer, and have had their account for at least 7 years OR customers who are younger than 65 years old who have had their account for at least 10 years. Your output should include:
Member ID
First and Last Name
Method of Sign-Up (branch enrollment)
Credit score
Email address (if they have one on record)
Consider how analyzing in-person registration volume can provide insight into branch effectiveness, staffing needs, and the balance between digital and traditional onboarding strategies.
<br />

###
<p align="center">
Union: Date Functions Calculated fields, Group by and Having (Original Query to Project 11): <br/>
<img width="299" height="302" alt="Image" src="https://github.com/user-attachments/assets/eed3ad57-f64e-4efd-be16-4753a4f3b870" />
<br />
<br />

<h2>SQL Project 11</h2>
From the following consolidated list that you provided a few days ago, may you provide the following:
Number of individuals in the list
Average credit score
Highest credit score
Lowest credit score
The consolidated list that you provided included the following groups:
Identify all applicants who completed online registration and determine the core attributes required to analyze digital engagement. We need this for applicants who have at least a 750 credit score and reside in the Southwest region OR applicants who are not located in NY, CA, and/or HI. 
Identify all customers in our market who registered in person at a physical branch location and extract the fields necessary to evaluate member engagement through face-to-face channels. We need this for individuals who have at least a 700 credit score, didn’t require a co-signer, and have had their account for at least 7 years OR customers who are younger than 65 years old who have had their account for at least 10 years.
<br />

###
<p align="center">
Subquery: <br/>
<img width="299" height="302" alt="Image" src="https://github.com/user-attachments/assets/eed3ad57-f64e-4efd-be16-4753a4f3b870" />
<br />
<br />















</p>
