# EDA-and-hypothesis-testing-on-well-established-hospital-in-india



The data is about the well established hospital in india. It is the nation's top corporate hospital and is acclaimed for pioneering the private healthcare revolution in the country.

As a data scientist working at this hospital, the ultimate goal is to tease out meaningful and actionable insights from Patient-level collected data.

You can help hospital to be more efficient, to influence diagnostic and treatment processes, to map the spread of a pandemic.

One of the best examples of data scientists making a meaningful difference at a global level is in the response to the COVID-19 pandemic, where they have improved information collection, provided ongoing and accurate estimates of infection spread and health system demand, and assessed the effectiveness of government policies.


Column Profiling:
Age: This is an integer indicating the age of the primary beneficiary (excluding those above 64 years, since they are generally covered by the government).

Sex: This is the policy holder's gender, either male or female.

Viral Load: Viral load refers to the amount of virus in an infected person's blood.

Severity Level: This is an integer indicating how severe the patient is.

Smoker: This is yes or no depending on whether the insured regularly smokes tobacco.

Region: This is the beneficiary's place of residence in Delhi, divided into four geographic regions - northeast, southeast, southwest, or northwest.

Hospitalization charges: Individual medical costs billed to health insurance


Problem Statement:
The company wants to know:

• Which variables are significant in predicting the reason for hospitalization for different regions

• How well some variables like viral load, smoking, Severity Level describe the hospitalization charges



Insights:

*   Their are more male than female in the data.
*   Their are more non-smokers than smokers in the data.
*   Their are more people from southeast region than remaining regions.
*   Males have slightly greater median of viral load than females.
*   smokers have high hospitalization charges than non smokers.
*   All the regions have almost same median of hospitalization charges.
*   In southeast region, median of viral load is more than remaining regions.
*   In southeast region, there are more smokers than remaining regions after comes northeast.
*   smokers in southeast region have high hospitalization charges than remaining regions.
*   Male smokers have high hospitalization charges than female smokers.
*   In northeast & southeast region, as the viral load increases hospitalization charges also increases.
*   For southwest & northwest, most of the points lie between 0-4000.



Recomendations:

*   Hospitalization charges for people who smoke is greater than people who don't smoke. So, people who are smoking have high chances of hospitalization. We can see what type of health problems are commom in smoking people and keep those medicines more in pharmacy.

*   Since, people who are smoking have high chances of hospitalization. Southeast region have more smokers than remaining regions. So we can open more number of hospital and pharmacy branches in that region.

