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