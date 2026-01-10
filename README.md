# Web Scraping and AI-Based News Summarizer
## Overview
This project performs website content summarization. It scrapes the latest news articles from a public news website and utilizes a Large Language Model(LLM) to generate concise summaries.
The program is designed to run on Jupyter notebook with markdown rendering.
<img src="hero_banner.png" >
## Prerequisites
* Python 3.9 or higher  - https://www.python.org
* Groq API key  - https://groq.com
    
## Installation


* Step 1: Clone the repository 
  * ```
    git clone https://github.com/Sivarathinam-sd/Web-Scraping-and-AI-Based-News-Summarizer.git
    cd Web-Scraping-and-AI-Based-News-Summarizer
    
* Step 2: Create and activate a virtual environment
  * ```
    python -m venv venv
  
  * For Mac ```source venv/bin/activate``` | For windows ```venv/Scripts/activate```
* Step 3: Install dependencies
  * ```
    pip install -r requirements.txt
* Step 4: Set up the API Key
  * Create a .env file in the root directory
  * Add the following line
    ```
    GROQ_API_KEY="your api key"
* Step 5: Run the Project
  * Open the file ```webScrapSummarizer.ipynb```
  * Run the cells sequentially to execute the web scraping and summarization.

