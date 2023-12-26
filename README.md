Description
This project is a Python-based data scraper designed to extract information about U.S. subsidiaries from a specified SEC filing webpage. It uses the requests and BeautifulSoup libraries to fetch and parse HTML content, specifically targeting tables that list subsidiary information under the "Jurisdiction" section. The script is capable of handling multiple tables on a single page and counts the number of branches in each U.S. state.

Setup and Installation:
Prerequisites:
Python 3.x
pip (Python package manager)
Libraries Used:
requests
beautifulsoup4

Clone the repository:
git clone https://github.com/your-username/your-repository-name.git

Install the required Python packages:
pip install requests beautifulsoup4

Usage
To run the script, execute the following command in the terminal:
python path/to/scraper.py

When prompted, enter the URL of the SEC filing page you wish to scrape.

Features
Extracts subsidiary data from SEC filing webpages.
Counts the number of branches in each state in the U.S.
Handles multiple tables on a single page.
Contributing
Contributions to this project are welcome. Please ensure that your code adheres to the project's coding standards and include tests for new features or bug fixes.

License
MIT License - Feel free to use, modify, and distribute this software as per the terms of the license.

Disclaimer
This script is for educational purposes only. Users are responsible for ensuring that their use of the script complies with the terms of service of the scraped website and applicable laws.I am not responsible for any misuse or legal implications arising from the use of this script.
