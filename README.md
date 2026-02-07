# web-scraping-pipeline-restaurant-reviews
This repository contains a Python-based web scraping pipeline for collecting restaurant reviews from RestaurantGuru.  The project scrapes restaurant links for a given city, extracts customer reviews for each restaurant, and merges all scraped data into a single dataset for further analysis.


## Project Structure

├── scrape_restaurant_links_restaurantguru.ipynb
├── scrape_restaurant_reviews_restaurantguru.ipynb
├── merge_restaurant_reviews.ipynb
├── archive/
│ └── archive_scrape_restaurant_reviews_restaurantguru.ipynb
└── README.md

---

## Workflow

1. **Scrape restaurant links**
   - Extracts all restaurant URLs for a selected city from RestaurantGuru.

2. **Scrape restaurant reviews**
   - Iterates over all restaurant links.
   - Collects review titles and texts.
   - Saves the data as multiple CSV files.

3. **Merge review files**
   - Combines all individual CSV files into one consolidated dataset.

---

## Requirements

- Python 3.x
- Selenium
- pandas
- Chrome browser
- Chrome WebDriver

Make sure the Chrome WebDriver version matches your installed Chrome browser.

---

## Configuration

- Set the city name directly in the notebooks.
- Update local file paths (e.g. WebDriver path, output folders) as needed.
- Adjust waiting times if scraping large datasets.

---

## Notes

- The `archive` folder contains older or experimental versions of the scraping scripts.
- This project is intended for **research and educational purposes**.
- Please respect the terms of service of RestaurantGuru when using this code.

---

## Author

Developed by *Eliane Tuchborn*
