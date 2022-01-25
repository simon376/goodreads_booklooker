# Used Book Search Application
## Search booklooker for sales on (used) books from the goodreads to-read shelf

very much work-in-progress!
small notebook to try web-scraping

- reads [exported goodreads dataset](https://www.goodreads.com/review/import)
- read into pandas, clean up data
- use **BeautifulSoup** to scrape booklooker.de
- search booklooker using ISBN or author, title
- build a dataframe containing all found sales for each searched book
- export dataframe to (ugly) HTML for quick overview, with links to the sale offers


TODO:
- [ ] add support for other sites, e.g. abebooks
- [ ] automate goodreads data export using beautifulsoup or selenium
- [ ] create web application using flask, fastAPI, etc.
