# eMILA_fuel_price_scraper
A simple notebook that scrapes the fuel prices from eMILA gas stations in Poland and visualises them in a scatter plot.

## Prerequisites & packages
### Local Jupyter environment
The following packages are required to be preinstalled to run this notebook: 
- pandas
- requests
- bs4
- plotly
#### Package installation
If you are missing any of the above packages, you can install them from your Python console using the following command:
```
pip install <package name>
```
It also uses the following built-in packages that should be included in your Python distribution:
- datetime
- re
### Google Colab
Should you prefer not to run this notebook locally (or you are on the road & are trying to figure out at which gas station you should rather fill up using your mobile device) you can also [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Lewandowski-commits/eMILA_fuel_price_scraper/blob/main/emila_fuel_price_scraper.ipynb]. There are no prerequisites as the hosted environment will already have all the packages installed.
