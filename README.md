# Book Catalog Scraper

This project is a simple web scraper that extracts book information from the first four pages of a book catalog website (https://books.toscrape.com/). The extracted data includes the book title, price, and star rating. The data is then saved to a CSV file for further analysis.
Requirements
To run this project, you will need Python 3.x and the following Python libraries:

    - pandas
    - BeautifulSoup4
    - requests

You can install these libraries using pip:

pip install pandas beautifulsoup4 requests

## Usage

    1. Clone this repository or download the book_scraper.py file.
    2. Open a terminal or command prompt and navigate to the directory containing the book_scraper.py file.
    3. Run the script using the following command:

		python book_scraper.py

   4. The script will scrape the book information and save it to a file named books.csv in the same directory.

## Output
The output CSV file will contain the following columns:

    Title: The title of the book
    Price: The price of the book in pounds (£)
    StarRating: The star rating of the book (1 to 5)

## License
This project is released under the MIT License.