# Office Contacts Scraper 

This folder contains an anonymized example of an end-to-end scraping and data-cleaning workflow.  
All domain names, company details, and sensitive project information have been removed for confidentiality.  
The purpose of this example is to demonstrate the structure and logic used in real data-collection projects.

## Overview

This project automates the extraction and cleaning of office contact information from directory-style member pages.  
It includes both the scraping workflow and the data-processing pipeline used to prepare a clean mailing dataset.

Key components:
- Automated page fetching with **Selenium**
- Structured HTML parsing using **BeautifulSoup**
- Wide → long data transformation
- Duplicate removal and field standardization
- Email validation and cleanup
- Export of a ready-to-use dataset

## Notebook Files

### **1. `office_contacts_all.ipynb`**
This notebook demonstrates a fully anonymized scraping workflow, including:

- WebDriver setup  
- Access validation (login required / restricted / OK)  
- Extraction of multiple contact blocks per company  
- Incremental CSV writing (wide format)  
- Logging system for resumable scraping  

---

### **2. `clean_contacts_for_mailing.ipynb`**
This notebook performs data cleaning and prepares the dataset for outreach or analysis:

- Removing empty or duplicate rows  
- Normalizing field values  
- Extracting contact names & emails from wide columns  
- Converting to long format  
- Email validation rules  
- Exporting `clean_mailing_list.csv`

## Purpose

This anonymized example reflects my experience with:

- Web scraping and automation  
- Data extraction and transformation  
- Building robust and resumable scraping workflows  
- Cleaning real-world datasets for practical use  

It demonstrates end-to-end data engineering logic without revealing any confidential project details.

## Notes

- All URLs, HTML structures, and company names have been replaced with placeholders.  
- The logic reflects real project work but is safe for public sharing.  
- This folder is part of my **data-collection-and-scraping** learning portfolio.