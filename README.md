# Web Scraping Project – E-Commerce Product Data Extractor

This repository contains a Python-based web scraping tool designed to extract product information (product names, image links, and product URLs) from e-commerce websites. The scraper is implemented in a Jupyter Notebook and outputs data in CSV and Excel formats.  
It is ideal for data analysts, researchers, students, and anyone who needs automated product data collection.

This project scrapes product data from e-commerce sites using Python, BeautifulSoup, and Requests. It extracts product names, images, and URLs across multiple pages and exports clean, structured results to CSV. Useful for automated data collection, analysis, and e-commerce research.

---

## Project Structure & File Details

| File Name | Type | Description |
|-----------|------|-------------|
| **Wescraping.ipynb** | Jupyter Notebook | Main file containing the full web scraping script, loops, extraction logic, and CSV export functionality. |
| **yoshops.csv** | CSV File | Final output file generated after scraping product data from the target website. |
| **Missing_Image_Data.xlsx** | Excel File | Contains records of missing or invalid image URLs (optional helper file). |
| **README.md** | Markdown | Documentation explaining project purpose, setup, usage, and instructions. |

---

## Features

- Scrapes multiple pages automatically  
- Extracts product name, image URL, and product page link  
- Uses headers to avoid bot blocks  
- Saves data to a clean CSV format  
- Simple and beginner-friendly code  
- Based on BeautifulSoup + Requests + Pandas  

---

## Use Cases & Applications

This project can be used for various real-world applications, such as:

- **Competitive price monitoring**  
- **Product catalog building**  
- **Market research**  
- **Academic or training projects**  
- **Image dataset preparation**  
- **Automation of repetitive data collection tasks**  
- **E-commerce analytics**

---

## Requirements & Installation

###  **Clone the Repository**

```bash
git clone https://github.com/riyasoni17/Webscraping-Project.git
cd webscraping-project
