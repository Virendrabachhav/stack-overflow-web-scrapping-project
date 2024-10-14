# Stack Overflow Web Scraping

This project demonstrates web scraping using Python to extract a specific question and its answers from Stack Overflow. The target question is:

> **"How do I get the current time in Python?"**

You can view the original webpage [here](https://stackoverflow.com/questions/415511/how-do-i-get-the-current-time-in-python).

## Features

The project includes several key features to streamline the web scraping process:

- **Web Scraping with Requests:** Fetch HTML content from a URL.
- **BeautifulSoup for Parsing:** Parse the HTML content and extract specific data such as the question title and its answers.
- **Pythonic Implementation:** Simple and clean Python code to retrieve and display the required information.

These features make the scraping process efficient and easy to follow for anyone who wants to extract web data using Python.

## Getting Started

Follow these steps to set up and run the project on your local machine.

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Pip (Python package manager)

### Installation

#### Clone the Repository

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Virendrabachhav/web-scrapping.git
   ```
2. Navigate to the project directory:

    ```bash
   cd web-scrapping
     ```
3. Install the required libraries:
   ```bash
   pip install requests beautifulsoup4
   ```
Now, you’re ready to run the project!

## Usage

Running the Jupyter Notebook
To run the project in Jupyter Notebook, use the following steps:

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook web-scraping.ipynb
   ```
2. Run each cell step by step to execute the web scrraping process.

## How It Works

1. Fetching HTML Content: The HTML content of the webpage is fetched using the `requests` library.
2. Parsing HTML: The HTML content is parsed with BeautifulSoup.
3. Extracting Data: The question title and the answers are extracted and printed.

## Sample Output
```python
Question Title: How do I get the current time in Python?

Answer 1:
Use the `time` module:
import time
print(time.strftime("%H:%M:%S"))

Answer 2:
Or use the `datetime` module:
from datetime import datetime
now = datetime.now()
print(now.strftime("%H:%M:%S"))
```

## Author

**Virendra Bachhhav** – [GitHub Profile](https://github.com/Virendrabachhav)

## License

This project is licensed under the MIT License.

## Acknowledgments

- Stack Overflow for providing a platform for programming questions and answers.
- BeautifulSoup for its powerful HTML parsing capabilities.
