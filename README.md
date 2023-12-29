 # TikTok Search Suggestions Scraper

## Overview
This project uses the Git Scraping technique, popularized by Simon Willison, to scrape TikTok Search Suggestions. The data is fetched hourly using GitHub Actions.

## How it Works
- **Scraping**: The script fetches search suggestion data from TikTok's API.
- **Scheduling**: GitHub Actions are scheduled to run this script every hour.
- **Data Storage**: Scraped data is stored in the repository, providing a history of changes over time.

## Usage
You can view the scraped data in the `search-suggestions.json` within this repository. Each hourly update is committed, allowing for tracking changes over time. See [https://flatgithub.com/juppcamper/tiktok-git-scrp?filename=search-suggestions.json](https://flatgithub.com/juppcamper/tiktok-git-scrp?filename=search-suggestions.json) for more. 

## Acknowledgements
This project is inspired by Simon Willison's Git Scraping approach.

## Contributing
Contributions to improve the scraper or extend its functionality are welcome. Please open an issue or pull request.


## Disclaimer
This project is for educational purposes only. Ensure compliance with TikTok's Terms of Service regarding data scraping.
