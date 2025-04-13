# Enhancing Rental Market Insights for Irish Property Platforms

This project analyzes the Irish rental market using web-scraped data to uncover insights into rental trends, market segmentation, and demographic factors. It combines rental listings from Daft.ie, population data from Wikipedia, and income data from CSO.ie to provide data-driven solutions for rental platforms.

## Data Sources

- **Rental Listings**: 1,900 property cards scraped from [Daft.ie](https://www.daft.ie/property-for-rent/ireland?sort=priceAsc)
- **Population Data**: County population tables scraped from [Wikipedia](https://en.wikipedia.org/wiki/List_of_Irish_counties_by_population)
- **Income Data**: Average income data across counties scraped from [CSO.ie](https://www.cso.ie/en/releasesandpublications/ep/p-dea/distributionofearningsbygenderandcounty2022/distributionofearningsbycounty/)

## Key Features

- Web scraping of rental listings, population data, and income data
- 30+ interactive visualizations created to:
  - Analyze dataset structure
  - Display clustering results
  - Visualize outputs from predictive classification and logistic regression models

## Technologies Used

- Python
- Web scraping: BeautifulSoup, Requests
- Data visualization: Plotly
- Machine learning: Scikit-learn (Clustering, Classification, Regression)

## Setup and Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/project-name.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the script:

```bash
jupyter nbconvert --to notebook --execute irish-rental-analytics.ipynb
```

## Usage

Once the script is executed, the interactive visualizations will be available for analysis. You can explore trends in rental prices, market segmentation, and how demographics influence rental listings.
