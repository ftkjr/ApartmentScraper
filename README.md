# ApartmentScraper

This repository contains two jupyter notebooks for scraping apartments for rent online then sorting through the data.

### Scraper

This hits the site, looks through the available list of apartment buildings (referred to as residences in the code), then goes to each residence's dedicated page and collects data on the listed apartments.
It also collects the information on the residence itself, including the address. 
This address is used in the sorting notebook to get the commute time between the residences and any location provided. 

### Sorter

The other notebook cleans and consolidates the collected data. Using the collected data, we compute an apartment rating based on the price and square footage.

#### If you have an api key for google distance matrix:
If an api key for the google distance matrix has been provided it collects the commute time from each residence to whatever destination has also been provided.
I'd provide instructions for how to get it but its in the name. (google it)
