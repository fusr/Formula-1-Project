# Capstone Project README

## Overview

This repository contains the code and data for Formula Data Dynamics Capstone Project, which was completed as part of a data analytics bootcamp. The project focuses on analyzing Formula 1 (F1) racing data to explore various hypotheses related to tyre usage, grid positions, and the relationship between constructors' and drivers' championships.

## Data Sources

### CSV Files

The primary dataset used in this project consists of CSV files downloaded from Kaggle. These files contain various data points related to Formula 1 races, drivers, teams, and more.

- [Kaggle F1 Dataset](https://www.kaggle.com/datasets/cjgdev/formula-1-race-data-19502017): This dataset provided essential information about Formula 1 races and served as the foundation for our analysis.

### Weather Data

To enrich the dataset with weather information for each Grand Prix, we scraped data from Wikipedia pages corresponding to each race. We utilized web scraping techniques to collect this data programmatically.

### Tyre Data

Information about tire usage during races was scraped from [www.f1cfa.com](https://www.f1cfa.com/), a reputable source for Formula 1 data. This data helped us investigate tyre strategies in different races.

## Hypotheses

Our analysis focused on testing the following hypotheses:

1. **Hypothesis 1:** On city circuits, softer tires are more often used. We explored whether the track type had an impact on tire choices during races.

2. **Hypothesis 2:** Drivers who start in the top four grid positions (1st to 4th) are more likely to win races. We examined the relationship between starting positions and race outcomes.

3. **Hypothesis 3:** Teams that finish in the top three positions in the constructors' championship are more likely to have their drivers win the drivers' championship the following year. We investigated the correlation between team performance and individual driver success in the following season.

## Project Structure

The project directory is structured as follows:

- `data/`: Contains the CSV files and scraped data used in the analysis.
- `notebooks/`: Includes Jupyter notebooks used for data exploration, analysis, and visualization.
- `README.md`: The file you are currently reading, providing an overview of the project.

## Requirements:

- pyenv with Python: 3.9.4

### Setup

Use the requirements file in this repo to create a new environment.

```BASH
make setup

#or

pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements_dev.txt
```



