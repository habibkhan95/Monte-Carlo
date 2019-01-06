# Monte-Carlo
Monte-Carlo Simulation (Jupyter Notebook)

## So what is this simulation?
In short - the Monte Carlo simulation uses random variables to simulate models. This is repeatedly to experiment and perform regression analysis. As we know in finance, indexes and calculations change all the time. what this would do (to some what degree) is to anticipate unexpected spikes, thus allowing there to be 

## Prerequisites 
1. ```$ pip install jupyter``` or, go onto [Jupyter Notebook](https://jupyter.org/) and click on _Try it in your browser_
2. ```$ pip install numpy```
3. ```$ pip install pandas```
4. ```$ pip install matplotlib```

## Getting started
Download the **SNP500-MonteCarlo.ipynb** file or click [here](https://raw.githubusercontent.com/habibkhan95/Monte-Carlo/master/SNP500-MonteCarlo.ipynb).
If you haven't installed Jupyter then upload the file into Jupyter on your browser. Whereas, if you have, then enter ```$ jupyter notebook```. This should now load your environment using a docker container. Now you will be able to select the file (SNP500-MonteCarlo.ipynb) where you have downloaded it. 

This example uses a few variables which need to be understood - 

| Variable | Description |
| --- | --- |
| `investment_value` | The initial investment. This then gets re-initiated after every year specified. |
| `time_period` | Duration of the forecasted model |
| `avg_return` | The average return which needs to be calculated for your chosen asset/index |
| `volatility` | The estimated volatility for a given time period |
| `eoy_investment_addition` | Amount to be added at the end of each year. This can be 0 |


