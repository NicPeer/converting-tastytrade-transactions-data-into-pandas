# Importing TastyTrade Transactions CSV into Python
Adding my options trading quant coding efforts here for the public to see #buildinpublic #tradeinpublic
Importing Transactions CSV into Python

See in this repository the Jupyter Playbook I created: https://github.com/NicPeer/converting-tastytrade-transactions-data-into-pandas/blob/main/BlueskyNomad_TastyTrade_Transactions_11Mar22_04Apr23.ipynb

And here is the csv I make use of TT_transactions_1st_year_2022.csv

I am trading options for a year now and have taken the decision to start learning Python to better understand and analyse what I am doing and what I can do better. 

In this playbook I want to mirror my transaction journal I maintain in Excel and on in the weekly trading journal entries on my website (www.blueskynomad.com). The goal is to save time, improve data quality and being able to do more analysis.

I am using the transactions CSV downloaded from Tastytrade for the first year of my options trading. At a later stage I want to add/merge/parse also the 'Year-to-Date'and my Positions data which I download daily. The idea is that I only have to upload the lastest transactions overview and load it into this notebook. I will do the same for my Interactive Brokers' transactions. As a next project, I want to use TastyTrade's and IB's APIs to automate this.

I also set up a playbook for learning pandas and testing set-ups. A few of the challenges I encountered and still have are related to cleaning up and preparing the data for use: converting objects to numbers and datetime formats, dealing with thousand separators and empty cells, indexing, etc.

This playbook at this stage is only limited to grouping and charting cashflows. The next step is to add P/L.

I already found out that using www.poe.com to assist me in setting this all up and finding answers to questions I have, really helps. I tried to find examples of this challenge in Stack Overflow and other sites but didn't yet find anything, so I intend to publish my questions also there and in the the PyquantNews'(PQN) community (www.pyquantnews.com). (Note: I just found a link in the PQN community added by Yong Shen Tan that may help and that I will check out: https://github.com/tys203831/portfolio_analysis).

Being a noob in Python and algorhythmic trading, I followed Jason Strimpel's excellent Getting Started With Python for Quant Finance (https://gettingstartedwithpythonforquantfinance.com/) course which taught me most of what I applied below. In addition I watched Corey Schaefer's YouTube pandas tutorials in parallel. I installed the 'quant stack' modules used also in the course.

pandas

NumPy

SciPy

Matplotlib

Statsmodels

Pyfolio

IB API

QuantStats

Zipline

OpenBB SDK

RiskFolio-Lib

I added the csv sheet. You need to change the URL to the file in the playbook.
