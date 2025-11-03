# Large Language Models (LLMs) — Comprehensive Encyclopedia

## Overview
This project presents a **Encyclopedia** of major **Large Language Models (LLMs)**, covering their **history, versions, ownership, advantages/disadvantages, pricing, and future directions**.  
The content is structured in a clean, responsive **HTML page** generated through a **Jupyter Notebook** using Python and BeautifulSoup-compatible HTML formatting.

The project also demonstrates the use of **Beautiful Soup**, a Python library for web scraping and HTML parsing. Beautiful Soup is used here to read, validate, and manipulate the generated HTML file (`LLM2.html`), ensuring proper structure and enabling potential data extraction workflows for data scientists.

---

## Repository Contents

| File Name | Description |
|------------|-------------|
| `LLM_Encyclopedia.ipynb` | Jupyter Notebook containing all Python code, markdown documentation, and HTML generation logic. |
| `LLM2.html` | Final rendered encyclopedia webpage with full content (history, catalogs, comparison tables, dictionary, etc.). |
| `BeautifulSoup.pdf` | Slide deck summarizing library overview, usage, and key demonstrations. |

---

## Features

- **Comprehensive Coverage** — Details over a dozen major LLM families, including OpenAI, Anthropic, Google, Meta, Mistral, xAI, Cohere, Alibaba, Microsoft, DeepSeek, Databricks, IBM, and Stability.
- **Structured Layout** — Organized sections with headings for History, Catalog, Comparison, Use Cases, Pricing, Future Models, Dictionary, and References.
- **PEP-8 Compliant Code** — Modular, well-documented Python following standard conventions.
- **Data Scientist Application** — Demonstrates parsing and extracting structured data (tables, lists, and definitions) for analytical use.
- **Dictionary Section** — Includes concise definitions of over 20 technical AI terms (LLM, Transformer, Tokens, RLHF, MoE, RAG, etc.).
- **Reproducibility** — Running the Jupyter Notebook regenerates the exact HTML output, ensuring full reproducibility.

---

## Code Structure & Explanation

```bash
LLM_Encyclopedia.ipynb
│
├── 1. Import and Setup
│   ├── Load HTML libraries (BeautifulSoup, HTML display)
│   ├── Configure UTF-8 rendering
│
├── 2. HTML Content Generation
│   ├── Create the base structure (<html>, <head>, <body>)
│   ├── Define styles (CSS variables, typography, color palette)
│   ├── Add structured sections using semantic tags (<section>, <article>, <table>)
│
├── 3. Data Population
│   ├── Insert details for each LLM family (OpenAI GPT, Anthropic Claude, etc.)
│   ├── Add comparison and pricing tables
│   ├── Append the dictionary of key terms
│
├── 4. Validation
│   ├── Verify structure using BeautifulSoup
│   ├── Ensure all tags, IDs, and navigation links are valid
│
└── 5. Export
    ├── Write the final output to LLM2.html
    ├── Print validation summary
