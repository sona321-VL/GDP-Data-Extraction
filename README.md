# GDP-Data-Extraction
# GDP Data Extraction and Processing

## 📌 Project Overview

This project demonstrates how to extract and process Gross Domestic Product (GDP) data from a web page using Python and Pandas.

The data was extracted from the archived Wikipedia page containing a list of countries by GDP (nominal), processed from Million USD to Billion USD, rounded to two decimal places, and saved as a CSV file.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Web Scraping
* CSV

## 🔍 Project Steps

1. Extracted GDP data from a web page using Pandas `read_html()`.
2. Selected the required GDP table from the webpage.
3. Converted the GDP column from Million USD to integer values.
4. Converted GDP values from Million USD to Billion USD.
5. Rounded GDP values to two decimal places using NumPy.
6. Renamed the column to `GDP (Billion USD)`.
7. Exported the processed data to `Largest_economies.csv`.

## 📊 Dataset

The final dataset contains GDP information for the world's largest economies.

### Sample Data

| Country       | GDP (Billion USD) |
| ------------- | ----------------: |
| United States |          26854.60 |
| China         |          19373.59 |
| Japan         |           4409.74 |
| Germany       |           4308.85 |
| India         |           3736.88 |

## 📁 Files

* `practice_project.ipynb` — Jupyter Notebook containing the Python code and data-processing steps.
* `Largest_economies.csv` — Processed GDP dataset.
* `README.md` — Project documentation.

## 🎯 Learning Outcomes

Through this project, I practiced:

* Web scraping with Pandas
* Working with HTML tables
* Data cleaning and transformation
* Data type conversion
* Numerical operations using NumPy
* Exporting data to CSV
* Managing and documenting a project using GitHub

## 📚 Project Context

This project was completed as part of a hands-on data extraction and processing exercise on Coursera.

## 👩‍💻 Author

**Sonalia**
