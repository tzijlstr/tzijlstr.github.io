1. Scraping Data
   - https://www.globalproductprices.com/rankings/coca_cola_price/
   - https://wisevoter.com/country-rankings/gdp-by-country/
   - https://divercitytimes.com/economy/currency/currency
     
   Data was scraped from these three sites to make the charts and tables used on this website.
   - The first site contained information pertaining to the price of Coca-Cola and their respective countries
   - The second focuses on those countries corresponding GDPs
   - The last includes the countries currency codes
   The following table shows a ten country sample of the data collected.

![Complete Table](FullTable.png "Complete Data Table")

2. Cleaning up and organizing data.
   - Combining the Price, GDP and Currency data to form 1 table of information
   - Converting the Price from USD to CAD for all countries data
   - Dropping Columns not need for the analysis
   The following table shows the cleaned and organized data table.
  
![Cleaned Table](CleanTable.png "Cleaned Data Table")
  
3. The graph below displays the Coca-Cola price in selected nations compared to the price in CAD
   Notice that all countries shown in the graph contain prices significantly higher than the Canadian Price.

![CAD Prices](CocaPrice.png "CAD Prices")

To establish whether or not GDP and Price are correlated the following Scatter Plot was generated

![GDP per Capita versus Price](GDPrice.png "Correlation between GDP per Capita and Price")

In conclusion there is no correlation between the GDP of a nation and the Price of Coca-Cola

A more likely reason behind the price differences found is licensing agreements for distribution and production within nations as well as royalities and external factors related to the health of the nations respective economy.
