# Contributing

Thank you for your interest in this project.

## Environment

- Databricks Free Edition
- Unity Catalog volume for PDF storage
- No DBFS, no Jobs, no Model Serving

## Project Structure

- `AI-Compliance-Document-Assistant.ipynb` – main Databricks notebook
- `architecture.md` – pipeline architecture and design notes
- `LICENSE` – MIT license
- `README.md` – project overview

## Adding New PDFs

1. Upload the PDF into your Unity Catalog volume, e.g.:  
   `/Volumes/workspace/hackathoncompliancedoc/documents`
2. Update any hardcoded paths if needed.
3. Re-run the consolidated notebook:
   - `AI-Compliance-Document-Assistant.ipynb` (located in the root directory)

## Issues

Please open an issue if you see:

- Extraction errors (blank pages, missing sections)
- Token limit issues
- Poor retrieval relevance
