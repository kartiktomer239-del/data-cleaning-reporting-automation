# 📊 Automated Data Cleaning & Reporting Pipeline

An automated data pipeline built in Python designed to streamline the ingestion, preprocessing, cleaning, and reporting of weekly sales data. This project eliminates hours of manual spreadsheet maintenance by converting messy, inconsistent raw data into polished, boardroom-ready executive insights with a single click.

---

## 🚀 Key Features

*   **Automated Preprocessing & Data Cleansing:**
    *   Identifies and handles missing critical identifiers (e.g., Transaction IDs).
    *   Imputes missing financial metrics using calculated column medians.
    *   Detects and removes duplicate entries automatically.
    *   Standardizes inconsistent structural data (e.g., merging "ny", "Nyc", and "New York").
    *   Enforces strict ISO datetime compliance.
*   **Dynamic Visual Reporting:** Generates high-resolution diagnostic charts (`.png`) breaking down metrics like regional revenue distribution.
*   **Executive Performance Text Summaries:** Automatically outputs localized, text-based KPI summaries perfect for instant copy-pasting into team channels or email updates.

---

## 📁 Repository Structure

```text
├── 📁 raw_data/          # Input folder containing unrefined, messy source data (CSV)
├── 📁 clean_data/        # Output folder where standardized, timestamped CSVs are saved
├── 📁 reports/           # Contains generated visual charts, text summaries, and screenshots
├── run_pipeline.py       # Core Python automation engine script
└── README.md             # Project documentation and setup guide
