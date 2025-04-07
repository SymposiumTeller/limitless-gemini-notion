# Limitless Life Log Processor

This system processes and summarizes Limitless Pendant Life Logs, creating structured summaries in Notion. It uses the Gemini API for intelligent processing and the Notion API for creating formatted summaries.

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Configure environment variables:
- Create an `.env` file and fill in your API keys:
  - NOTION_API_KEY
  - LIMITLESS_API_KEY
  - GEMINI_API_KEY

3. Update the Notion page ID:
- In `life_log_processor.py`, replace `"your-page-id"` with your actual Notion page ID where summaries should be created.

## Usage

Run the script to process today's logs:
```bash
python life_log_processor.py
```

The script will:
1. Fetch life logs from the Limitless API
2. Process and analyze the content using Gemini
3. Create a structured summary in Notion with:
   - Whatever shitty prompt you use


## Features

- Goes brrrrrr

## Requirements

- Python 3.7+
- Notion API access
- Limitless API access
- Gemini API access 
