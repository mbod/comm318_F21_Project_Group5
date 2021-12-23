## Data files 

* This folder should contain the data files you have used in your analysis


* You should update this README file to list and describe the files.


* You can also create additional sub-folders to better organize your data.
    * For example, you could have a folder called `raw` or `orig` to contain the original data files you downloaded and then a folder called `final` or `clean` that contains versions of these data sheets that you have worked with to clean up missing data, to subset or merge etc.
    
    
### Opi_Prescribing_Rates_federal.csv
* This is the dataset imported from data.gov (source: https://catalog.data.gov/dataset/opioid-prescribing-rates-at-va-facilities-2012-2018).
* The dataset is federal level data containing all the states, including CT. It focuses on the prescribing rate of opioids from the Department of Veterans Affairs medical centers from 2012 and 2018 and also details specific information of the medical centers, such as state and longitude.

### opi_prescribing_rates_df_clean.csv
* This is cleaned version of Opi_Prescribing_Rates_federal.csv. It was cleaned by deleting duplicate medical facilities, changing "Percent Change" columns so the numbers would be less than 1 to accurately reflect the proportions, and adding in a rate difference column to show the difference between 2018 and 2012 rates.

### Connecticut_Prescriptions_per_Year.csv
* This is the dataset imported from data.goc (source: https://catalog.data.gov/dataset/connecticut-prescriptions-per-year) 
* This dataset contains information about the amount of controlled substance prescritpions, opioid prescriptions, and benzodiazepine prescriptions given out per year from 2014-2020 in Connecticut.

### CT_prescript_clean.csv
* This is the cleaned version of the Connecticut_Prescriptions_per_Year.csv dataset. This dataset was already pretty clean so the only thing that was changed was the column names. 

### accidental_drug_deaths_CT.csv
* This is the dataset imported from data.gov (source: https://catalog.data.gov/dataset/accidental-drug-related-deaths-2012-2018) 
* This dataset contains information about accidental drug related deaths in Connecticut from 2012-2020. It details the date of the death, the age, sex, race, residence, location, and cause of death. 

### accidental_drug_deaths_CT_clean.csv
* This is the cleaned version of accidental_drug_deaths_CT.csv. It was cleaned by renaming and removing unwanted columns. 

### opi_admission_by_town.csv
* This file is the CT opioid rehab admissions data in .csv form
* Source: https://catalog.data.gov/dataset/opioid-related-treatment-admissions-by-town-in-department-of-mental-health-and-addiction-s

### opi_admission_by_town.geojson
* This file is the .geojson form of opi_admission_by_town.csv

### ct_towns_map.geojson
* This file contains the GeoData for CT towns in .geojson form
* This was used earlier in the semester for data analysis

### opi_town_clean.csv
* This file contains the data points for all CT towns in .csv form
* This is the cleaned up version of opi_admission_by_town.csv

### Connecticut_and_Vicinity_Town_Boundary_Set.geojson
* This file contains the GeoData for CT and neighboring towns in .geojson form
* Source: https://catalog.data.gov/dataset/connecticut-and-vicinity-town-boundary-set/resource/21b737eb-efc2-4faf-8575-b09d85af6ddf

### Drug_Overdose_Death_Counts_federal.csv
* This file contains the federal drug overdose data collected from 2015-2021
* Source: https://catalog.data.gov/dataset/vsrr-provisional-drug-overdose-death-counts

### drug_overdose_death_clean.csv
* This file contatins the cleaned up data from Drug_Overdose_Death_Counts_federal.csv
* It was cleaned by removing unwanted columns and renaming columns to more practical names

### opioid_arrests.csv
* This file contains PA opioid arrest data from 2013-2021
* Source https://data.pa.gov/Opioid-Related/Opioid-Seizures-and-Arrests-CY-2013-Current-Quarte/wmgc-6qvd