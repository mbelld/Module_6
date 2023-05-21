# Module_6
Module 6 submission

required libraries and dependencies

* import pandas as pd
* import hvplot.pandas
* from pathlib import Path


leveraged the following website for use of brackets to list the grouping attributes --> https://stackoverflow.com/questions/17679089/pandas-dataframe-groupby-two-columns-and-get-counts


prices_by_year_by_neighborhood = sfo_data_df.groupby(['year', 'neighborhood']).mean()
