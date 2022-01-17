# Amazon-Web-Scarper

Created a web scraper using simple functions to check price of a product on amazon (can be duplicated to check price at other markets with specific changes to class ids of respective data)

Procedure:

1. Import libraries
2. Specify the URL from where data is to be scraped
3. Specify system specific headers
4. Create soup objects required for scraping
5. Create data objects to be scraped
6. Clean data
7. Create a csv to store and append the data scraped
8. Create a function check_price combining all above operations
9. Create a function send_mail to send price alerts when the check_price condition is met
