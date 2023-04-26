# IMDb Crawler

This is a Python script that scrapes Movies and Series on IMDb and outputs the data to a csv file.

### Prerequisites

- Python 3.x
- Requests
- Beautiful Soup 4
- Pandas

## Installation

1. Clone this repository
2. Install the required packages

## Usage
1. Change url variable with url with filters that you want to scrap
2. Run `python imdb-crawler.py`
3. The script will scrape the all movies & series and save the data to a file named `movies.csv`.

## Data Format
The following data will be scraped for each movie:

- id
- title
- year
- genres
- link
- audience_rating
- runtime
- rating
- votes
- plot
- lq_poster
- poster
- actors
- directors

## Tips for Running the Script

To avoid getting banned by IMDb, it is recommended to run the script on Google Colab. This will ensure that the script is executed from different IP addresses, thus reducing the risk of getting blocked.

## Acknowledgments

This project is based on   [ Web Scraping 101 in Python blog by Morten Hegewald](https://medium.com/@mortenhegewald/web-scraping-101-in-python-35f8653b1c97).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).



