# london-housing-price-analysis
Exploratory data analysis of London borough house prices (1998–2018) using pandas, identifying Hackney as the borough with the greatest price growth at 6.2×.

This project analyzes UK house price data from the London Datastore to identify which of the 32 London boroughs experienced the greatest average house price increase over a 20-year period (1998–2018). Using Python and pandas, the raw Excel data is cleaned, transposed, and melted into tidy format before applying a price ratio model. Two independent approaches — a custom function with iteration and a pandas groupby/unstack pipeline — both confirm Hackney as the top borough with a 6.2× price multiple.
