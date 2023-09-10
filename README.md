# Stock Data Visualizer

The Stock Data Visualizer is a tool designed to present real-time stock data in a visually engaging manner. By connecting to a real-time stock data API, the application retrieves and displays stock information in interactive charts, providing insights into stock performance.

## Features

- **Real-time Stock Data**: Access up-to-date stock data for a variety of time frames.
- **Interactive Charts**: Select between bar and line charts to visualize stock trends.
- **Date Range Selection**: Customize the view by selecting specific start and end dates.
- **S&P 500 Symbols**: Integration with a curated list of S&P 500 symbols for quick selection.

## Technologies Used

- Programming Language: Python
- Web Framework: Flask
- Visualization Library: Pygal
- Containerization: Docker

## Installation

1. **Clone the Repository**: `git clone <repository_url>`
2. **Navigate to Directory**: `cd stock-visualizer`
3. **Build the Docker Container**: `docker build -t stock-visualizer .`
4. **Run the Container**: `docker run -p 6001:6003 stock-visualizer`
5. **Access the App**: Open `http://localhost:6001` in your browser.

## Usage

- **Choose a Symbol**: Select a stock symbol from the list of S&P 500 symbols.
- **Select Chart Type**: Choose between a bar or line chart to visualize the data.
- **Select Time Series**: Choose the desired time series function (e.g., daily, weekly, monthly).
- **Set Date Range**: Select the desired date range to view specific data.
- **View Chart**: Click on the "Submit" button to render the chart.

## Contributing

If you're interested in contributing to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

This project was built using Alpha Vantage API. Special thanks to everyone in my group, who supported the development and made this project possible. Thank you to Professor Kristofferson Culmer for his guidance, support, and encouragement.
