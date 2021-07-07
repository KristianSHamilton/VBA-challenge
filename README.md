The VBA of Wall Street
Created by Kristian Hamilton
Date created: 7/6/2021
Last updated: 7/7/2021

stock_scraper_v2_subroutine.cls will aggregate data from given Excel spreadsheet and populate a table to the right of the dataset.

This table has the stock's Ticker for each stock within the dataset of each sheet, 
yearly price change and % change from the stocks first open and last close within the dataset,
and the Total Volume of the stock traded from the period within the dataset.

This subroutine also will take the data populated within the newly created table and find the stock with:
the greatest % increase,
the greatest % decrease,
the greatest Total Volume.

Once run stock_scraper_v2_subroutine.cls will run across all sheets within an Excel workbook.

I don't like to talk about stock_scraper_v1...