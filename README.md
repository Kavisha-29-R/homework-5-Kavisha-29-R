# HW5 – Interactive Visualization & Web Hosting

This repository contains my submission for **Homework 5**.  
The assignment involves web scraping GDP data, creating interactive visualizations with Plotly, and hosting a Sankey diagram on GitHub Pages.

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `hw5.ipynb` | Jupyter notebook containing all code for Parts 1 and 2. It has been run cleanly using **Restart & Run All** so that all outputs are displayed. |
| `stacked_bar.html` | Interactive stacked bar plot of GDP by country (grouped by IMF regions), exported from Plotly. |
| `sankey.html` | Sankey diagram visualizing MRICloud data (Type = 1, starting from intracranial volume), exported from Plotly. |

---

## 📝 Assignment Overview

### 1. GDP by Country – Stacked Bar Plot  
- Webscrape [Wikipedia – GDP (Nominal)](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)) using Python.  
- Group countries within IMF regions.  
- Generate a **stacked interactive bar plot** using Plotly.  
- Save the plot to an HTML file: `stacked_bar.html`.  

### 2. MRICloud Data – Sankey Diagram  
- Based on the chapter on interactive graphics from [ds4bio book](https://smart-stats.github.io/ds4bio_book/book/_build/html/interactive.html).  
- Display subject MRICloud data as a **Sankey diagram** (minimum 3 levels for Type = 1, starting from intracranial volume).  
- Save the plot to an HTML file: `sankey.html`.  

### 3. Host the Sankey Diagram on GitHub Pages  
- Created a **public repository** on my personal GitHub account (not the classroom repo). [Sankey-Repo](https://github.com/Kavisha-29-R/hw5-Sankey-Plot.git) 
- Added the Sankey HTML file to that repo.  
- Hosted it via **GitHub Pages**.  

---

## 🌐 Live Sankey Diagram  

You can view the publicly hosted Sankey diagram here:  
[**Click here to view the Sankey Diagram**](https://kavisha-29-r.github.io/hw5-Sankey-Plot/sankey.html)

---

## ⚙️ Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/[YOUR USERNAME]/homework-5-Kavisha-29-R.git
   cd homework-5-Kavisha-29-R
