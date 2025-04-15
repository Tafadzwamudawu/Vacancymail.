﻿# Vacancymail.
# Job Scraper - VacancyMail Zimbabwe

## Description
A Python script that scrapes the 10 most recent jobs from [https://vacancymail.co.zw/jobs/](https://vacancymail.co.zw/jobs/) and saves the data in scraped_data.csv.

## Features
- Extracts job title, company, location, expiry date, and description
- Saves data in structured CSV format
- Cleans and formats data
- Error handling and logging
- Optional daily scheduling using schedule

## Setup

### Prerequisites
- Python 3.7+
- Install dependencies:

```bash
pip install requests beautifulsoup4 pandas schedule
