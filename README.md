# Exploratory Data Analysis for Sekundärregelleistungsmarkt


We analyze the marginal price of `Sekundärregelleistungsmarkt` in Germany and Austria.

In a simplied version of explaining, the regelleistungsmarkt is aimed for stabilizing the electricity frequency control by requesting electricity in a very short period of time.

Data for this analysis are taken from [regelleistung.net](https://www.regelleistung.net/ext/) and you can find the terminologies and get better understanding of the regelleistungsmarkt in this website. We are not considering `Primärregelleistungsmarkt` and `Minutenreserveleistung` in this notebook but this notebook can be easily extended to analyze those market as well. This analysis also doesn't focus on a specific regional `Übertragungsnetzbetreiber (ÜNB)` or a specific country but you can easily filter it and apply the same analysis.

Note that the data cover the dates from July 12th 2018 to August 5th 2020: the process of the general regel\"arbeits\"markt has been significantly changed since November 2nd 2020. For more information, please refer to [this file by regelleistung.net](https://www.regelleistung.net/ext/tender/remark/download/128315996).

## Running the notebook

Assuming that you have python3 installed on your computer,

```
   $ git clone https://github.com/hahey/regelleistung_EDA.git
   $ cd regelleistung_EDA
   $ python3 -m venv .venv3
   $ source .venv3/bin/activate
   $ pip install -U pip setuptools
   $ pip install -r requirements.txt
   $ jupyter notebook
```

Check out `http://localhost:8888` at your browser.

## License

All the Jupyter notebook files in this repository are licensed under `CC BY-NC-SA 4.0`.
