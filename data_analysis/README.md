## Data analysis notebooks


### opi_prescribing_rates_fed_sharon
* This notebook analyzes and cleans the dataset Opi_Prescribing_Rates_federal.csv from data.gov (source: https://catalog.data.gov/dataset/opioid-prescribing-rates-at-va-facilities-2012-2018).
* The exploration component aims to discover the frequency of the non-VA prescribing rate (whether Average, High, or Low) and how often each state appears in the dataset. There are also 3 simple regressions to determine if there is a correlation between the 2018 prescribing rates and variables like the 2012 prescribing rate, latitude, and longitude.

### opi_prescribing_rates_fed_analysis_sharon
* This notebook analyzes which states have the highest and lowest opioid prescribing rate at Department of Veterans Affairs medical centers in 2016 and 2018 and if longitude is a factor that affects prescribing rates. This is more of a general high-level analysis for our data story.
* The dataset that I am using is opi_prescribing_rates_df_clean.csv from JupyterHub notebook opi_prescribing_rates_fed_sharon. The original dataset is from data.gov (source: https://catalog.data.gov/dataset/opioid-prescribing-rates-at-va-facilities-2012-2018).

### CT_Prescriptions_per_year_step1_nat
* This notebook analyzes and cleans the dataset Connecticut_Prescriptions_per_Year.csv from data.gov (source:https://catalog.data.gov/dataset/connecticut-prescriptions-per-year). 
* First, the data was examined in order to understand how many columns and rows there were and what each column meant and what each row represents. Then, the data was cleaned. This was already a pretty clean dataset so the columns were just renamed to not contain spaces. Next, the data was explored and visualized in order to determine if the prescribing rate of opioids was increasing from 2014-2020. 

### CT_prescriptions_per_year_step2_nat
* This notebook analyzes the data from CT_prescript_clean.csv. 
* This notebook both visualizes the amount of opioid prescriptions in CT from 2014-2020 as well as calculates the percent changr from 2014 to 2020. 

### accidental_drug_deaths_nat
* This notebook analyzes and cleans the dataset accidental_drug_deaths_CT from data.goc (source: https://catalog.data.gov/dataset/accidental-drug-related-deaths-2012-2018). 
* First, the data was examined in order to understand how many columns and rows there were and what each column meant and what each row represents. Then, the data was cleaned by renaming and removing unwanted columns. Next, the data was explored by looking at the range of dates that were included, creating an opioid filter to determine the amount of drug related deaths that were due to opioids, and looking at the distribution of opioid deaths by city. 

### accidental_drug_deaths_step2_nat
* This notebook analyzes the data from accidental_drug_deaths_CT_clean.csv. 
* This notebook compares the amount of total drugs deaths and opioid-related drug deaths to determine what percent of drug deaths in CT from 2012-2020 were due to opioids. Then, the data is visuzliazed to see the amount of opioid deaths per year. Next, we look at the percent change from year to year to see if the percent change is increasing or decreasing. 

### opi_town_admissions_Ben
* This notebook analyzes and cleans opi_admission_by_town.csv (source: https://catalog.data.gov/dataset/opioid-related-treatment-admissions-by-town-in-department-of-mental-health-and-addiction-s)
* This notebook that that .csv into a .geojson to use later

### opi_town_admis_analysis_Ben
* This notebook builds on opi_town_admissions_Ben and conducts further analysis of the data
* This notebook also combines the admissions data with the .geojson so that the adamissions data can be put on a map
* This notebook measures and visualizes the changing rates of rehab admissions by year and by CT town

### drug_overdose_death_Jonah
* This notebook analyzes and cleans up Drug_Overdose_Death_Counts_federal.csv (source: https://catalog.data.gov/dataset/vsrr-provisional-drug-overdose-death-counts)
* The data was analyzed and useless columns were dropped. The data was found to have useful year and state data for opioid and non-opioid related drug deaths, something that was analyzed later

### drug_overdose_death_analysis_Jonah
* This notebook uses the data from drug_overdose_death_Jonah and looks deeper into the data than before
* The notebook shows the changes between opioid and non-opioid drug overdose deaths over the span of 2015-2020
* This notebook also looks at a map of the drug overdose deaths in the US by mapping to a geopandas map of the US

### opioid_arrests_analysis_Jonah
* This notebook briefly looks at opioid related arrests in the state of Pennsylvania (source: https://data.pa.gov/Opioid-Related/Opioid-Seizures-and-Arrests-CY-2013-Current-Quarte/wmgc-6qvd)
* The analysis shows that the amount of opioid related arrests has increased dramatically, with over 100% increase from 2013-2020