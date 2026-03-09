# 📊 Week 9: Python for Visualization & Reporting

> **Module:** Python for Data Analysis | **Team:** Data Drifters

---

## 👥 Project Team

| Name | Role |
|------|------|
| 👤 Thato Msina | Team Member |
| 👤 Fikile Noyila | Team Member |
| 👤 Lesedi Mphachake | Team Member |
| 👤 Jereshan Sinan | Team Member |
| 👤 Kaylene Martins | Team Member |

---

## 📖 Project Overview

This project documents our analytical journey into the **WebTraffic Dataset**. Our goal is to transform raw web traffic data into meaningful visual stories and automated reports.

<img width="1484" height="735" alt="34" src="https://github.com/user-attachments/assets/65172277-8448-453b-bb10-efb0bdace876" />

---

## 🛠️ Technology Stack

| Category | Tool / Library |
|----------|---------------|
| Language | Python 3 |
| Data Manipulation | Pandas |
| Visualization | Matplotlib, Seaborn, Plotly |
| Notebook Environment | Jupyter Notebook (Google Colab) |
| Output Formats | HTML, PDF |

---

## 📊 Dataset: WebTraffic.csv

| Column | Description |
|--------|-------------|
| `date` | Date of the recorded traffic |
| `page` | Page visited (e.g. Home, About, Contact) |
| `source` | Traffic source (Direct, Search, Social, Referral) |
| `visits` | Total number of visits |
| `unique_visitors` | Number of unique visitors |
| `bounce_rate` | Proportion of single-page visits (0–1) |

---

## 🚀 Getting Started

### Option 1: Run on Google Colab (Recommended)

Click the badge below to open the notebook directly in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dMcnEvjqIVTCRDHxuYNEO39xOMStxWQE?usp=sharing)

### Option 2: Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/St10245564/Python-for-Visualization-Reporting.git
   cd YOUR_REPO_NAME
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Week9_WebTraffic.ipynb
   ```

---

## 📋 Requirements

Create a `requirements.txt` with the following content:

```
pandas
matplotlib
seaborn
plotly
nbconvert
jupyter
kaleido
```

---

## 📈 Key Analyses Performed

### 1. Traffic Trend Plots
- Daily visits over time
- Page-level traffic comparison
- Source breakdown (Direct vs Search vs Social vs Referral)

### 2. Bounce Rate Analysis
- Average bounce rate per page
- Source vs bounce rate correlation

### 3. Automated Reports
- HTML report generated programmatically using Pandas + Plotly
- PDF export via `nbconvert` or `pdfkit`

---

## 🎯 Learning Objectives

- [x] Understand and apply **Matplotlib**, **Seaborn**, and **Plotly** for data visualization
- [x] Perform **exploratory data analysis** on real-world web traffic data
- [x] Automate **report generation** to PDF and HTML formats
- [x] Present insights in a clear, visual, and reproducible manner

---

## 📌 Submission Checklist

- [ ] Jupyter Notebook with all visualizations
- [ ] Exported HTML report
- [ ] Exported PDF report
- [ ] PowerPoint presentation with embedded plots
- [ ] Excel file with data model, dashboard, and scenarios

---

*Data Drifters — Turning raw data into visual stories* 🌊📉
