# Vendor Scraper Template

This folder serves as a starting point for scraping a vendor's product catalog using Apify.

## Required files:
- `main.py` – the Python scraper logic
- `apify.json` – Apify metadata (memory, timeout, etc.)
- `requirements.txt` – Python dependencies
- `sample_output.json` – (add one!) example output following our schema

## Guidelines:
- Use the Apify SDK: `from apify import Actor`
- Push data with: `await Actor.push_data(data)`
- Output must match the structure in `/vendor_schema.md`
