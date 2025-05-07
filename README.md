This project provides a series of data extractions and visualizations for Tesla and GameStop stock data and their respective quarterly revenues. The goal of this project is to extract and analyze stock price and revenue data over time, and visualize it in an interactive dashboard.

Project Breakdown:
Question 1 - Extracting Tesla Stock Data Using yfinance
Extract historical stock data for Tesla using the yfinance library. The stock data includes information on opening price, closing price, high/low prices, and volume.

Question 2 - Extracting Tesla Revenue Data Using Webscraping
Scrape quarterly Tesla revenue data from macrotrends.net using BeautifulSoup and requests.

Question 3 - Extracting GameStop Stock Data Using yfinance
Similar to Tesla, we use yfinance to extract historical stock data for GameStop (GME).

Question 4 - Extracting GameStop Revenue Data Using Webscraping
Scrape quarterly GameStop revenue data from macrotrends.net using BeautifulSoup and requests.

Question 5 - Tesla Stock and Revenue Dashboard
Create an interactive dashboard that displays Tesla's stock price and revenue over time using Plotly.

Question 6 - GameStop Stock and Revenue Dashboard
Create a similar interactive dashboard for GameStop showing both stock price and revenue.

Question 7 - Sharing your Assignment Notebook
Upload your complete Jupyter Notebook with the code and visualizations to GitHub, and share the link to your assignment.

Requirements:
To run this project, you'll need the following Python libraries:

yfinance

requests

BeautifulSoup4

pandas

plotly

Steps to Run:
Clone the Repository
Clone this repository to your local machine:

bash
Copy
git clone https://github.com/yourusername/stock-revenue-dashboard.git
Install Dependencies
Create a virtual environment and install the required dependencies:

bash
Copy
pip install -r requirements.txt
Run the Jupyter Notebook
Navigate to the folder where you saved the notebook and run it in your Jupyter Notebook environment:

bash
Copy
jupyter notebook
Visualize the Results
The notebook will guide you through extracting and visualizing stock and revenue data. At the end, you'll see interactive Tesla and GameStop dashboards.

Example Output:
After running the notebook, the following output will be generated:

An interactive line graph displaying Tesla's stock price and revenue.

Another interactive line graph displaying GameStop's stock price and revenue.

Screenshots:
Include screenshots of the final dashboards and graphs here:


Notes:
Ensure the correct date formats for stock and revenue data to align both datasets properly on the plots.

The scraping of revenue data relies on a public source and may need adjustment if the structure of the page changes.

Grading Breakdown:
Question 1: Extract Tesla Stock Data (2 Points)

Question 2: Extract Tesla Revenue Data (1 Point)

Question 3: Extract GameStop Stock Data (2 Points)

Question 4: Extract GameStop Revenue Data (1 Point)

Question 5: Tesla Stock and Revenue Dashboard (2 Points)

Question 6: GameStop Stock and Revenue Dashboard (2 Points)

Question 7: Sharing the Notebook (2 Points)

License:
This project is licensed under the MIT License - see the LICENSE file for details.

How to Share Your Work on GitHub:
Ensure that all your Jupyter notebook files, code, and any required data (if applicable) are added to the repository.

Push the code to GitHub using the following commands:

bash
Copy
git add .
git commit -m "Add final project files"
git push origin main
