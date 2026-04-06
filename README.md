# JSON Telemetry Data Converter

## ✔ Status: Completed

## 📌 Overview
This project converts telemetry data from multiple JSON formats into a single unified structure. It simulates a real-world backend task where systems receive data from different sources and need standardization.

## 🚀 Features
- Supports multiple input JSON formats
- Converts ISO timestamps to milliseconds (epoch format)
- Extracts and restructures nested data
- Handles location parsing into structured fields
- Includes unit tests to ensure accuracy

## 🛠 Technologies Used
- Python
- JSON
- unittest (for testing)

## ⚙️ How It Works
The system detects the input format and:
- Converts Format 1 directly (timestamp already in milliseconds)
- Converts Format 2 by transforming ISO timestamp into milliseconds
- Outputs a unified structured JSON format

## ▶️ How to Run
1. Clone or download the project
2. Open terminal in project folder
3. Run:
   ```bash
   python main.py
