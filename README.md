The scrape.py is the python code hat scrapes eBay deals using selenium and pandas to save to a csv file. (I sed csss selectors to locate elements and I used try except to avoid potetnial errors. Also, i used EC waits to ensure the scraping method works properly).
The workflow in the repo managed to scraped the data every 3 hours for 1 day (fri to sat)
The scraped data are saved too ebay_tech_deals.csv (CSV file) (899 row)
To clean the data, (in file clean_data.py), I handled outliers and missing info (NaN or null) using pandas library (filling missisng values - sripping unwanted symbols - specifiying percentage of discount..)
when he cleaned data was ready, I saved it to cleaned_eBay_deals CSV file to prepare it to visiualization.
The visualization code is in EDA.ipynb where i used pandas, matplotlib, and seaborn for histogram - bar plot - bar chart visualization to compare prices - see frequency of shipping option - textt analysis to see what brand is more frequent (apple - samsung..)....etc
