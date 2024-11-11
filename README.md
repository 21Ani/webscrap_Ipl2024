
## IPL Auction Data Web Scraper

This project is a web scraping tool that extracts data from the [official IPL auction page](https://www.iplt20.com/auction#autab4-2022). The script pulls details about each IPL team, including the team's name, funds remaining, number of overseas players, and total players. The extracted data is stored in a CSV file for further analysis or reference.

### Project Overview

The project uses Python with the `requests` library to fetch HTML content from the IPL auction webpage. BeautifulSoup is then used to parse and extract relevant data for each team. The information includes:
- **Team Name**: The official name of each IPL team.
- **Funds Remaining**: The budget left for each team.
- **Overseas Players**: Count of overseas players in the team.
- **Total Players**: Total number of players in the team.

The extracted data is saved into a CSV file (`team_info.csv`), making it easy to use for analysis, reporting, or visualization.

### Prerequisites

Ensure you have the following Python libraries installed:
- `requests`
- `beautifulsoup4`
- `pandas` (optional, for further data manipulation)


### Note
This script depends on the structure of the webpage remaining consistent. If the webpage structure changes, adjustments to the HTML parsing may be necessary.

