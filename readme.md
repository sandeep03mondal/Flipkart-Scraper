# Flipkart Scraper

A web scraping project that collects and processes product data from Flipkart using Python and Selenium. The scraped data includes product names, prices, ratings, and reviews, enabling efficient analysis of current market trends.

---

## Features

- Automatically collects detailed product information from Flipkart.
- Extracts essential product details, including:
  - Product names
  - Prices
  - Ratings
  - Reviews
- Exports scraped data to a CSV file for easy data analysis.
- Web interface using Flask to trigger scraping and view results.

---

## Tech Stack

- **Language:** Python
- **Web Scraping:** Selenium
- **Data Management:** Pandas
- **Web Application:** Flask

---

## Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/sandeep03mondal/FSDS-Pro-Assignments/tree/main/9%29%20Flask%20Project/FlipKart%20Scraper
```
### Step 2: Navigate to the project directory
```bash
cd FlipKart-Scraper
```

### Step 5: Install dependencies

```bash
pip install -r requirements.txt
```
## Usage
### Step 1: Start the Flask web application
```bash
python app.py
```
### Step 2: Open the web interface in your browser
```
Visit http://127.0.0.1:5000.
```
### Step 3: Use the web interface
```
Input the desired Flipkart search term.
Trigger the scraper to collect product data.
View and export the scraped data.
```

## Project Structure
```
FlipKart-Scraper/
│
├── app.py                  # Main Flask application
├── scraper.py              # Web scraping logic
├── templates/              # HTML templates for the web interface
│   ├── index.html
│   └── results.html
├── requirements.txt        # List of project dependencies
└── README.md               # Project documentation
```

## Modules Used

- **Selenium**:
```For web automation and scraping.```

- **Webdriver Manager**:
```Automatically manages Chrome drivers for Selenium.```

- **Pandas**:
```For data manipulation and CSV export.```

- **Flask**:
```Web framework for building the project’s web interface.```


## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements
- Thanks to the Flipkart team for their amazing website.
- Special thanks to all contributors.

