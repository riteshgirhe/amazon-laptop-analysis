# Amazon Laptop Analysis

A Python data analysis project that scrapes laptop listings from Amazon.in, cleans the collected data, and analyzes pricing, brand, RAM, storage, processor, color, and rating trends using Pandas, Matplotlib, and Seaborn.

## Project Workflow

**Web Scraping → Data Cleaning → Exploratory Data Analysis → Data Visualization**

## Files

| File                        | Description                                  |
| --------------------------- | -------------------------------------------- |
| `Amazon_scrap_laptop.ipynb` | Scrapes laptop listings from Amazon.in       |
| `amazon_laptop_scrap.csv`   | Raw scraped dataset                          |
| `Amazon_Charts.ipynb`       | Exploratory data analysis and visualizations |
| `Clean_Dataset_Amazon.csv`  | Cleaned dataset used for analysis            |

## Analysis

The project explores:

* Laptop prices by brand
* Average price by brand
* Average rating by brand
* RAM and price relationships
* Price distribution
* Rating distribution
* Number of products by brand
* SSD/storage analysis
* Price vs. rating
* Processor distribution
* Laptop color distribution

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Requests
* BeautifulSoup4
* Jupyter Notebook

## Installation

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn requests beautifulsoup4
```

## Usage

### 1. Scrape the data

Open and run:

```text
Amazon_scrap_laptop.ipynb
```

This collects laptop listings from Amazon.in and saves the raw data to:

```text
amazon_laptop_scrap.csv
```

> Amazon may change its page structure over time, so the scraping code may require updates.

### 2. Analyze and visualize the data

Open and run:

```text
Amazon_Charts.ipynb
```

The notebook uses:

```text
Clean_Dataset_Amazon.csv
```

to perform exploratory data analysis and generate visualizations.

## Project Structure

```text
Amazon-Laptop-Analysis/
│
├── Amazon_scrap_laptop.ipynb
├── amazon_laptop_scrap.csv
├── Amazon_Charts.ipynb
├── Clean_Dataset_Amazon.csv
└── README.md
```

## License

This project is licensed under the MIT License.
