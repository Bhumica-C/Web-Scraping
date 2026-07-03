# Web Scraping — Books to Scrape
## Task 1

## Project Overview
This project involves scraping real book data 
from books.toscrape.com using Python and 
BeautifulSoup. 1000 books were scraped across 
50 pages collecting Title, Price and Rating.

## Business Problem
A bookstore company needs to:
- Collect competitor book pricing data
- Understand rating patterns
- Build a dataset for further analysis

## Tools Used
- Python
- BeautifulSoup4
- Requests
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Steps Performed
1. Connected to books.toscrape.com
2. Parsed HTML using BeautifulSoup
3. Scraped 1000 books across 50 pages
4. Extracted Title, Price and Rating
5. Cleaned price (removed £ symbol)
6. Converted ratings from words to numbers
7. Visualized price and rating distributions
8. Exported data to CSV

## Key Findings
1. Average book price is around £35
2. Ratings are evenly distributed 1-5 stars
3. Most books are priced between £10-£60
4. Successfully built custom dataset 
   from scratch using web scraping

## Files
- scraped_books.csv (1000 books dataset)
- price_distribution.png
- rating_distribution.png
- README.md

## Author
- Name: Bhumica C
- Domain: Data Analytics
