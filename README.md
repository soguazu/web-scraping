# Premier League Results Web Scraper

A simple web scraping project that extracts Premier League match results from Wikipedia.

## Overview

This project scrapes the 2024-25 Premier League results table from Wikipedia and converts it into a structured pandas DataFrame for analysis.

## Features

- Scrapes Premier League results from Wikipedia
- Parses home/away match data with scores
- Converts data to pandas DataFrame format
- Handles team name cleaning and formatting

## Requirements

- Python 3.x
- BeautifulSoup4
- pandas
- requests

## Installation

```bash
pip install beautifulsoup4 pandas requests
```

## Usage

Run the Jupyter notebook `2024–25 Premier League Result.ipynb` to:

1. Fetch the Premier League Wikipedia page
2. Parse the results table
3. Extract match data (home team, away team, score)
4. Display results in a pandas DataFrame

## Data Structure

The scraper extracts the following data for each match:

- **home**: Home team name
- **away**: Away team name
- **score**: Match score (e.g., "2-1")

## Example Output

```
           home                         away score
0  Arsenal F.C.             Aston Villa F.C.   2-2
1  Arsenal F.C.              AFC Bournemouth   1-2
2  Arsenal F.C.               Brentford F.C.   1-1
3  Arsenal F.C.  Brighton & Hove Albion F.C.   1-1
4  Arsenal F.C.                 Chelsea F.C.   1-0
```

## Files

- `2024–25 Premier League Result.ipynb` - Main Jupyter notebook containing the scraping code
