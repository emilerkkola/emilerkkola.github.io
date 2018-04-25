---
title: "Integrated Payment Client: Transaction Data Scraper"
layout: post
date: 2017-09-01
tag: data scraping, transactions
image: https://www.nfcworld.com/wp-content/uploads/2017/08/worldpay-logo-200w.jpg
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Transaction data scraper"
category: project
author: eemelierkkola
externalLink: false
---


Integrated payment clients enable communication between the firmware running on pin-entry devices and mobile / desktop devices to enable payments processing. These clients store transaction information in log files, that allow for troubleshooting of errors and transaction tracking. 

Error analysis through log files is often left as manual labour for technical consultants and data analysists, resulting in long and tedious scrolling through hundreds of log files each with thousands of lines of transaction info. However, this process could easily be automated using simple dictionary and list comprehension in python. Upon starting as a data analyst at Worldpay, I began developing a log utility tool to scrape key transaction information from hundreds of log files at a time. The logic of the tool greatly depends on the logging style of an individual payment client, and the transaction flow in this specific case was not linear. Nested transactions occur frequently, and for this reason I assigned a unique thread number as the dictionary key for each transaction. 

The ability to scrape info such as times between key transaction events allows for intelligent analysis on whether an issue is server or client related, and enables the team to respond to issues appropriately by simply glancing through the spreadsheet that the utility outputs. Each transactions flow is mapped in a spreadsheet row allowing for easy locating of errors and their causes. For legal reasons I have not provided the source code here, however the screenshot below shows the nature of the data scraped in the spreadsheet produced.

---

Stack:

- Python
- py2exe

---

