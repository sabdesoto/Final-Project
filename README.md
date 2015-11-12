# Project Vegetation
# Billy Hung, 2015-11-07

# Project Introduction
Climate change is one of the greatest threats facing the planet. Since the Industrial Revolution, human have been actively releasing CO2 into the atmosphere by burning of fossil fuels. This excess amount of CO2 into the atmosphere traps more infrared radiation that would otherwise be reflected to outer space. The mean global atmospheric CO2 concentration increased by 9% during 1980-2000 (Nemani et al, 2003). As a consequence, global average temperature has been rising. According to NASA’s Goddard Institute for Space Studies (GISS), the average global temperature on Earth has increased by about 0.8° Celsius since 1880. 
Most of the observed climatic changes have been reducing climatic constraints to the growth of primary producers, such as increase in CO2 and temperature results in higher rate of photosynthesis. Although most studies reached a consensus that climate change resulted in an increased of net primary productivity in terrestrial and marine ecosystems (Nemani et al, 2003; Brown et al, 2013), the effects of temperature changes on vegetation are still undetermined. Some studies show increased temperature leads to a decrease in vegetation (Jin et al, 2008), other studies shows increased temperature leads to a increase in vegetation (Zhang et al, 2013). Aside from temperature change, these papers also suggest that rainfall pattern could potentially be a factor in determining the change in vegetation. 
The goal of this study is to investigate the effect of temperature and rainfall pattern on vegetation change. The leading hypothesis is that increased temperature and rainfall would lead to a upward shift of vegetation because the higher elevation provides a more suitable environment for the plant species and the whole vegetation.

# Flow Chart
* Organization by adding an elevation column for explicitly 
* Narrowing the analysis by subsetting an elevation range
* Visualizing the data by using scatterplot and box plot 
* Performing statistical analysis
* Checking conditions for the analysis

# How it works
The python file takes in, organizes (add elevation column), and subsets datasets (subset elevation above 3000m). Produces scatterplots and box plots for visualizing the data, and finally performing statistical analysis (linear regression or multiple regression is time is permitted) on the dataset.



# Datasets
* Temperature data from TCCIP (1982 to 2012). The dataset record monthly mean temperature for all elevation range (0-3950m)
* Rainfall data from TCCIP (1982 to 2012). The dataset record monthly mean rainfall for all elevation range (0-3950m)
* Vegetation (Normalized Difference Vegetation Index) data from AVHRR (1982 to 2012). The dataset record monthly vegetation index for all elevation range (0-3950)

# Libraries used
* For loading data: pandas
* For plotting: matplotlib
* For statistical functions: scipy and statsmodels
