# Wikipedia Web Scraper

This project provides a Python-based web scraping tool designed to extract and organize sections from Wikipedia pages into structured data. The tool parses headings, paragraphs, and bullet points, aligning sections into a coherent format suitable for analysis, data processing, and further research.

---

## Project Overview

Wikipedia is a valuable source of information, but extracting and organizing its content for analysis can be challenging. This web scraping tool addresses this problem by:

- Extracting Wikipedia sections including headings, paragraphs, and bullet points
- Aligning extracted sections into a structured format
- Outputting data in a structured form that can be further processed or analyzed

The tool is built with Python and uses the BeautifulSoup and requests libraries for web scraping.

---

## Key Features

- Scrapes headings, paragraphs, and bullet points from Wikipedia pages
- Organizes extracted content into structured data for easy manipulation
- Cleans and aligns sections to maintain coherence and order
- Generates a structured DataFrame for analysis and export

---

## Prerequisites

To run this project, ensure that you have the following installed on your system:

- Python 3.x
- Jupyter Notebook or any Python environment
- Required Python libraries:
  - pandas
  - BeautifulSoup4
  - requests

You can install the necessary libraries with the following commands:

```bash
pip install pandas beautifulsoup4 requests
```

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/ahmdmohamedd/wikipedia_web_scraper.git
```

2. Navigate to the project folder:

```bash
cd wikipedia_web_scraper
```

3. Open the `web_scraping.ipynb` file in Jupyter Notebook or your preferred Python environment.

---

## How to Use

1. Launch the Jupyter Notebook environment.
2. Open the `web_scraping.ipynb` notebook file.
3. Follow the instructions in the notebook to run the provided code sections step by step.
4. The scraper will extract sections from Wikipedia pages, including headings, paragraphs, and bullet points.
5. The output will be structured data that you can analyze, export, or manipulate according to your requirements.

---

## Project Structure

```
wikipedia_web_scraper/
├── web_scraping.ipynb
├── wikipedia_scraped_data.csv
├── README.md
```

- `web_scraping.ipynb`: Main Jupyter Notebook where the scraping logic is implemented.

---

## Data Extraction and Output

The scraper extracts the following sections from Wikipedia pages:

- **Headings**: Titles of sections and subsections.
- **Paragraphs**: Text sections extracted in order from the content.
- **Bullet Points**: Information formatted as lists or bullet points.

The data is organized into pandas DataFrames for easy access and export.

---

## Troubleshooting

- Ensure that your internet connection is stable, as the scraper relies on network requests.
- If scraping errors occur, check if Wikipedia pages are accessible and correctly formatted.
- Update Python libraries with the following command:

```bash
pip install --upgrade pandas beautifulsoup4 requests
```

---

## Contributing

Contributions are welcome! If you would like to improve or extend this project, feel free to fork the repository, make your changes, and submit a pull request. Ensure that your code adheres to the project structure and includes meaningful comments and documentation.

---
