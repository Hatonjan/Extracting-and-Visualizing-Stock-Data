# Extracting and Visualizing Stock Data

## Description
This project demonstrates how to extract essential financial data from public datasets, clean and transform the data, and visualize it using interactive graphs. By combining data from Yahoo Finance and other sources, I create dual visualizations for historical share prices and revenues of selected companies.

## Features
- **Stock Price Data**: Downloaded directly from Yahoo Finance using the `yfinance` library.
- **Revenue Data**: Scraped and cleaned from web sources with `requests` and `BeautifulSoup`.
- **Interactive Graphs**: Visualized using Plotly's interactive tools, showcasing historical trends.

## Requirements
Before running the project, ensure you have the following Python libraries installed:
- `requests`
- `pandas`
- `yfinance`
- `beautifulsoup4`
- `plotly`

You can install the required libraries using pip:
```bash
pip install requests pandas yfinance beautifulsoup4 plotly
```

## Files in the Repository
- **`app.py`**: The main script containing all the logic for data extraction, cleaning, and visualization.
- **`requirements.txt`**: A file listing all required Python libraries for easy installation.
- **Sample Data Sources**:
  - Yahoo Finance stock data (Tesla & GameStop).
  - Revenue data (scraped from example URLs provided).

## How to Run
1. Clone this repository to your local environment:
   ```bash
   git clone https://github.com/Hatonjan/Extracting-and-Visualizing-Stock-Data.git
   ```
2. Navigate to the project directory:
   ```bash
   cd repository-name
   ```
3. Run the main script:
   ```bash
   python app.py
   ```
4. The visualizations for Tesla and GameStop stock data will appear in your default web browser.

## Examples
### Tesla Visualization
- **Share Price**: Interactive line graph showing Tesla's historical stock prices.
- **Revenue**: Historical revenue trends in millions of USD.

### GameStop Visualization
- **Share Price**: Interactive line graph showing GameStop's historical stock prices.
- **Revenue**: Historical revenue trends in millions of USD.

## Project Highlights
- **Modular Design**: The `make_graph` function can be reused for different datasets.
- **Data Cleaning**: Handles messy revenue data by removing currency symbols and missing values.

## Contributing
Contributions are welcome! Feel free to fork the repository and make a pull request.

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
