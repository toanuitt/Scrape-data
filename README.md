# Data Scraper

## Overview

The Data Scraper project is designed to fetch and extract data from various web sources. The extracted data can be stored in different formats such as CSV, JSON, or directly into databases for further analysis and usage.

## Features

- Scrape data from websites
- Parse HTML content using BeautifulSoup
- Store extracted data in CSV or JSON format
- Configurable settings for different websites
- Error handling and logging
## Requirements

- Python 3.7+
- requests
- BeautifulSoup4
- pandas
- selenium

## Source
This repository provides data crawled from web:

- **Great School**: https://www.greatschools.org/
- **Realtor**: https://www.greatschools.org/
- **USnews**: https://www.usnews.com/
## Structure
```bash
├── Great School
│   ├── GreatSchool.ipynb
├── Realtor
│   ├── Realtor.ipynb
├──USNews
│    ├── USNews.ipynb
├──requirements.txt
└──README.md

```

## Installation

To get started with the project, follow these steps:

1. Clone the repository:
    ```bash
    $ git clone https://github.com/toanuitt/Scrape-data.git
    ```

2. Navigate to the project directory:
    ```bash
    $ cd Scrape-data
    ```

3. Install the required packages:
    ```bash
    $ pip install -r requirements.txt
    ```



## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License.



