# Power_BI Visualization 


## Data Source and Introduction

This Power BI visualization project utilized data from https://data.gov.my/ which is an open source database that houses data catalogues by the government of Malaysia and specifically the - data catalogue Transactional Records: Deaths due to COVID-19 which records death from Covid-19 related complications with various demographic and medical dimensions including COVID-19 vaccination records from 17 March 2020 to the present year 31 May 2024. The link to the dataset can be viewed through the following URL: https://data.gov.my/data-catalogue/covid_deaths_linelist. 

## How is this data produced?

This dataset is produced by the c, based on daily ground-level surveillance conducted to monitor the evolution of COVID-19 in Malaysia. Following Malaysia's transition to endemicity, the public reporting frequency was altered from daily to weekly. Nevertheless, internal surveillance is still conducted on a daily basis.

## Dashboard Objective

This dashboard visualization may help government, health organizations and insurance companies in Malaysia understand the needs and requirements for planning for any future occurrence of infectious disease like COVID-19 if it occurs again. Preparation of accurate data visualization can help decision makers in government offices and health organization leaders to allocate sufficient resources for control strategies like lockdown and vaccination campaigns. The dashboard also can assist in providing insights into the effectiveness of certain administered vaccines or the severity of future outbreaks or different strains of the same disease at a future time period. 
Having accurate representation of current and past data for a particular disease may help in identifying vulnerable segments of a population especially for those who are most likely to be effected by the disease (e.g., the elderly, people with preexisting conditions, or certain socioeconomic groups) and pre-emptive protection measures can be implemented curb mass outbreak or escalation of the disease to a more serious/threatening level. Health organizations and pharmaceutical companies also may use this data visuals to plan vaccine and medication rollout period and amount the assessment of real-world effectiveness and safety for the Malaysian general public and environment. 

## Dashboard visualization production steps:

Step 1 : Load data into Power BI Desktop using dataset is a csv file option

Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

Step 3 : It was observed that in none of the columns errors & empty values were present.

Step 4 : Remove underscore and capitalize the first letter of words of each column as part of the data preparation process and remove "comorb" column as it values are not evaluated in this dashboard.

Step 5 : The DAX function EVALUATE TOPN(100, 'Covid deaths list')  is created to calculated the number of total cars for a certain period.

Step 6 : In the report view, under the view tab, dashboard theme was selected.

Step 7 : Chart and design were selected and configured for visualization.

Step 8 : Line and area chart, clustered bar, donut type chart were selected to represent total by COVID-19 deaths by age group, by location states, gender and what vaccination was administered by the deceased person based on the information provided by Crisis Preparedness and Response Centre (CPRC) at the Ministry of Health.

Step 9 : Visual filters (Slicers) were added for categories "State" for 1 slicer and "Age", "Vaccine Brand", and "Gender" for other slicers.
Step 10 : Filter selection based on time period (1 January 2024 to 31 July 2024) for data gathering purposes. 

## Dashboard visualization summary for selected time period (1 January 2024 to 31 July 2024)

From the visualization selection - it can be summarizes that most car registrations in Malaysia from 1 January 2024 to 31 May 2024, consists of the following car categories: 

Total of 33,309 Malaysians and 4,042 non-Malaysians that have been test positive from COVID-19 complications of which 21.5K were male gender and 15.8k were female gender.

The highest average age of death from COVID-19 is 50 -74 years and the death of arrival at the hospital due to COVID-19 complication also show the same average from the same age group (50 -74 years).

Total Individuals who died with the Pfizer, Sinovac and Astra Zeneca vaccination  from January 2024 to 31 May 2024 which total around (Sinovac: 7,705 deaths) and (Pfizer: 5,425 death) and (Sinovac: 1,071 deaths).

Top 3 states in Malaysia to have the most deaths due to COVID-19 complications are Selangor (11.1K deaths), Johor(4.8k deaths) and Sabah(3.2K deaths).

Top 3 states in Malaysia to have highest percentages due to COVID-19 complications are Selangor (58.08%), Johor(25.04%) and Sabah(16.88%).

The highest decrease of COVID-19 related death since 2020 to May 2024 comparison of all states in Malaysia is Selangor (18.8%), Johor (15.86%), Perak (13.59%), Kedah (10.88%) and Sabah (7.4%).





