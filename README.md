# api_homework
# Initial imports
import os
import requests
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline

# the following code demonstrates how to parse json format to call relevant data from an api for analysis. In this case we are running a financial analysis on a predetermined value of crypto and stocks/bonds. 
variables representing relevant data are put into dataframes. the data is visualized using .plot and 
using the MCForcastTools to run the montecarlo simulation to see possible outcomes of the initial predetermined investment after 30 years. 
