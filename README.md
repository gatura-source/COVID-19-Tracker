# COVID-19-Tracker
# 🦠 COVID-19 Global Data Tracker

A data analysis and visualization project tracking global COVID-19 trends using real-world data and Python tools.

## 📌 Project Description

This project explores global COVID-19 data to analyze **cases**, **deaths**, **recoveries**, and **vaccination progress** over time and across countries. The goal is to clean, analyze, and visualize COVID-19 trends, then present insights in a clear and informative Jupyter Notebook.

By the end of the project, you'll have an analysis report with charts and written summaries—suitable for presentation or publishing.

---

## 🚀 Project Objectives

- ✅ Import and clean COVID-19 global data
- ✅ Analyze time trends (cases, deaths, vaccinations)
- ✅ Compare metrics across countries or regions
- ✅ Visualize trends with charts
- ✅ Communicate findings using narrative and code

---

## 🗂️ Project Segments (Step-by-Step)

### 1️⃣ Data Collection

**Goal:** Obtain a reliable COVID-19 dataset.

- Source: [Our World in Data - owid-covid-data.csv](https://ourworldindata.org/covid-cases)
- Alternative: Johns Hopkins CSSE GitHub repo (advanced)

**Action:** Download `owid-covid-data.csv` and place it in your working directory.

---

### 2️⃣ Data Loading & Exploration

**Goal:** Load and explore dataset structure.

**Tasks:**
- Load using `pandas.read_csv()`
- Preview columns and rows
- Check for missing values

**Key Columns:**
- `date`, `location`, `total_cases`, `new_cases`, `total_deaths`, `total_vaccinations`, etc.

---

### 3️⃣ Data Cleaning

**Goal:** Prepare the dataset for analysis.

**Tasks:**
- Filter for countries of interest (e.g., Kenya, USA, India)
- Drop irrelevant/missing rows
- Convert `date` to datetime
- Fill or interpolate missing numeric values

---

### 4️⃣ Exploratory Data Analysis (EDA)

**Goal:** Generate trends and summaries.

**Tasks:**
- Plot total cases/deaths over time
- Compare daily new cases
- Calculate and analyze death rates

**Visuals:**
- Line charts
- Bar charts
- (Optional) Heatmaps for correlation

---

### 5️⃣ Visualizing Vaccination Progress

**Goal:** Track vaccination rollout across countries.

**Tasks:**
- Plot cumulative vaccinations
- Compare vaccination rates

**Charts:**
- Line charts
- Optional: Pie charts

---

### 6️⃣ (Optional) Choropleth Mapping

*Skipped in this project, but you can use Plotly or GeoPandas for geographic visualizations of global cases.*

---

### 7️⃣ Insights & Reporting

**Goal:** Summarize key findings.

**Tasks:**
- Document 3–5 narrative insights
- Highlight unusual trends or patterns
- Use markdown cells for storytelling

**Deliverables:**
- 📘 Jupyter Notebook (.ipynb)
- 📊 Visualizations
- 📝 Written summaries

---

## 📦 Tools Used

- `pandas`
- `matplotlib`
- `seaborn`
- `Jupyter Notebook`

*(Note: `plotly` or `geopandas` not used in this version.)*

