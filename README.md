# News_Scraper
News scraper is the ETL component for a larger project. it scrapes text from major news sites and performs minor manipulations to feed into an NLP loop. 


## Theory
In theory, every news site on the internet conforms to certain conventions to make it easier for social media sites to hadle them. By targeting the text in the html of news sites, News Scraper retrieves the text data for processing, and ignores the unecessary frills like video, photos, buttons, although individualmodificatins may need to be performed for specific sites.

## ETL
Extract, Transform, Load or ETL is the process of retrieving raw data from a source (extract), preparing it into useable form for analysis (transfrm), then passing it onto a datavase or machine for storage or processing. Newsscraper aims to be the ETL pipeline for a larger project involving NLP and machine learning. 
News scraper is a simplified raw pipeline as it is intended to scrape from any news site on the internet. As such it casts a wide net for text and performs minimal transformaton. 
