# FinTech-CryptoArbitrage  

![CrytpoArbitrage_Pic](./Images/M3-CryptoArbitrage_2022-10-11170237.png)

*'Searching for Bitcoin arbitrage opportunities across global markets*'

---     

## Background
In this project as a FinTech analyst at a high-tech investment firm, the Vice-President is considering arbitrage opportunities in Bitcoin and other cryptocurrencies. After consultation with the VP, we determine that as Bitcoin trades on markets across the globe we can capitalize on simultaneous price dislocations in those markets by using the powers of Pandas. 

To get started we decided to sort through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. My task is to apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin. A Jupyter notebook is utilized to contain the code for your data collection, preparation, and analysis, including visualizations.

To meet requirements designed for this project: in the same notebook file, comments and text to document the analysis are for making a clear and concise report for presentation to the VP. To accomplish this tasks, the following phases of financial analysis are performed:

1) Collect CSV data in a Jupyter notebook file.
2) Prepare datasets for analysis by cleaning missing and erroneous data.
3) Analyze the data through summary statistics and visualizations, and use this information to select areas for deeper analysis. Specifically, searching for time periods in to identify arbitrage opportunities. 


--- 

# Technologies 

The software operates on python 3.9 with the installation package imports embedded with Anaconda3 installation. It includes 'PyViz' as a single platform for accessing multiple visualization libraries from the Python visualization package. Two PyViz libraries, hvPlot and GeoViews are utilized for this program.

* [anaconda3](https://docs.anaconda.com/anaconda/install/windows/e) .

* [matplot](https://hvplot.holoviz.org/index.html#) .

---

## Installation Guide

Before running the applications first activate the Conda development environment and launch JupyterLab to import the following required libraries apps. If hvplot and geo views is not installed with anaconda, the recommended way to install hvPlot is using the conda terminal command below provided by Anaconda. 

```python libraries
import pandas as pd
from pathlib import Path 
%matplotlib inline 


[conda install -c conda-forge matplotlib-inline] or [pip install matplotlib-inline] 
```

---
# Usage

This application is launched from web-based JupyterLab utilizing Pandas which is designed for data analysis to write and read code in an IDE and review results through the Python libraries. The Anaconda3 software application includes the Pandas libraries; **'PyViz' as a single platform for accessing two PyViz libraries, hvPlot and GeoViews.** They are utilized for high-level plot charts in this program from the Python visualization package. **HoverTool**is imported from the Bokeh library for **hvplot and GeoViews**. It utilize data frames and plot charts in an integrated Conda development environment. 

The program is developed in Jupyter notebooks on a **.ipny** file. Imports of PyViz libraries **hvplots and geoviews**; and with  **HoverTool** are used for more advanced interactive chart environments. These apps makes it much easier to explore data in interactive plot properties, without having to write additional code to select ranges, columns, or data values manually. These interactive visualization libraries also improve browser plot presentations. Together they advance functions to create informative visualizations from the Pandas DataFrames and data metrics. 

The **san_francisco_housing.ipynb** program utilizing the above libraries has several steps to retrieve, aggregate, create, evaluate, and analyze data to make forcasts for real estate investing. Through these steps real estate portfolio managers can visualize property opportunities to efficiently aid purchase decisions in meeting investment goals.   

```python
crypto_arbitrage.ipynb
```
 

---

## Contributors

*Provided to you by digi-Borg FinTek*, 
Dana Hayes: nydane1@gmail.com

---

## License

Columbia U. Engineering