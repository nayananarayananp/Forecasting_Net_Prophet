### Forecasting Net Prophet
## JupyterLab files
forecasting_net_prophet.ipynb
This application contains all time series data preparation, analysis, and visualization needed by the company to make money. The notebook specifically offers information with seasonality representations in visual form. Along with an hourly forecasting model for user search volume for Prophet, it also offers a study to demonstrate and establish the relationship between a company's Google Search traffic and stock price.

## Technologies
The following package from Python 3.7 is used in this project:

Jupyterlab Notebook

Pandas 

pystan

Google Colab

Facebook Prophet 

hvPlot 

## Installation Guide
Before running the application first install the following dependencies.

!pip install pystan
!pip install prophet
!pip install hvplot
!pip install holoviews

and then import the required Python Libraries.

import pandas as pd
import holoviews as hv
from prophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline

## Usage
Simply clone the repository and execute the forecasting_net_prophet.ipynb to run this program:

  forecasting_net_prophet.ipynb
  
## Contributors
Contributed by Nayana Narayanan.

## License
MIT License
