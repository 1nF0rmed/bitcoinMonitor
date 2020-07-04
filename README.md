# Bitcoin Monitor

A simple GUI tracker for bitcoin prices that collects tick data from the following sources:

- BTC-e
- Bitstamp
- Bitfinex
- Huobi

## Setup
This is build on PYTHON 3.

1. Install the project dependencies:
```bash
$ pip install -r requirements.txt
```
2. Install mpl_finance as its not available on pip anymore
```bash
$ pip install https://github.com/matplotlib/mpl_finance/archive/master.zip
```
3. Assuming you are on a Linux distribution, you should already have Tkinter installed in Python 3

## Run
```bash
$ python main.py
```

## Output

1. Bitfinex ticks

![alt text](https://github.com/1nF0rmed/bitcoinMonitor/raw/master/images/Bitfinex-btc.png "Ticks data for BTC from Bitfinex")

2. Bitstamp ticks

![al text](https://github.com/1nF0rmed/bitcoinMonitor/raw/master/images/Bitstamp-output.png "Ticks data for BTC from Bitstamp")