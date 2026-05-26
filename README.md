# GDP Analysis Project

## Project Overview

The **GDP Analysis Project** is a **Python-based data analysis application** that processes GDP data of countries and produces meaningful results based on user-defined configuration settings. The project follows a **modular architecture**, separating data loading, processing, and presentation into different Python modules.

### The goal of the project is to:
- Clean and organize GDP data  
- Filter data by region and year  
- Perform GDP calculations (sum or average)  
- Save results in a JSON file  
- Display results through a simple dashboard  

All user choices are controlled via a **config.json file**, ensuring no hardcoded values.

---

## ❗ Problem Statement

Raw GDP data is large, unstructured, and difficult to analyze directly.

This project solves the problem by:
- Cleaning and reshaping GDP data  
- Making analysis configurable  
- Automating GDP calculations  
- Producing clean and reusable outputs  

---

## ⭐ Key Features

- **Config-driven logic (no hardcoding)**  
- **Modular design (Single Responsibility Principle)**  
- **Error handling for invalid inputs**  
- **Clean data preprocessing**  
- **Output saved to JSON**  
- **Dashboard / presentation layer ready for future visualization extensions**  

---

## 📁 Project Structure

```text
project/
│
├── data/
│   ├── gdp_with_continent_filled.csv
│   ├── gdp_data_clean.csv
│   └── output_result.json
│
├── data_loader.py
├── data_processor.py
├── dashboard.py
├── main.py
├── config.json
└── README.md
