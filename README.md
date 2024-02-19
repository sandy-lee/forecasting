# Forecasting

💬 About:

    This is a task I completed in an attempt to forecast demand for [double glazing] using Google Trends data as a proxy for customer interest/demand in the UK. I used the Neural Prohpet library (https://neuralprophet.com/) to do the forecast in Python. Neural Prophet is a deep learning approach to traditional time series forecasting, the advantage of this approach being that the model can be refitted as more data becomes available.  

💾 Files in this repo are:

    **neural_prophet_forecasting.ipynb** - this file contains the code to import the data CSV, fit a Neural Prophet model and export a forecast.
    **multiTimeline.csv** - this file contains 5 years worth of Google Trends data for the keyword [double glazing] for the UK market.

⚡ TO DO:

    The next step is to test the predictions against real data to see if the model holds up well against reality.
