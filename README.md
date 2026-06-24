# Kerala University Affiliated Colleges – Web Scraping Project

## Project Overview

This project focuses on extracting affiliated college information from the **University of Kerala – Affiliated Colleges Portal** using web scraping techniques.

Source Website:

https://www.keralauniversity.ac.in/affiliated-colleges


## Objective

To collect and organize college details from the Kerala University affiliated colleges portal and create a structured dataset.

The extracted information includes:

- College Name
- Address
- Contact Number
- Email Address
- Website URL


## Technologies Used

- Python
- Requests
- BeautifulSoup
- Regular Expressions (Regex)
- Pandas
- Matplotlib


## Project Workflow

### 1. Web Page Analysis

- Analyzed the structure of the Kerala University affiliated colleges portal.
- Identified college listing pages and individual college profile pages.
- Extracted required HTML elements.


### 2. Data Extraction

The scraping process:

1. Access the affiliated colleges page.
2. Collect individual college profile links.
3. Visit each college profile page.
4. Extract:

   - College Name
   - Address
   - Contact Number
   - Email Address
   - Website URL


### 3. Data Cleaning

Performed data cleaning operations:

- Removed duplicate records.
- Removed unwanted rows:
  - University of Kerala
  - Affiliated Colleges

- Handled missing values.
- Validated email addresses.
- Checked phone number formats.


## Dataset Information

Final dataset contains:

| Column | Description |
|---|---|
| College Name | Name of affiliated college |
| Address | College contact address |
| Contact Number | Phone number |
| Email Address | Official email |
| Website URL | College website |


## Data Analysis

Performed analysis on:

- Total number of colleges extracted
- Missing email addresses
- Missing website URLs
- Contact information completeness


## Visualizations

Created visualizations for:

1. Colleges with and without websites

2. Colleges with and without email addresses

3. Contact information completeness


## Key Insights

- Most colleges provide website information.
- Some colleges have missing email details.
- Contact information availability differs among colleges.
- Data quality varies between college records.


## Output Files

- `Kerala_University_Affiliated_Colleges.csv`

Raw scraped dataset

- `Kerala_University_Colleges_Cleaned.csv`

Cleaned dataset

- `Kerala_University_Colleges_Final.csv`

Final dataset after removing unwanted records


## How to Run

Install required libraries:

```bash
pip install requests beautifulsoup4 pandas matplotlib
