## DOGE Data Scraper ## 
This repository includes a script to download data from DOGE's "Wall of Receipts" via its API, as well as data from several of my downloads. 

  * Base URL: https://api.doge.gov/savings/

## 🌟 Use ##
The code in "api_script" was intended for use in a Jupyter Notebook. The current script can be manipulated to pull contracts, grants and leases data from the DOGE website at once or seprately. 

Those queries are available via the following endpoints:
  * save_doge_data('grants', 'grants', 'GRANTS FILE PATH AND NAME HERE.xlsx')
  * save_doge_data('leases', 'leases', 'LEASES FILE PATH AND NAME HERE.xlsx') 
  * save_doge_data('contracts', 'contracts', 'CONTRACTS FILE PATH AND NAME HERE.xlsx') 

## 🔍 About ##
This code was written and simplified with assistance by ChatGPT and Claude (and a decent amount of human intervention).

## 📊 Data ##
Data collected using this script (as well as an earlier versions of the code) is also available in this repository.

## 👤 Author ##
Made by Madison Alder
Contact: madisonalder@outlook.com
