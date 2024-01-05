# Covid-19 Analysis

## Project Overview
This project is designed to offer a comprehensive understanding of the progression and implications of the COVID-19 pandemic. Through a meticulous analysis of various data facets, we aim to discern patterns in confirmed cases, fatalities, recoveries, and testing. Our objective extends to the comparison of COVID-19 statistics among diverse regions, as well as the scrutiny of the effects of interventions such as lockdowns or vaccination campaigns. The ultimate goal is to formulate data-driven recommendations and cultivate a more profound insight into the dynamics of the pandemic.

## Data Sources
The primary dataset utilized in this analysis is the "Covid_19_India_Dataset.csv" sourced from Intern Career. This dataset provides comprehensive information on daily reported COVID-19 cases, encompassing details such as the number of confirmed cases, deaths, recoveries, and testing data.

## Tools
- Excel (Data Cleaning)
- PowerBI (Data Analysis and Report Creation)

## Data Preparation and Cleaning
During the initial preparation phase, the following tasks were executed:
- Loading and inspecting the data.
- Addressing missing values to ensure data consistency.
- Conducting data cleaning and formatting procedures.

## Exploratory Data Analysis (EDA)
EDA involved exploring the dataset to answer key questions such as:
1. What are the trends in confirmed cases, deaths, recoveries, and testing?
2. What is the severity of cases in different regions?
3. What is the impact of measures like lockdowns or vaccination?
4. What are top 3 states with the highest death number and recovery number?

## Data Analysis
Creating calculated columns and measures using PowerBI. Example ;

```Active cases = SUM(covid_19_india[Confirmed]) - SUM(covid_19_india[Deaths]) - SUM(covid_19_india[Cured])```

## Results
The summarized outcomes of the data analysis are outlined below: 
- The analysis revealed over 5 billion confirmed cases of Covid-19, indicating an upward trend in the Sum of Deaths from January 2020 to July 2021.
- Maharashtra reported the highest Sum of Confirmed cases (1,121,491,467), contributing to 20.57% of the total confirmed cases across all 46 regions.
- The top three states for death and recovery cases were Maharashtra, Karnataka, and Kerala, with Maharashtra leading in the Sum of Cured cases (1,018,765,039), representing 54.17% of the total Cured cases.
- The aggregate of positive cases demonstrated a notable 97.46% decrease from January 2021, likely attributed to measures such as lockdowns, vaccinations, and preventive actions.
- A greater number of vaccine doses were administered during the initial stage as opposed to the second stage.
- In vaccine distribution, CovidShield doses were the most administered, followed by Covaxin, with Sputnik being the least distributed.
- India led in the Sum of 18-44 Years (Doses Administered), accounting for 50.00%, significantly higher than the lowest at Lakshadweep (1,342,750).
- The age group 18-44 years had the highest sum of vaccine doses administered, followed by 45-60 years, while the 60+ age group had the lowest sum.
- In terms of the number of individuals vaccinated, the 45-60 age group led, followed by 60+, with the 18-45 age group having the lowest sum.

## Recommendations 
1.	Targeted Measures in High-Incidence Regions: Given that Maharashtra has the highest number of confirmed cases, it would be advisable to implement targeted measures in this region. This could include increased testing, vaccination drives, and public awareness campaigns to curb the spread.
2.	Enhanced Healthcare Infrastructure: The states with the highest numbers of cases and deaths, such as Maharashtra, Karnataka, and Kerala, may benefit from additional resources for healthcare infrastructure. This could involve increasing hospital capacity, ensuring an adequate supply of medical supplies, and training healthcare professionals.
3.	Vaccination Strategy Refinement: While India has made significant strides in vaccine distribution, efforts can be made to improve distribution equity among different states and age groups. Strategies to encourage vaccination in regions with lower coverage should be explored, and public awareness campaigns can address vaccine hesitancy.
4.	Monitoring and Adapting to Trends: Continuously monitor and analyze the trends in COVID-19 cases, deaths, and vaccinations. Being adaptable and adjusting strategies based on emerging patterns can help in more effective and targeted responses.
5.	Continued Public Health Measures: Sustaining and possibly strengthening measures such as vaccinations, and promotion of preventive actions like handwashing and mask usage can help to maintain the downward trend in positive cases.
6.	Public Awareness: Ongoing public education campaigns can reinforce the importance of adhering to preventive measures. Clear communication about the effectiveness of actions such as wearing masks and handwashing can encourage continued compliance.
7.	Age-Specific Vaccination Campaigns: Given the variation in vaccine coverage among age groups, consider tailored vaccination campaigns. Special attention may be needed for the 18-45 age group, ensuring they have equitable access to vaccines.
8.	Encouraging Second Dose Adherence: Since more doses were administered in the first stage compared to the second, efforts should be made to encourage individuals to complete the full vaccination schedule. This involves public communication, reminders, and ensuring an ample supply of vaccines for second doses.
9.	Diversification of Vaccine Distribution: While CovidShield dominates in distribution, efforts can be made to diversify vaccine options and address any challenges hindering the distribution of vaccines like Sputnik. A diverse vaccine portfolio enhances flexibility in responding to different population needs.
10.	International Collaboration: Collaborate with international organizations and other countries to share experiences, resources, and best practices. This can include mutual assistance in vaccine distribution, technology transfer, and research collaboration.

## Limitation
During data cleaning in Excel, null values were substituted with zero instead of utilizing Power Query in Power BI to remove empty spaces and null values. This decision was made to avoid the deletion of a substantial portion of the data, ensuring the accuracy of the analysis conclusions.
