# CryptoView - Python and Power BI Project

CryptoView is a versatile Python and Power BI project for analyzing cryptocurrency data. With Python, you can scrape crypto data using libraries like cryptocmd and cmcscraper. Power BI allows you to create a dynamic dashboard with charts, slicers, KPIs, and forecasts to visualize and gain insights into the crypto market.

## Features

- Data Scraping: Utilizes the cryptocmd library to scrape data for popular cryptocurrencies. The data is collected using the cmcscraper module and saved to a CSV file using pandas.
- Multipage Dashboard: The Power BI dashboard consists of multiple pages, each serving a specific purpose.
  - Index Page: Serves as the landing page of the CryptoView dashboard.
  - Crypto Overview: Provides an overview of the crypto market with a line chart showcasing market cap and volume over time. Slicers allow users to switch between market cap and volume, select specific cryptocurrency tickers, years, and months or quarters. The page also includes a table with ticker names and symbols, as well as KPIs for market cap, volume, high, and low values. A "Reset All" button is available to reset slicer selections.
  - Price Insights: Displays line charts for high and low prices, as well as open and close prices, to provide insights into crypto price trends.
  - Rank Change: Compares the ranks of cryptocurrencies based on market cap or volume over time using a ribbon chart. Users can switch between market cap and volume comparisons using a slicer.
  - Forecasts: Presents predictions for the next 24 Months with a confidence level of 95%. Users can explore forecasts for volume, market cap, open price, and close price. A slicer allows switching between these metrics.
- Navigation Bar: The Power BI dashboard includes a navigation bar on the left side for easy navigation between different pages.

## Screenshots

### Jupyter Notebook
![Jupyter Notebook_page-0001](https://github.com/adityachoudhary7/CryptoView/assets/88120344/ca817a6b-2e5c-45af-8622-f89ce8bb386d)


### PowerBI 
![CryptoView_page-0001](https://github.com/adityachoudhary7/CryptoView/assets/88120344/b1c0dae8-9598-4717-9167-0b46f424f591)
![CryptoView_page-0002](https://github.com/adityachoudhary7/CryptoView/assets/88120344/90cb95cc-2504-4af3-91fb-855e97f7ff9f)
![CryptoView_page-0003](https://github.com/adityachoudhary7/CryptoView/assets/88120344/58659dab-57d9-44c8-bc32-faa60428a568)
![CryptoView_page-0004](https://github.com/adityachoudhary7/CryptoView/assets/88120344/c439b318-c530-43aa-b70b-be6570a6a6a8)
![CryptoView_page-0005](https://github.com/adityachoudhary7/CryptoView/assets/88120344/778f69fa-f0bb-46fb-b105-10669880288e)





## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgements

CryptoView was developed using the following libraries:

- cryptocmd
- pandas
- Power BI

A special thanks to the creators and maintainers of these libraries for their invaluable contributions to the open-source community.

## Contact

For any questions or inquiries about CryptoView, you can reach me via [LinkedIn](https://www.linkedin.com/in/aditya-choudhary-318309150/) or by opening an issue on the GitHub repository.

---

Thank you for your interest in CryptoView! Explore the world of cryptocurrencies and gain valuable insights with this Python and Power BI project.
