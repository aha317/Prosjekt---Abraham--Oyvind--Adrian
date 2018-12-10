# Prosjekt---Abraham--Oyvind--Adrian
Group project--- BED-2056
BED-2056 - Project - Abraham, Adrian, Øyvind

The focus of the project have been looking at the commodities market, as well as OSEBX incl.
the stocks (ticker) NHY, MHG, SALM and EQNR. The commodities we chose to look at was Copper, Aluminium, 
Fish Prices, and also Crude Oiland Crude Oil WTI. The reasong for choosing the four stocks 
we did, was because of the volume of stocks traded in the given stock on OSEBX.

The data was retrieved from different sources, where netfonds.no was the biggest contributor.
Because of different sources of data, we decided to remove data before 2011, as it was non-comparable
to other data because of missing data. Because of this, we only look at the stock market
from 2011 moving forward. The dataretrieving is however dynamic, which gives us the opportunity
to retrieve data moving forward. 

After the data was cleaned and prepared, we use the stocks to calculate a optimal portfolio. 
Here we also visualize the efficient frontier. 

Moving on, we visualize the development from 2011, with both development of the stocks incl. OSEBX,
as well as log returns and drawdowns of peaks.

We also calculate the rolling correlation (100 days) with OSEBX, to see how the prices of
commodities correlate with OSEBX. We see here that most commodoties correlate positively with OSEBX,
but according to the graph fish prices correlate negative. The may be due to the method of 
calculating and cleaning the data. As fish prices were weekly data, it had to be converted to 
daily data. This then gives us 0% returns on most days, and hence, will most of the time not correlate
with the returns on OSEBX.

Our final graph shows development of commodity prices.
