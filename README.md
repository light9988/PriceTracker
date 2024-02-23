# PriceTracker

Price Tracker is a Python-based tool developed in a Jupyter Notebook environment to track prices of specific products from various websites, store historical data, visualize price trends, and provide alerts when prices drop.

### Features

- **Web Scraping**: Utilizes Beautiful Soup to extract prices of specific products from target websites.
- **Data Storage**: Uses CSV files to store historical price data for analysis and visualization.
- **Visualization**: Generates statistical graphics using Seaborn to visualize price trends over time.
- **Price Drop Monitoring**: Implements a price drop monitoring feature, allowing users to receive alerts when prices drop below a certain threshold.

### Setup

1. **Anaconda Installation**: Ensure you have Anaconda installed. If not, download and install Anaconda from [here](https://www.anaconda.com/products/distribution).

2. **Twilio Account Setup**: Sign up for a Twilio account and obtain your account SID, authentication token, and Twilio phone number. You can sign up [here](https://www.twilio.com/try-twilio).

3. **Clone Repository**: Clone the repository.

4. **Open Jupyter Notebook**: Open the Jupyter Notebook by navigating to the directory where the notebook is saved and running the following command in the terminal:
   ```
   jupyter notebook price_tracker_and_comparator.ipynb
   ```

5. **Follow Notebook Instructions**: Follow the instructions provided in the notebook to configure and run the price tracking scripts. Ensure to set up your Twilio credentials and phone number for SMS alerts.

### Usage

1. **Configure Tracking**: Edit the notebook to configure the list of target websites and products to track.

2. **Run Scripts**: Run the web scraper script to extract price data from the target websites. Then, run the data analysis script to generate statistical graphics and visualize price trends.

3. **Set Price Threshold**: Set up the price drop monitoring feature by configuring the desired price threshold for receiving alerts.

4. **Receive Alerts**: Run the monitoring script to receive alerts via SMS when prices drop below the specified threshold.

### Contributing

Contributions are welcome! Please follow the guidelines provided in the notebook and contribute to the project.

### License

This project is licensed under the MIT License. See the `LICENSE` file for details.

### Acknowledgements

Special thanks to the Beautiful Soup and Seaborn teams for their fantastic libraries and tools that make this project possible.

### Contact

For inquiries or support, please contact me.
