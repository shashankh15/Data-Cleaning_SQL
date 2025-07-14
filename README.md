# Data-Cleaning_SQL
# 🧹 Data Cleaning in MySQL — Layoffs Data Project

This is a complete data cleaning project I worked on using MySQL. The dataset contains information on layoffs in the tech industry, and the goal was to clean and prepare the data for deeper analysis. The project is inspired by Alex The Analyst’s tutorial, but I’ve added my own structure and touches throughout the process.

## 📁 Dataset

The dataset used for this project contains the following columns:

- `company`
- `location`
- `industry`
- `total_laid_off`
- `percentage_laid_off`
- `date`
- `stage`
- `country`
- `funds_raised_millions`

The raw CSV file was imported into MySQL, and from there, cleaning was done through SQL queries.

## 🛠️ Tools Used

- **MySQL Workbench**  
- **SQL** (for all cleaning tasks)

## 🧽 Cleaning Steps Performed

Here’s a summary of the steps I took during this project:

- Removed duplicates
- Handled `NULL` and missing values
- Standardized date formats
- Fixed inconsistent formatting (e.g., capitalization, whitespace)
- Checked for and corrected anomalies (e.g., invalid percentages)
- Created new cleaned columns for better readability and use

> All transformations were done **within MySQL** using SQL queries — no external tools or scripts.

## 📂 Files in This Repo

- `layoffs_raw.csv` — The original raw dataset
- `data_cleaning.sql` — SQL script containing all queries used to clean the data
- `README.md` — You're reading it :)

## 📊 What I Learned

Working through this project helped me understand:

- The importance of clean data before any sort of analysis
- How to structure SQL queries logically when dealing with real-world messiness
- How to document and structure a project end-to-end


---
## 📬 Contact

- 📧 Email: hosmanishashank1517@gmail.com
- 💼 LinkedIn: www.linkedin.com/in/shashank-hosmani-7b31a6317

---
Feel free to fork, clone, or suggest improvements!

