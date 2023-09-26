# Data Visualization Projects using Python Bokeh Library

## DataViz_1
<img width="869" alt="Screenshot 2023-09-26 at 15 04 20" src="https://github.com/asirimece/DataViz_Bokeh/assets/116263023/ee2a9e50-4eec-41ae-8874-fcbfdac7c512">

Aims to inspect the financial status of Amazon, Meta, Google, Microsoft and Apple (the one that has not announced massive layoffs yet) over the period of the pandemic. The dataset contains important items in the companies’ financial statements from 2019 Q1 to 2022 Q4.


## DataViz_2
<img width="1167" alt="Screenshot 2023-09-26 at 15 03 38" src="https://github.com/asirimece/DataViz_Bokeh/assets/116263023/64a1e66b-0824-4faf-a9db-7d1266b0bc05">

Shows the stock data of Apple in a candlestick chart.
An overlay of two financial metrics, ‘EPS Growth’ and ‘PE Ratio’, which investors refer to when evaluating the company’s stock.
Interactive features such as panning and zooming are implemented, as well as a clickable interactive legend to hide or show a metric. A range selection plot zooms in on one region in the chart.


## DataViz_3
<img width="881" alt="Screenshot 2023-09-26 at 15 05 32" src="https://github.com/asirimece/DataViz_Bokeh/assets/116263023/ad17ef5f-a5db-46a4-98b3-60930a445d5c">

Interactive visualization app for the analysis of a high-dimensional dataset.
The dataset contains information on 750 public companies in the tech industry with 5 categorical columns and 102 numeric columns.
The dataset is first processed with the principal component analysis (PCA) technique to reduce the 102 numeric features to 2 principal components, based on which the companies are clustered in.
Then, the PCAs are visualized in a PCA plot and applied a color map.
In addition, a subplot shows the statistic of an original feature where selection widgets such as lasso tool are implemented.


## DataViz_4
<img width="904" alt="Screenshot 2023-09-26 at 15 14 14" src="https://github.com/asirimece/DataViz_Bokeh/assets/116263023/a863b1ca-1c50-4da5-ba5d-f95a5432dd90">

Interactive map to showing the geographic distribution of tech companies in the US.
Each circle in the map represents the total market cap and number of employees of the tech companies in a city, which are encoded in the color and size respectively. The user can: 
- tap on a circle to show in the subplot the market cap and number of employees of each company in that city,
- use the slider to change the lower bound of the market cap to filter out the companies with a market cap smaller than this value.
- click the play button to see the animation of the changes in the market cap and the number of employees over the years.
