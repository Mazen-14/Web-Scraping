# Web-Scraping
- The project extract specific data from an HTML webpage using Python and saving it into a JSON file and CSV file.
- The extracted data includes hyperlinks, video links, and book card information (title, price, stock availability and button text).

# Files-Contained
- webscraping.ipynb: Jupyter Notebook for all the 6 questions codes
- table.csv: for Q1
- table_data.csv: for Q2
- productinformation.json: for Q3
- input.json: for Q4
- link.json: for Q5
- featuredproduct.json: for Q6

# Tools-Used
- Python
- BeautifulSoup: To parse HTML
- CSV: To save the extracted data in CSV format
- JSON: To save the extracted data in JSON format

# Challenges-Faced
- Some tags didn't have enough attributes, causing me not to be able to get specific tags
- Multiple p tags in product information cards: To solve this I had to index the price and stock p tag
- Special characters like £ were written as \u00a3: This was resolved by adding ensure_ascii=False while exporting to JSON

# Done-By
Mazen Mohamed Hemdan Ahmed


