# COVID19_dashboard
A simple interactive covid-19 dashboard written in a Python Jupyter Notebook. Based on UK Government data published by Public Health England. 

API calls forwarding and response packing is handled using PHE Python SDK kit (https://pypi.org/project/uk-covid19).

The SDK returns JSON files, which are then wrangled into DataFrames with pandas.

Plots are produced with matplotlib and seaborn, and then displayed in a Binder via voila (https://voila.readthedocs.io/en/stable/install.html).


### HOW TO RUN:

The dashboard is deployed as a Binder, click the link below (may take a few minutes on the first run):



[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KAntoniuk/COVID19_dashboard_/main?urlpath=voila%2Frender%2FDashboard.ipynb)
