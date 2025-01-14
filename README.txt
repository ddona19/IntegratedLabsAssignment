BOOK SCRAPPER ASSIGNMENT
This project scrapes data from a book website, for this case it's OpenLibrary, an open source digital Library created by the Internet Archives organization. This project can take book titles from a page, for this example I've taken titles from the Fantasy genre, these titles can then be send to OpenLibrary's own API and the project will showcase more data about the books scrapped. Such as author, the year the book was published, rating and page number.

Library requirements t orun code:
-Requests
-BeautifulSoup
-csv
-urlib.parse

After installing the libraries the code shouldrun normally. Book titles will be crapped via web scraping and for every title found the OPenLibrary API will be called to take further data from it. Data will be stored in a csv file and hten it will be encrymented using XOR, the csv file's contents will be encrymented, it can be decrymented agian by running the same function again.