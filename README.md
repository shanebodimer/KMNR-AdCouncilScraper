# KMNR Ad Council Scraper

Scrape new PSAs from the Ad Council website

## Requirements

- Python 3
- [Beautiful Soup 4](https://www.crummy.com/software/BeautifulSoup/)
- [Requests](http://docs.python-requests.org/en/master/)

## Installation

1. Clone the project

   `git clone git@github.com:KMNR/Ad-Council-Scraper.git`

2. Install required dependencies

   `pip install -r requirements.txt` or `pipenv install` (if developing locally)

3. Run `./scrape.py <path>`, where `<path>` is the download location (directory must exist, and will be cleared before assets are downloaded)
