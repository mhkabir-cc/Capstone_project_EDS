This is folder where all the scripts will be stored.


For executing the codes, I have considered the following steps:

The data analysis was carried out in several steps. First, the Eurostat weekly mortality data were cleaned and reshaped from wide format into a long time-series format in R. Weekly death counts were then organized by country, year, and week number. A historical baseline was created using pre-pandemic years, and this baseline was used to calculate excess mortality by comparing observed weekly deaths with expected deaths. The analysis then focused on summer weeks to identify unusual mortality peaks during major heatwave years.

Second, the UTCI heat-stress dataset in NetCDF format was processed to extract temporal patterns of heat exposure across Europe. Monthly values of high UTCI days were aggregated into annual and summer indicators, allowing the identification of years with particularly intense heat stress. Where needed, country-level summer exposure values were derived from the gridded dataset to match the mortality data.

Finally, the mortality and heat-stress datasets were combined for comparative analysis. Country-level summer excess mortality was compared across major heatwave years such as 2003, 2010, 2015, 2018, and 2022. The results were visualized using bar charts and time-based comparisons to highlight the most affected countries in terms of both absolute excess deaths and percent excess mortality. This combined approach made it possible to assess how periods of stronger heat stress aligned with increased mortality across Europe.
