---
description: This is meta description
draft: false
subtitle: ""
title: Frequently Asked Questions
---


{{< faq "How do I provide data for analysis?" >}}
To use the dashboard select 'CSV File Upload' function just above the dashboard.  A template file with the data format expected by the dashboard can be [downloaded](files/MYPORTFOLIO.zip), edited with your data and then uploaded via the CSV File Upload function.  If needed, the format of the tickers in the file for upload can be cross-referenced with [Yahoo Finance](https://finance.yahoo.com). After uploading your .csv file see the portfolio report by selecting *Dashboard* and then *Portfolio Report* from the sidebar menu.
{{</ faq >}}

{{< faq "The report is not running properly after uploading my data, what gives?" >}}
Most likely the data has been provided in a format other than .csv or the .csv file that has been provided does not meet the expected format for the application to work with. An example file with the content the application is designed to work is [available for download](files/MYPORTFOLIO.zip). The application expects a .csv file that contains:  
**Description:** Either the name of the company or "CONTRIBUTION" if the action is one of "DEPOSIT"  
**Action:** Recorded as "DEPOSIT" for a contribution or "BUY" for a stock purchase  
**Symbol:** The ticker symbol as referenced by [Yahoo Finance](https://finance.yahoo.com) if the action is one of BUY or "DEPOSIT" if the action is one of "DEPOSIT".  
**Date:** The date of the stock purchase or constribution deposit in the format of m/d/yyyy.  For example December 27 2017 purchase would be provided as 12/27/2017.  
**Quantity:** The number of stock purchased.  If the action is one of DEPOSIT this value can be entered as 0.  
**Currency:** The currency applied to the the stock purchase.  Currently USD and CAD are handled by the application.  
**BuyPrice** If the Action is one of "DEPOSIT" this is the amount of the DEPOSIT made for stock purchases.  If the Action is one of "BUY" this per unit purchase price for the stock.  

{{</ faq >}}

{{< faq "Are you keeping a record of my supplied data?" >}}
No data user portfolio data is kept by this service.  This is precisely the reason why users of our service provide their data when an analysis is wanted via an upload rather than keeping a database of all user's investment details.  No customer data is retained locally.  The current session is completed as soon as the user leaves the website.
{{</ faq >}}

{{< faq "I need a unique report, can you make it?" >}}
E5C Analytics would be pleased to have an opportunity to respond to a custom reporting or data analysis need.  Drop us an email describing your analysis or reporting need and let us reply with how we can help you fulfill your requirement.
{{</ faq >}}


{{< faq "Do you accept requests for new features in the service?" >}}
We are interested to hear what you have in mind for features and enhancements.  The only thing we ask is that you keep our guiding principles of **Value for Money**, **Meaningful Metrics** and keeping a **Simple Interface** in mind with any suggestions.    Development requests fitting those criteria will certainly be considered as future enhancements providing value-add to the service.
{{</ faq >}}

{{< faq "Do you provide refunds?" >}}
At this point the service is free, so no refunds are offered obviously.  Should there ever come a time when the service is subscription fee-based a refund policy will be part of that subscription agreement. 
{{</ faq >}}


