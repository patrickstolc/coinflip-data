# Coinflip Data
This repository contains [releases](https://github.com/patrickstolc/coinflip-data/releases) of data and datasets used in experiments and research on [Coinflip.so](https://coinflip.so).

> __⚠️ Important:__ Data and datasets can go through multiple releases cycles. Please be aware of any changes to the data and update accordingly. Releases only come as `.tar.gz` files, installed to your `site-packages` using pip.

## Quickstart
To download and install a specific dataset you need to install the [coinflip package](https://github.com/patrickstolc/coinflip). Next, run the following command, with the name of the symbol and subset that you want to use.
```
python -m coinflip download [symbol] [subset]
```
You can find an overview of available datasets in [releases](https://github.com/patrickstolc/coinflip-data/releases).

To remove a dataset, run the following command,
```
python -m coinflip remove [symbol] [subset]
```
