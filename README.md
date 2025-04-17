# Reddit-And-Twitter-Scrapers
This repository contains two Python-based scrapers for collecting and processing textual data from Reddit and Twitter/X. Using the praw and tweepy libraries.

# Social Media Scrapers: Reddit & Twitter (X)

Two lightweight and general-purpose Python scrapers designed to collect textual data from **Reddit** and **Twitter/X**. The scrapers are useful for building datasets for Natural Language Processing (NLP), text classification, sentiment analysis, and more.

---

## Features

  - Reddit Scraper** (using `praw`)
  - Scrapes posts from one or more subreddits
  - Search by keyword
  - Filters out empty or suggestion-style content
  - Optionally limits post content to a fixed word count (e.g., 30 words)
  - Saves structured CSV with username and post content

  -  Twitter/X Scraper (using `tweepy`)
  - Collects tweets using the Twitter API v2
  - Supports keyword and hashtag search
  - Automatically excludes retweets and long tweets (optional)
  - Saves structured CSV with username and tweet content

---

##  Requirements

```bash
pip install praw tweepy pandas

