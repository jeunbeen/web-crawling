# web-crawling
Scraping news articles from naver.com

User guide
Set first_date, end_date and get the scraped data from each news company.
* query: your search word
* news_office_checked: company code

How it works
1. Collect urls (for the selected news company)
2. Save urls as a csv file
3. Read csv
4. Scrap title, date, and body text from each url
5. Save the information as a csv file - in the order of index, date, title, body, company, url