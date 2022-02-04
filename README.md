# Crypto Arbitrage

This project entails building a tool to help credit union members evaluate their financial health. There is to analysis in one Jupyter notebook:

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

---

## Technologies

* [pandas](https://github.com/pandas-dev/pandas) - is a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive 

* [%matplotlib inline](https://pythonguides.com/what-is-matplotlib-inline/) - can be used to enable the inline plotting, where the plots/graphs will be displayed just below the cell where your plotting commands are written

* [Alpaca trade API python](https://github.com/alpacahq/alpaca-trade-api-python) - is a python library that allows rapid trading 

* [JupyterLab](https://github.com/jupyterlab/jupyterlab) - an extensible environment for interactive and reproducible computing, based on the Jupyter Notebook and Architecture

---

## Instalation Guide

Before opening the Jupyter notebook, you need to install:

With conda:

```python
conda install -c conda-forge notebook matplotlib
```

With pip:

```python
pip install notebook matplotlib
```
```python
pip install alpaca-trade-api
```
```python
pip install python-dotenv
```

---

## Contributors

Author: Magdalena Svimberska
email: magdalena.svimberska@gmail.com

---

## License

GNU General Public License