# Data Analyst Agent API  
An AI-powered API that can source, prepare, analyze, and visualize any data on demand.  

---

## Overview
The **Data Analyst Agent API** lets you send a **natural language request** describing your analysis task, and it will:
1. **Source** datasets (from your URLs or public datasets).  
2. **Clean & prepare** the data.  
3. **Analyze** it (statistics, comparisons, modeling).  
4. **Visualize** it (charts, graphs).  
5. **Return** results (summary text, plots, and data files).  

Built with **FastAPI**, **Pandas**, **Matplotlib**, **DuckDB**, and **Gemini Flash**

---

## Features
- Accepts **plain English** analysis requests.
- Supports multiple **data sources** (CSV, JSON, Parquet, APIs).
- Automatic data cleaning and processing.
- Generates **visualizations** (PNG, SVG).
- Returns a **natural language summary** and downloadable results.
- Runs analysis in a **secure sandbox**.
- **Dockerized** for deployment.
---

## Prerequisites
Before you install and run the API, make sure you have:

1. **Python 3.11 or later**  
   [Download here](https://www.python.org/downloads/)

2. **Google Gemini API key**  
   - Sign up at [Google AI Studio](https://aistudio.google.com/app/apikey)  
   - Copy your key and save it for `.env`

3. **Git** (to clone the repo)  
   [Download here](https://git-scm.com/downloads)

4. **pip** (Python package manager)  
   Comes with Python, but you can upgrade:
   ```bash
   python -m pip install --upgrade pip
