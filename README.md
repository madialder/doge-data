## DOGE Data Scraper ## 
This repository includes a script to download data from DOGE's "Wall of Receipts" via its API, as well as data from several of my downloads. 

  * Base URL: https://api.doge.gov/

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

⚠️ An important note: The dataset is not complete. I began collecting May 22, 2025, but I believe I missed five data uploads between the July 10, 2025 download and the Oct. 21, 2025 download.

The following is a list of the data upload dates by DOGE and whether they're represented.
| DOGE Upload Date  | Collected? | Date Collected |
| ------------- | ------------- |  ------------- |
| May 11, 2025  | ✅ | May 21, 2025
| May 26, 2025  | ✅ | May 27, 2025
| June 3, 2025  | ✅ | June 6, 2025
| June 29, 2025 | ✅ | July 10, 2025
| July 26, 2025 | ❌ |
| Aug. 12, 2025 | ❌ | 
| Aug. 14, 2025 | ❌ | 
| Aug. 15, 2025 | ❌ | 
| Sept. 8, 2025 | ❌ | 
| Oct. 4, 2025 | ✅ | Oct. 21, 2025



## 👤 Author ##
Made by Madison Alder 

I'm a reporter with FedScoop teaching myself data analytics.

Contact: madisonalder (at) outlook.com
