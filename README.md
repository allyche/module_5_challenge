# Financial Planning with APIs and Simulations

This is a python / jupyter notebook based project demonstrating two financial analysis tools.

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

---

## Technologies

This project leverages python 3.7 with the following packages:

1. [pandas] (https://pandas.pydata.org/) a software library written for the Python programming language for data manipulation and analysis. 
2. [requests] The pathlib is a standard module. Path is the core object to work with files.
3. [json] JavaScript Object Notation (JSON) is a standardized format commonly used to transfer data as text that can be sent over a network. Python has a built-in package called json , which can be used to work with JSON data.
4. [alpaca_trade_api] a python library for the Alpaca trade API. It allows rapid trading algo development easily, with support for the both REST and streaming interfaces. For details of each API behavior, please see the online API document.
5. [MCForecastTools]This is one of the forecasting tools in Python. In this project, Monte Carlo simulation is the tool used (i.e. MCForecastTools.py)
6. [datetime]Encapsulation of date/time values.
7. [%matplotlib inline] The chart plotting command. The output of plotting commands is displayed inline within frontends like the Jupyter notebook, directly below the code cell that produced it. The resulting plots will then also be stored in the notebook document.

---

## Installation Guide

Before running the application first install the following dependencies:

import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
import datetime
%matplotlib inline

---

## Contributors

Brought to you by Ally Che (ally.che@gmail.com)

---

## License
Project Jupyter