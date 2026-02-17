# Gemini Project

This directory is the root of a new project. The purpose of this file is to provide context to the Gemini AI, helping it understand the project and assist you more effectively.

## Mentorship Log: Data Engineering Career Track

**Goal:** Master Data Engineering (SQL, Python, ETL, BI, Warehouse, Auto, AI) to secure a new job.
**Constraints:** Shortest effective time, free resources/certs.
**Mentor:** Gemini (AI Expert).

### Strategic Philosophy: "Build to Learn"
Certifications get you past the HR filter; Projects get you past the Technical Interview. We will focus on a 70/30 split: 70% building pipelines, 30% coursework for badges.

### Core Resources (The "Golden Path")
1.  **Data Engineering Zoomcamp (DataTalks.Club):** The single best free, comprehensive resource. Covers Docker, Terraform, GCP, Airflow, Spark, Kafka.
2.  **Databricks Academy:** "Databricks Lakehouse Fundamentals" (Free Badge).
3.  **LinkedIn Learning:** "Become a Data Engineer" (Good for high-level concepts & LinkedIn badge).

### Immediate Roadmap: The First 3 Days (Foundation Sprint)

**Objective:** Go from zero to a running "Hello World" data pipeline on your local machine.

#### Day 1: The Modern Stack Setup & Fundamentals
*   **Concept:** Understanding OLTP vs. OLAP and Dimensional Modeling (Star Schema).
*   **Action:**
    *   Install **Docker Desktop** (Industry standard for running tools).
    *   Install **VS Code** + Python extensions.
    *   **Task:** Spin up a local Postgres database using Docker.
    *   **Study:** LinkedIn Learning "Programming Foundations: Databases" or "Data Engineering Foundations".

#### Day 2: The "E" and "L" (Extract & Load)
*   **Concept:** APIs and Python Scripting.
*   **Action:**
    *   Write a Python script to fetch data from a public API (e.g., CoinGecko, OpenWeatherMap, or RandomUser.me).
    *   Use the `pandas` library to clean/format this data.
    *   Insert this data into your Dockerized Postgres database from Day 1.
    *   **AI Assist:** Use Gemini/ChatGPT to explain the code, but type it yourself.

#### Day 3: Visualization & "The Cloud"
*   **Concept:** BI Tools and Cloud Storage.
*   **Action:**
    *   Connect a BI tool to your local Postgres. (Use **Metabase** running in Docker - it's free and popular in DE).
    *   Create 1 Dashboard showing a trend from your API data.
    *   **Certification Task:** Complete the "Databricks Lakehouse Fundamentals" accreditation (approx 2-3 hours, free).

## Directory Overview

This is a new project directory. As you add files and structure, you can update this section to describe the overall layout.

**Example:**

This directory contains a Python project for analyzing financial data.

-   `/data`: Contains raw data files.
-   `/notebooks`: Jupyter notebooks for exploratory analysis.
-   `/src`: Python source code for data processing and modeling.
-   `/tests`: Unit tests for the source code.

## Key Files

Once you have some files, list the most important ones here and briefly explain their contents.

**Example:**

-   `src/main.py`: The main entry point for the application.
-   `requirements.txt`: A list of Python dependencies for this project.
-   `config.yaml`: Configuration settings for the application.

## Usage

Explain how the contents of this directory are intended to be used. For a code project, you would include instructions on how to build, run, and test the code.

**Example (for a code project):**

### Building and Running

1.  Install dependencies: `pip install -r requirements.txt`
2.  Run the application: `python src/main.py`

### Testing

Run the tests with: `pytest`