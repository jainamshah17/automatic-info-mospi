# Automation of Statistical Information Compilation
The Ministry of Statistics and Programe Implementation (Stats & PI) collects statistical information (mostly pdf reports) from all other ministries websites (38 in total), these different ministries uploads reports randomly i.e. date and time is not fixed. The officials from Min. of Stats & PI have to regularly browse through these websites and check whether they have uploaded new reports or not. Manually browsing these many websites everytime is tedious task.  
## Overview of the System
![Overview](https://github.com/jainamshah17/web-scrapping/blob/master/images/overview.PNG)   
## Description / Features
We automated the process of browsing different ministries websites by creating a web-scraping tool, it constantly monitors these websites and immediately notifies the officials regarding any new updates. We also provided a web-application for controling the web-scraping tool, and other managerial features.
  - One Click Search (Scrapes when you search)
  - Automatic Search (once set, no need to open the web-app)
  - Aggretaion of all available reports on the web-app
  - Instant Notification via SMS/E-mail
## Web-Application
For searching:  
![Searching](https://github.com/jainamshah17/web-scrapping/blob/master/images/search.PNG)   
Aggregated Reports:  
![Aggregated Information](https://github.com/jainamshah17/web-scrapping/blob/master/images/agg.PNG)   
## Technology Stack
Web Scraping Tool : Python, BeautifulSoup4 (HTML Parsing Library)  
Web-App: PHP, HTML, CSS3, JavaScript  
Database : MySQL  
