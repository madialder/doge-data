## DOGE Data Scraper ## 
This repository includes a script to download data from DOGE's "Wall of Receipts" via its API, as well as data from several of my downloads. 

  * Base URL: https://api.doge.gov/savings/

## 🌟 Use ##
The code in "api_script" was intended for use in a Jupyter Notebook. The current script can be manipulated to pull contracts, grants and leases data from the DOGE website at once or separately. 

Those queries are available via the following endpoints:
  * save_doge_data('grants', 'grants', 'GRANTS FILE PATH AND NAME HERE.xlsx')
  * save_doge_data('leases', 'leases', 'LEASES FILE PATH AND NAME HERE.xlsx') 
  * save_doge_data('contracts', 'contracts', 'CONTRACTS FILE PATH AND NAME HERE.xlsx') 

## 🔍 About ##
This code was written and simplified with assistance by ChatGPT and Claude (and a decent amount of human intervention).

## 📊 Data ##
Data collected using this script (as well as earlier versions of the code) is also available in this repository. The file naming convention is a six digit YEAR, MONTH, DAY, followed by a single name description of the data downloaded (either 'grants,' 'leases,' or 'contracts').

//An important note: The dataset is not complete. I began collecting May 22, 2025, but I believe I missed two data uploads between the collection July 10, 2025 and the collection Oct. 21, 2025.//

## 👤 Author ##
Made by Madison Alder 

I'm a reporter with FedScoop teaching myself data analytics.

Contact: madisonalder (at) outlook.com
