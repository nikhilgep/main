# main
pulls api fred
# FRED API Observations App

A simple Python Flask app to fetch time-series data from the St. Louis Fed (FRED) API.

## Features

- Fetch observations for any FRED series ID
- Filter by observation start/end dates (optional)

## Usage

### 1. Deploy

- Click "New Web Service" on [Render](https://render.com/) and connect this repo.
- Set the environment variable `FRED_API_KEY` with your [FRED API key](https://fred.stlouisfed.org/docs/api/api_key.html).

### 2. Endpoints

- **GET /**  
  Health check/homepage.

- **GET /observations?series_id=SERIES_ID&observation_start=YYYY-MM-DD&observation_end=YYYY-MM-DD**  
  Example:  
  `/observations?series_id=GDP&observation_start=2020-01-01&observation_end=2021-01-01`

### 3. Local Development
