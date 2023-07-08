# Top 250 IMDb Movies Data

This repository contains a Python script to scrape data from the top 250 movies on IMDb and save it as a CSV file.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- Python 3.x
- Selenium
- BeautifulSoup
- Polars (or Pandas)
- Chrome WebDriver (or WebDriver for your preferred browser)

## Usage

1. Clone this repository or download the code files.
2. Install the required dependencies by running the following command:
   ```shell
   pip install selenium beautifulsoup4 polars webdriver_manager
   ```
   Note: You may need to install the specific WebDriver for your chosen browser. In this example, we're using Chrome.

3. Open the Python script file (`scrape_imdb_top250.py`) in a text editor.
4. Run the script by executing the following command:
   ```shell
   python scrape_imdb_top250.py
   ```

The script will launch a browser, scrape the top 250 movies data from IMDb, and save it as a CSV file (`top250imdb_2023-07-07.csv`).

## Data Description

The scraped data includes the following fields for each movie:

- Rank: The rank of the movie in the IMDb Top 250 list.
- Title: The title of the movie.
- Rate: The IMDb rating of the movie.
- Year: The year of release.
- Duration: The duration of the movie in minutes.

## Libraries Used

The script utilizes the following Python libraries:

- [Selenium](https://pypi.org/project/selenium/): Used for automating browser interactions.
- [BeautifulSoup](https://pypi.org/project/beautifulsoup4/): Used for parsing HTML content.
- [Polars](https://pypi.org/project/polars/) (or [Pandas](https://pypi.org/project/pandas/)): Used for data manipulation and analysis.

## Note

The code provided is meant for educational and personal use only. Please be respectful of IMDb's terms of service and avoid excessive scraping or unauthorized use of the data.

## License

This project is licensed under the [MIT License](LICENSE).
