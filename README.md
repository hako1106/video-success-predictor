# TikTok Data Scraper with Selenium

This project uses Selenium to collect video data from TikTok based on specific hashtags. It extracts metadata such as likes, comments, shares, saves, appends language parameters to URLs, and retrieves video transcripts using a third-party tool.

## Features

- Scrape videos from TikTok by hashtag
- Extract video titles and associated hashtags
- Collect engagement metrics: likes, comments, shares, saves
- Add `?lang=vi-VN` to each video URL
- Retrieve transcripts using https://script.tokaudit.io/

## Requirements

- Python 3.x
- **[Google Chrome](https://googlechromelabs.github.io/chrome-for-testing/)**  
  You need to have Google Chrome installed. It’s recommended to use a version from the Chrome for Testing site for better compatibility with automation tools.
- **ChromeDriver**  
  Ensure that the version of ChromeDriver matches the version of Chrome you are using. You can also download the correct driver version from the [Chrome for Testing](https://googlechromelabs.github.io/chrome-for-testing/) page.
- Python libraries:
  - selenium
  - re
  - csv

To install Selenium, run:

```bash
pip install selenium
```

## Configuration
In your script, make sure to edit the following paths:

```bash
chromium_binary_path = 'chrome-win64\\chrome.exe'
chromium_driver_path = 'chromedriver-win64\\chromedriver.exe'
```

Also, define the hashtag(s) you want to scrape:
```bash
hashtags = ["homestay"]
```
