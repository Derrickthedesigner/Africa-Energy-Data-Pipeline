#  Africa Energy Data Scraper

##  Overview
This project is a modular ETL (Extract–Transform–Load) pipeline designed to collect, clean, validate, and store energy-related data for all African countries from the [Africa Energy Portal](https://africa-energy-portal.org/). It supports both local CSV exports and MongoDB integration for scalable analysis.

---

##  Project Goal
**Main Objective:**  
Extract energy indicators for all African countries (2000–2024) and store them in a structured MongoDB collection.

**Target Source:**  
 [Africa Energy Portal](https://africa-energy-portal.org/)

---

##  Key Features
- ✅ Scrapes energy metrics (access, generation, renewables, etc.) across 55 African countries  
- ✅ Covers 25 years of data (2000–2024)  
- ✅ Transforms nested JSON into wide-format tabular structure  
- ✅ Validates completeness across years and metrics  
- ✅ Exports to timestamped CSV files  
- ✅ Uploads structured records to MongoDB  
- ✅ Built in a Jupyter Notebook for transparency and reproducibility  

---
## Workflow Breakdown

### 1.  Setup
Install required packages:
```bash
pip install pandas pymongo cloudscraper python-dotenv tqdm

