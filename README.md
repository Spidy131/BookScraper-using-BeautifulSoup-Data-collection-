# BookScraper-using-BeautifulSoup-Data-collection-
This project is a simple web scraping script built with Python, BeautifulSoup, and Pandas. It scrapes data from the open-source website BooksToScrape, collecting information about books such as title, price, rating, and availability.

🔍 Features
      Extracts:
      Book title
      Price
      Star rating
      Availability
      Stores the data in a structured Pandas DataFrame
      Saves the result as a CSV file (books_data.csv)
Project Structure:
      bookscraper-bs4/
      │
      ├── books_scraper.py       # Main scraping script
      ├── books_data.csv         # Output CSV file
      └── README.md              # Project description

🛠 Requirements
     Python 3.x
     BeautifulSoup (bs4)
     Requests
     Pandas
Install the requirements:
    !pip install beautifulsoup4 requests pandas
Run the script directly in a Python environment or Jupyter/Colab notebook:
    python books_scraper.py
The script generates a CSV file named books_data.csv containing the scraped data.

