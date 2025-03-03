# Alibaba Web Scraping Using Python

## **Project Overview**

This project demonstrates how to scrape product data from a specific Alibaba product page using Python. It uses the `requests` library to fetch the web page, `BeautifulSoup` from `bs4` to parse and extract information, and `pandas` to organize the data into a structured format and save it to a CSV file.

The project is focused on extracting the following data:
- Product title
- Price
- Quantity
- Timestamp of when the data was collected

The data is then saved to a CSV file for further analysis or processing.

---

## **Data Source**

The data is scraped from the following Alibaba product page:

[https://www.alibaba.com/product-detail/MereSports-Men-s-100-Merino-Wool_1601352569953.html?spm=a2700.galleryofferlist.p_offer.d_image.f0d313a0eX1fnF&s=p](https://www.alibaba.com/product-detail/MereSports-Men-s-100-Merino-Wool_1601352569953.html?spm=a2700.galleryofferlist.p_offer.d_image.f0d313a0eX1fnF&s=p)

---

## **Technologies Used**

- **Python 3.x**
- **BeautifulSoup**: A Python library for parsing HTML and XML documents.
- **requests**: A simple HTTP library for making web requests.
- **pandas**: A data manipulation library for working with structured data (e.g., DataFrames).

---

## **Installation**

1. **Clone the repository** (if applicable):
   ```bash
   git clone <repository_url>
   ```

2. **Install the required libraries**:
   To install the dependencies, you can use `pip`. Run the following command in your terminal or command prompt:
   ```bash
   pip install requests beautifulsoup4 pandas
   ```

---

## **Contributing**

Feel free to fork this repository and submit pull requests if you have suggestions for improvements.

---
