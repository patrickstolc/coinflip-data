# Coinflip Data
This repository contains [releases](https://github.com/patrickstolc/coinflip-data/releases) of data and datasets used in experiments and research on [Coinflip.so](https://coinflip.so).

> __⚠️ Important:__ Data and datasets can go through multiple releases cycles. Please be aware of any changes to the data and update accordingly. Releases only come as `.tar.gz` files, installed to your `site-packages` using pip.

## Quickstart
The [coinflip package](https://github.com/patrickstolc/coinflip) is required to download datasets. 

To download a dataset, use the following code, with the name of the symbol and subset that you want to use.
```python
from coinflip.universe import load
df = load('aapl', 'reddit')  # returns a Pandas dataframe
```

To remove a dataset from within your code:
```python
from coinflip.universe import remove
remove('aapl', 'reddit')
```
