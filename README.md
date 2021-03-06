## Welcome

This repository is to showcase my role in the application of Deep Learning to a tricky real-world problem: beating the Texas Electricity grid's day-ahead predictions for their own prices.

This was a final project for CS 294-36, Deep Time Series Learning, taught by Francois Belletti https://github.com/bellettif. Teammates included PhD Candidates Brian Kilberg & Pedro Ivo Bastos Hespanhol, masters student Nicolas Mon, and undergraduate Liam Purvis (myself). 

The core of the data, that from the texas electric grids, I compiled into a database as contracting work for intersectpower.com and queried the relevant nodes for this project. Hespanhol sourced the financial data, Mon found the weather data, and Brian helped with the  Neural Net Design. Not all the code is included (particularily the hyperparameter sweeps by Mon), but all of my code is here, save the mysql queries of the database for the electric grid data.

To read the final report, please go to the Electric_Grid_Prediction notebook. In order to see the modeling code, please observe Liams_Code.ipynb. The still somewhat messy data wrangling code is in Data_Wrangling.ipynb (the raw data is too large to store in github. If you are interested in reproducibility, please contact me).

I hope this serves a both an inspiring application of Deep Learning, an interesting code sample, and a helpful example of a research question that I came up with and took through the entire Data Science process from data collection, wrangling, and modeling to a compelling conclusion. 
