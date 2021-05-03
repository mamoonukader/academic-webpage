---
title:  Data
summary:
date: 2020-01-30
weight: 120

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---

#### Income Risk 
We use the Survey of Income and Program Participation to estimate a household income process with time-varying variance of persistent income shocks (1980-2012). See 
{{% staticref "/publication/blpt_ecma/" %}}Bayer, Luetticke, Pham-Dao, Tjaden (2019){{% /staticref %}}
for details.


{{% staticref "files/data_figure2.xlsx" %}}Download data{{% /staticref %}}.


#### Inequality 
Our structural model in {{% staticref "/publication/bbl_inequality_2020/" %}}Bayer, Born, Luetticke (2020){{% /staticref %}} allows us to generate a quarterly time series for US inequality from 1954-2019. The model replicates the annual observations on the US top 10% wealth and income shares from the World Inequality Database, and we can use the Kalman smoother to create a quarterly time series.

{{% staticref "files/inequality_model.csv" %}}Download data{{% /staticref %}}.


#### Tax Progressivity

A measure of tax progressivity in the US, 1916-2017. In {{% staticref "/publication/bbl_inequality_2020/" %}}Bayer, Born, Luetticke (2020){{% /staticref %}} we extend the Mertens and Montiel Olea (2018)-calculations of average (ATR) and average marginal tax rates (AMTR) to the years 2013-2017 and with these calculate tax progressivity as in Ferriere and Navarro (2018) using the average and average marginal tax rate: P = (AMTR - ATR)/(1 - ATR).

{{% staticref "files/progressivity_measures_all.xlsx" %}}Download data{{% /staticref %}}.

Replication code: https://github.com/ralphluet/Tax-Progressivity-Construction

