# Task 2 – Samsung Phone Advisor (Jupyter Notebook Based)

## Overview
This project implements a **Samsung Phone Advisor** system that allows users to ask
natural-language questions about Samsung smartphones.  
The system retrieves phone specifications from a **PostgreSQL database** and generates
human-readable reviews or comparisons using a **RAG (Retrieval-Augmented Generation)**
and **Multi-Agent** approach.

The entire project is implemented **only using Jupyter Notebook (`.ipynb`)** without any
`.py` files.

---

## Features
- Scrapes Samsung phone data from **GSMArena**
- Stores phone specifications in **PostgreSQL**
- Uses **RAG** to retrieve structured phone data
- Uses **Multi-Agent reasoning**:
  - Agent 1: Data Extractor (fetches specs from database)
  - Agent 2: Review Generator (creates natural language reviews/comparisons)
- Provides a **single FastAPI endpoint** for all queries
- Accepts **natural-language questions**
- Runs FastAPI **inside Jupyter Notebook**

---

## Technology Stack
- Python (Jupyter Notebook)
- FastAPI
- PostgreSQL
- SQLAlchemy
- BeautifulSoup (Web Scraping)
- Uvicorn
- nest-asyncio

---
