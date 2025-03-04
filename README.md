# **Alibaba Web Scraping Using Python**

## **Project Overview**

This project demonstrates how to scrape product data from **Alibaba** using Python. It utilizes the `requests` library to fetch web pages, `BeautifulSoup` from `bs4` to parse and extract information, and `pandas` to organize the data into a structured format before saving it to a CSV file.

The project is divided into two parts:

### **Part One: Scraping a Specific Product Page**
This part focuses on extracting data from a single Alibaba product page. The extracted data includes:
- **Product Title**
- **Price**
- **Quantity**
- **Timestamp of Data Collection**

The data is saved into a CSV file: [`alibaba_data_scraped_part1.csv`](https://github.com/ayaelsaoudi1/Alibaba-Web-Scraping-Using-Python/blob/main/alibaba_data_scraped_part1.csv).

#### **Data Source for Part One**
[Alibaba Product Page](https://www.alibaba.com/product-detail/MereSports-Men-s-100-Merino-Wool_1601352569953.html?spm=a2700.galleryofferlist.p_offer.d_image.f0d313a0eX1fnF&s=p)

---

### **Part Two: Scraping Multiple Product Listings**
In this part, the script is enhanced to scrape multiple pages from Alibaba’s product listing. It automates the extraction of:
- **Product Names**
- **Prices**
- **Minimum Order Quantities (MOQ)**

The script loops through multiple pages and collects this data, which is then stored in [`alibaba_data_scraped_part2.csv`](https://github.com/ayaelsaoudi1/Alibaba-Web-Scraping-Using-Python/blob/main/alibaba_data_scraped_part2.csv).

---

## **Installation & Setup**

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <https://github.com/ayaelsaoudi1/Alibaba-Web-Scraping-Using-Python.git>
   cd Alibaba-Web-Scraping-Using-Python
   ```

2. **Install dependencies**:
   Run the following command to install the required Python libraries:
   ```bash
   pip install requests beautifulsoup4 pandas
   ```
---

## **Contributing**
If you have suggestions or improvements, feel free to **fork** this repository and submit a **pull request**.


