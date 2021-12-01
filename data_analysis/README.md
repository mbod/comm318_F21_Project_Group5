## Data analysis notebooks


### opi_prescribing_rates_fed_sharon
* This notebook analyzes and cleans the dataset Opi_Prescribing_Rates_federal.csv from data.gov (source: https://catalog.data.gov/dataset/opioid-prescribing-rates-at-va-facilities-2012-2018).
* The exploration component aims to discover the frequency of the non-VA prescribing rate (whether Average, High, or Low) and how often each state appears in the dataset. There are also 3 simple regressions to determine if there is a correlation between the 2018 prescribing rates and variables like the 2012 prescribing rate, latitude, and longitude.

### opi_prescribing_rates_fed_analysis_sharon
* This notebook analyzes which states have the highest and lowest opioid prescribing rate at Department of Veterans Affairs medical centers in 2016 and 2018 and if longitude is a factor that affects prescribing rates. This is more of a general high-level analysis for our data story.
* The dataset that I am using is opi_prescribing_rates_df_clean.csv from JupyterHub notebook opi_prescribing_rates_fed_sharon. The original dataset is from data.gov (source: https://catalog.data.gov/dataset/opioid-prescribing-rates-at-va-facilities-2012-2018).