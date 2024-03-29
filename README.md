This Python program is designed for web scraping data from Twitter. It uses the Selenium library to automate interactions with the Twitter website and a Microsoft Edge WebDriver for web navigation. Here's a brief overview of the program:

Dependencies: The program uses the msedge.selenium_tools library for web automation with Microsoft Edge. You'll need to install it.

Web Automation: The program automates actions on the Twitter website, including logging in, entering search queries, changing page sort, and scrolling down to collect tweet data.

Data Collection: It collects data related to tweets, including user information, tweet text, post date, reply count, retweet count, and like count.

Data Storage: The collected data is saved to a CSV file specified by the path variable. It creates a CSV file and appends data to it.

Main Function: The main function orchestrates the entire scraping process, taking Twitter credentials, search terms, and the output file path as inputs.

Usage: The script is set up to run if it's the main file. It initializes the necessary parameters and starts the scraping process.

Unique Tweet Handling: It uses a unique_tweets set to ensure that only unique tweets are saved to the CSV file based on a generated tweet ID.
Please note that web scraping can be against the terms of service of many websites, including Twitter. Ensure you have the necessary permissions and follow ethical guidelines when using this script. Additionally, keep your Twitter credentials secure and do not share them publicly.

PRE-REQUISITES
To run the Twitter scraper project you've provided, you'll need several prerequisites:
1. Python: Ensure you have Python installed on your system.
2. Selenium: You need to install the Selenium library to automate the web interactions.
3. Microsoft Edge WebDriver: This project uses the Microsoft Edge WebDriver for web automation. You need to download the WebDriver executable compatible with your Microsoft Edge version. Make sure to place the executable in a directory included in your system's PATH environment variable.
4. Twitter Developer Account and API Keys: You need to create a Twitter Developer account and obtain API keys to access Twitter's data. Follow these steps:
1)Go to the Twitter Developer Platform: Twitter Developer.
2)Create a new Twitter App to obtain API keys.
3)Note down the API key, API secret key, Access token, and Access token secret.


