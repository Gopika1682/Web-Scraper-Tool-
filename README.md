# Web-Scraper-Tool-
A Python-based web scraper that extracts structured data from a dynamic, JavaScript-rendered web application using browser automation and exports the results to CSV files.


Automated Web Scraping and Data Extraction

Overview
This repository contains a three-part web scraping project built using Python and Playwright.
The tasks aim to extract structured data from the Tines Library across three phases:
1. Task 1: Scrape all tools and their number of stories.
2. Task 2: For each tool, scrape all stories with details.
3. Task 3: Scrape all stories in one view from ?view=all.
All extracted data is printed to the terminal and saved as CSV files in the Output/ folder.

Folder Structure
Gopika-RD-Assignment/
│
├── code/
│ ├── main.py # Main script to run all tasks
│ └── requirements.txt # Python dependencies
│
├── Output/
│ ├── scraper_tools.csv # Output of Task 1
│ ├── scraper_tool_stories.csv # Output of Task 2
│ └── scraper_all_stories.csv # Output of Task 3
│
├── README.md # Project overview and setup instructions
└── Documentation.pdf # Detailed documentation of tasks and implementation

System Requirements
Operating System: Windows 10/11, macOS, or Linux
Python Version: 3.9 or later
Internet Connection: Required for accessing Tines Library
Dependencies: PlayWright for python

Setup Instructions
1. Clone or unzip this repository.
2. Navigate to the code/ directory:cd code
3. Verify Python installation:python --version
4. Install dependencies:pip install -r requirements.txt
5. Install Playwright browsers (required once):playwright install

Running the Code
Run all tasks sequentially:
python main.py
Task 1 outputs: scraper_tools.csv
Task 2 outputs: scraper_tool_stories.csv
Task 3 outputs: scraper_all_stories.csv
All files are saved in the Output/ folder. During execution, extracted data will also print in real-time in the
terminal.

Notes
Missing fields (e.g., Author or Works with) are stored as "null".
Code reusability:
Task 1 logic reused in Task 2.
Task 2 logic reused in Task 3.
The scraping process may take a few minutes depending on network speed.

References
Data Source: Tines Library
Libraries & Tools: Playwright, Python Documentation
Learning Resources: YouTube tutorials on Playwright for web scraping
Assistance: OpenAI GPT-4 for guidance and optimization
