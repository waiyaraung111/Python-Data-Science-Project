# Analyzing Historical Stock/Revenue Data and Building a Dashboard

This project aims to analyze the historical stock price and quarterly revenue data of two major companies, Tesla and GameStop. Using data scraping, manipulation with Pandas, and visualization with Plotly, the notebook explores trends and insights in the companies' financials.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Data Collection](#data-collection)
4. [Visualization](#visualization)
5. [Usage](#usage)
6. [Technologies Used](#technologies-used)
7. [License](#license)

## Project Overview
The project performs the following tasks:
- **Data Collection**: Scrapes stock price and revenue data for Tesla and GameStop from reliable financial websites.
- **Data Manipulation**: Cleans and structures the data using the Pandas library for analysis.
- **Visualization**: Creates interactive visualizations using Plotly to explore the historical share prices and quarterly revenue trends of Tesla and GameStop.

## Installation

To run this project locally, you need to have the following installed:
- Python 3.x
- Jupyter Notebook
- Pandas
- Plotly
- BeautifulSoup (for web scraping)

### Step-by-Step Installation:
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open the `Final Assignment.ipynb` notebook in the Jupyter interface.

## Data Collection
The stock and revenue data for Tesla and GameStop were collected through web scraping. The scraping mechanism uses BeautifulSoup to extract relevant tables from financial websites, and the data is then cleaned and formatted for analysis.

### Data Sources:
- Tesla and GameStop historical stock prices
- Tesla and GameStop quarterly revenue

The data is automatically fetched in the notebook as part of the execution.

## Visualization
This project uses Plotly for data visualization. The following plots are included:
- **Historical Share Price Graph**: A line chart showing the trend of stock prices over time for each company.
- **Quarterly Revenue Graph**: A line chart displaying quarterly revenue trends.

These graphs are interactive, allowing zooming, panning, and hovering over points for specific data.

## Usage
To use the notebook:
1. Run all cells in the `Final Assignment.ipynb`.
2. Observe the output visualizations for insights on Tesla and GameStop's stock and revenue performance.
3. Modify the notebook to fetch and analyze data for other companies as needed.

## Technologies Used
- **Jupyter Notebook**: For running Python code interactively.
- **Pandas**: For data manipulation and cleaning.
- **Plotly**: For interactive visualizations.
- **BeautifulSoup**: For web scraping financial data.




