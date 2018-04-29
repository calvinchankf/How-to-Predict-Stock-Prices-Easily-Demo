# How-to-Predict-Stock-Prices-Easily-Demo
How to Predict Stock Prices Easily - Intro to Deep Learning #7 by Siraj Raval on Youtube

---

## About this fork
I found the original repo was kinda tough to get started, therefore I have included some necessary setups for kickstarting

#### Whats New
- migrated the code version from python2 to python3
- added requirements.txt for easier setup
- added `main.py` cos i want to run it in terminal as well :)

#### How to Run
```
python3 -m venv .env
source .env/bin/activate
pip install -r requirements.txt
jupyter notebook
```
To avoid installing dependencies globally on my machine, installing them in a virtual environment would be a good choice (or use docker), so the above commands simply:

- create virtual environment and put it in `.env/` folder
- activate the virtual environment
- install dependencies in virtual environment
- run it with jupyter

To exit the virtual environment, just simply use the command:
```
deactivate
```

---

## Overview

This is the code for [this](https://youtu.be/ftMq5ps503w) video on Youtube by Siraj Raval part of the Udacity Deep Learning nanodegree. We use an [LSTM neural network](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) to predict the closing price of the S&P 500 using a dataset of past prices.

## Dependencies

* keras
* tensorflow
* numpy
* matplotlib

see `requirements.txt`

## Usage

Run this using [jupyter notebook](http://jupyter.readthedocs.io/en/latest/install.html). Just type `jupyter notebook` in the main directory and the code will pop up in a browser window.

## Coding Challenge - Due Date, Thursday, March 2nd 2017 at 12 PM PST

Use the price history AND two other metrics of your choice to predict the price of GOOGL stock with an LSTM network. You can find the CSV [here](https://www.google.com/finance/historical?q=NASDAQ%3AGOOGL&ei=Xu6wWKnDAcS1jAGX6a-ACg). Metrics could be sentiment analysis from Twitter of what people have said about Google, dividends, etc.

## Credits

Credits go to [jaungiers](https://github.com/jaungiers/LSTM-Neural-Network-for-Time-Series-Prediction). I've merely created a wrapper to get people started.
