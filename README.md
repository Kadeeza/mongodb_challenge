# 🍽️ NoSQL Database Analysis with MongoDB

![Python](https://img.shields.io/badge/Tool-Python-blue) ![MongoDB](https://img.shields.io/badge/Tool-MongoDB-green) ![PyMongo](https://img.shields.io/badge/Tool-PyMongo-green) ![NoSQL](https://img.shields.io/badge/Skill-NoSQL-orange) ![Data Analysis](https://img.shields.io/badge/Skill-Data%20Analysis-green)

## 📌 Project Summary

This project uses MongoDB and Python (PyMongo) to set up, update, and query a NoSQL database — demonstrating the ability to work with unstructured and semi-structured data outside of traditional relational databases.

The two-part workflow covers database setup and data ingestion, followed by exploratory analysis using MongoDB queries to surface actionable insights.

---

## 🎯 Business Objective

Not all data fits neatly into tables. NoSQL databases like MongoDB are widely used in industries that handle flexible, document-based data at scale. This project demonstrates how to:

- Import and structure data in a MongoDB collection
- Update and modify documents programmatically
- Query a NoSQL database to answer analytical questions

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Scripting and data manipulation |
| MongoDB | NoSQL document database |
| PyMongo | Python driver for MongoDB |
| Pandas | Presenting query results as DataFrames |
| Jupyter Notebook | Step-by-step analysis |

---

## 📊 Project Workflow

### Part 1 — Database Setup (`NoSQL_setup_starter.ipynb`)
- Imported dataset into a MongoDB database
- Confirmed successful data load using PyMongo queries
- Added new documents to the collection
- Updated existing records with new field values
- Removed unwanted records from the collection
- Converted data types to appropriate formats for analysis

### Part 2 — Exploratory Analysis (`NoSQL_analysis_starter.ipynb`)
- Queried the database to answer specific business questions
- Used `.count_documents()` to measure dataset size and filter results
- Sorted results to find top and bottom performers
- Converted query results to Pandas DataFrames for clean display

---

## 💼 Business Value Delivered

This project demonstrates the ability to:

✅ Set up and populate a MongoDB database from raw data files  
✅ Perform CRUD operations (Create, Read, Update, Delete) programmatically  
✅ Write targeted NoSQL queries to answer business questions  
✅ Integrate MongoDB results with Pandas for reporting  

---

## 📁 Repository Structure

```
mongodb_challenge/
│── NoSQL_setup_starter.ipynb      # Database setup and data ingestion
│── NoSQL_analysis_starter.ipynb   # Exploratory queries and analysis
│── Resources/                     # Source data files
│── README.md
```
