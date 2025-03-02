## Web Scraping: Monitoring Craigslist Listings

This assignment involves building a web scraping tool to monitor Craigslist garage sales in Phoenix for suspicious activity. The script will search for specific keywords in listings, extracting and storing relevant URLs for further investigation. For this assignment, I utilized [this Cragslist link](https://phoenix.craigslist.org/search/sss?excats=5-2-13-22-2-24-1-23-1-1-1-1-1-1-3-6-10-1-1-1-2-2-8-1-1-1-1-1-4-1-3-1-3-1-1-1-1-7-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-1-2-1#search=1~gallery~0~0) for Garages and Moving Sales in the Phoenix area.

### Objectives
- Scrape Craigslist’s "Garage & Moving Sales" section for listings.
- Extract links from ad listings using BeautifulSoup.
- Search for suspicious keywords (e.g., "mattress," "cabinet," "wrench").
- Store results in a CSV file containing the keyword and listing URL
- Implement delays between requests to avoid detection.

Results can be found in this folder and is titled: Results_keywords_found.csv
