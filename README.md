# Using a REST API Service - Python

This Python script demonstrates how to use a REST API service to interact with movie data. It makes HTTP requests to the API endpoints and performs various operations such as retrieving movie details, searching for movies, and extracting data for analysis.

## Prerequisites

Before running the script, make sure you have the following:

- Python (version 3.x) installed on your machine.
- Required libraries: requests, pprint, pandas, requests_html.
- API keys: Replace `<your v3 key>` and `<your v4 key>` in the script with your own API keys.

## Installation

1. Clone this repository or download the script file (`connect.py`) to your local machine.

2. Install the required libraries by running the following command:

   ```
   pip install requests pprint pandas requests_html
   ```

3. Replace `<your v3 key>` and `<your v4 key>` with your actual API keys. You can obtain these keys by signing up for the API service.

4. Save the changes in the script.

## Usage

1. Open a terminal or command prompt and navigate to the directory where the `connect.py` script is located.

2. Run the script using the command:

   ```
   python connect.py
   ```

   The script will perform the following tasks:

   - Make HTTP requests to retrieve movie data from the provided API endpoints.
   - Extract and print the movie details from the responses.
   - Save the extracted movie data to a CSV file named `movies.csv`.

3. After the script finishes executing, you can find the `movies.csv` file in the same directory.

## Note

- The script demonstrates two different API versions (v3 and v4) for illustration purposes. You can choose the appropriate version based on your API provider's documentation.

- Modify the script as needed to interact with other API endpoints or perform additional operations.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and use the code according to the terms of the license.

## Disclaimer

Please use this script responsibly and in compliance with the API provider's terms of service.
