# **Instant Data Cleaner**

### _A simple, fast, code-free tool for cleaning messy datasets._

Instant Data Cleaner is a lightweight Streamlit application that helps you clean and prepare datasets without writing code.\
It focuses entirely on **practical, essential data-cleaning steps** --- the things everyone needs before analysis, visualization, modeling, or sharing data.

This project began as a broader "all-in-one dashboard," but is now intentionally scoped down to a dedicated, easy-to-use **cleaning tool**. A redesigned UI and more refined workflow are planned for future versions.

---

## 🚀 **Current Status --- Version 1**

V1 includes all the fundamental cleaning features needed to tidy most datasets.\
It's stable, functional, and meant to be a solid foundation before the larger V2 redesign.

---

# ✨ **Features (V1)**

## 📥 **Input & Exploration**

- Upload CSV or Excel files _(JSON planned for V2)_

- Preview raw data with pagination

- View dataset structure (columns, data types, row counts)

---

## 🧽 **Data Cleaning Tools**

### **Column Operations**

- Rename columns

- Remove columns

- Reorder columns

### **Row Operations**

- Remove rows by index

- Filter rows using conditions

- Drop duplicate rows

### **Missing Values**

- Drop rows/columns with missing data

- Fill missing values with:

  - Mean

  - Median

  - Mode

  - Forward fill

  - Backward fill

  - Custom values

### **Data Types & Values**

- Change data types

- Convert strings to datetime (when already formatted as such)

- Edit or replace specific cells (via interactive editor)

### **Create Columns**

- Add new columns with a constant value\
  _(More options planned for V2)_

---

## 📤 **Export**

- Download the cleaned dataset in your chosen format (Only CSV for now)

---

# 🛣️ **Roadmap**

Instant Data Cleaner will stay focused on **cleaning**, but the workflow, interface, and tools will continue to expand.

Planned improvements:

### **V1 → V2 Goals**

- Fully redesigned UI

- Cleaner step-by-step workflow

- Improved sidebar navigation

- More column creation tools

- Additional date/time utilities

- Better error handling & highlighting

- Performance improvements for large files

Again --- this project is intentionally _not_ adding visualization or modeling features.\
The mission is to stay focused and great at one thing: **cleaning data**.

---

# 🤝 **Contributing**

This is a personal project, but suggestions and feedback are always welcome.

---

# 📄 **License**

This project is licensed under the MIT License. See the LICENSE file for details.

---

<div align="center"> <h2>🚀 Moonshot Hackathon</h2> <a href="https://moonshot.hackclub.com" target="_blank"> <img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/35ad2be8c916670f3e1ac63c1df04d76a4b337d1_moonshot.png" alt="This project is part of Moonshot --- a 4-day hackathon in Florida visiting Kennedy Space Center and Universal Studios!" style="width: 100%; max-width: 450px;"> </a> <p>Built as part of Hack Club's Moonshot program.</p> </div>
