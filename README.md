### PyScraper (eshopping-price-scraper)

PyScraper (eshopping-price-scraper) is a prototype project designed for scraping prices for products from online stores and other sources. Its main objective is to simplify the process of determining the price of a specific product, by utilizing an automated system to quickly search several store fronts and return a calculated mean average price while accounting for taxes, inflation and displaying a detailed and comprehensible price history, while aiding the user to select the best available offer.

### Current State

The current state of the project is capable of scraping the Mercado Livre interface using the BeautifulSoup Python library. Mercado Livre is a popular Brazilian online storefront, chosen for this prototype as it freely allows scraping.
I look forward to implementing ways to ethically obtain pricing data and further improve the scraping algorithm including support for different locations and currencies.

### Purpose

The sole purpose of this project is to facilitate the gathering, analysis and comparison of pricing data. The ability to quickly price items is extremely useful to budget efficiently and ensure the best deals on products.

### TODO Features:

1. Converting scraped prices to an excel sheet
2. Ability to add excel sheets and/or item lists and allow the program to get the price for each of them (multiple queries at once)
3. Finish documentation