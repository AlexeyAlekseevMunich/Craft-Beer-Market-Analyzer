# Craft-Beer-Market-Analyzer

## Project Overview

This is a **personal learning project (Pet Project)** aimed at collecting, storing, analyzing, and visualizing data about craft beer offerings from various online retailers, primarily in the German market. The primary goal is to identify market trends, popular styles, pricing strategies, new arrivals, and stock turnover rates.

This project serves as a practical application and extension of skills acquired during my professional development, particularly in Python, SQL, data handling, and potentially web technologies.

**Technologies Planned / Used:**
*   **Data Collection:** Python (Requests, BeautifulSoup, Selenium for dynamic sites)
*   **Data Processing & Analysis:** Python (Pandas, NumPy), SQL
*   **Data Storage:** PostgreSQL
*   **Data Visualization:** Power BI
*   **Version Control:** Git
*   **(Potential) Web Interface/API:** Flask/Django (for future enhancements)

## Project Goals

*   To build a robust data pipeline for scraping beer data from selected e-commerce websites.
*   To design and implement an efficient relational database schema for storing structured beer information.
*   To perform in-depth trend analysis on various beer attributes (price, style, brewery, ABV, availability, sales velocity).
*   To create insightful and interactive dashboards visualizing these trends.
*   To apply and deepen practical skills in web scraping, data engineering, database management, and business intelligence.
*   To explore full-stack development aspects by potentially adding a simple web interface or API later.

## Project Roadmap

The project will be developed iteratively through the following key stages:

*   **Stage 1: Core Scraper Development (MVP)**
    *   Develop a Python scraper for an initial target online beer shop.
    *   Extract key beer information (Name, Brewery, Style, Price, Volume, ABV, Availability).
    *   Initially store scraped data in a structured format (e.g., CSV) for testing and schema design.
    *   *Key Focus: Web scraping techniques, HTML parsing, robust error handling.*

*   **Stage 2: Database Design & Setup (PostgreSQL)**
    *   Design a relational database schema (beers, breweries, shops, price history, stock levels, etc.).
    *   Set up a PostgreSQL database instance.
    *   Create tables, define relationships, and implement constraints (DDL).
    *   *Key Focus: Database design principles, normalization, SQL DDL, PostgreSQL specifics.*

*   **Stage 3: Data Ingestion Pipeline**
    *   Modify Python scraper(s) to load data directly into the PostgreSQL database.
    *   Implement data cleaning, transformation (ETL/ELT basics), and validation during ingestion.
    *   Handle data updates and avoid duplicates.
    *   *Key Focus: Python-PostgreSQL interaction (`psycopg2`/`SQLAlchemy`), data pipeline concepts.*

*   **Stage 4: Initial Data Analysis & Power BI Visualization**
    *   Write SQL queries for preliminary data analysis (e.g., popular styles, price distributions).
    *   Connect Power BI to the PostgreSQL database.
    *   Create initial dashboards with key performance indicators (KPIs) and visualizations.
    *   *Key Focus: Analytical SQL, DAX (in Power BI), dashboard design.*

*   **Stage 5: Expanding Scraper Coverage & Robustness**
    *   Add scrapers for additional online beer shops to broaden data scope.
    *   Implement Selenium for websites requiring JavaScript rendering or complex user interactions.
    *   Refine error handling and logging for all scrapers.
    *   *Key Focus: Adapting scrapers to different site structures, advanced scraping with Selenium.*

*   **Stage 6: Advanced Analytics & Trend Monitoring**
    *   Develop logic to track new arrivals, stock changes, and estimate sales velocity.
    *   Perform more complex trend analysis (e.g., seasonal trends, brewery performance).
    *   Utilize Python (Pandas, NumPy, possibly scikit-learn for basic predictions) for deeper analysis.
    *   *Key Focus: Time-series considerations, advanced data manipulation with Pandas.*

*(Further development may include automation, API development, and more sophisticated machine learning models.)*

---

*This README is a living document and will be updated throughout the project's lifecycle.*
