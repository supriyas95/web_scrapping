# 🧠 Large Language Models (LLMs) — Comprehensive Encyclopedia

### 📘 Overview
This project presents a **Wikipedia-style encyclopedia** of major **Large Language Models (LLMs)**, covering their **history, versions, ownership, advantages/disadvantages, pricing, and future directions**.  
The content is structured in a clean, responsive **HTML page** generated through a **Jupyter Notebook** using Python and BeautifulSoup-compatible HTML formatting.

---

## 📂 Repository Contents

| File Name | Description |
|------------|-------------|
| `LLM_Encyclopedia.ipynb` | Jupyter Notebook containing all Python code, markdown documentation, and HTML generation logic. |
| `LLM2.html` | Final rendered encyclopedia webpage with full content (history, catalogs, comparison tables, dictionary, etc.). |
| `assets/` *(optional)* | Folder for images, icons, or style extensions (if applicable). |

---

## 🚀 Features

- **Comprehensive Coverage** — Details 13+ major LLM families (OpenAI, Anthropic, Google, Meta, Mistral, xAI, Cohere, Alibaba, Microsoft, DeepSeek, Databricks, IBM, Stability, etc.).
- **Structured Layout** — Clear HTML sections with navigation (`History`, `Catalog`, `Comparison`, `Dictionary`, etc.).
- **PEP-8 Compliant Code** — Modular, well-commented, and easy to read for future extension or scraping tasks.
- **Data Scientist-Friendly** — Uses logical markup and tables to enable potential data extraction and analysis.
- **Dictionary Section** — Includes concise definitions of 20+ technical terms (LLM, Transformer, Tokens, RLHF, MoE, RAG, etc.).
- **Reproducible Notebook** — Running the `.ipynb` notebook regenerates the exact HTML output (`LLM2.html`).

---

## 🧩 Code Structure & Explanation

```bash
LLM_Encyclopedia.ipynb
│
├── 1️⃣ Import and Setup
│   ├── Load HTML libraries (BeautifulSoup, HTML display)
│   ├── Configure UTF-8 rendering
│
├── 2️⃣ HTML Content Generation
│   ├── Create the base structure (`<html>`, `<head>`, `<body>`)
│   ├── Define styles (CSS variables, typography, color palette)
│   ├── Add structured sections using semantic tags (`<section>`, `<article>`, `<table>`)
│
├── 3️⃣ Data Population
│   ├── Insert details for each LLM family (OpenAI GPT, Anthropic Claude, etc.)
│   ├── Add comparison and pricing tables
│   ├── Append the dictionary of key terms
│
├── 4️⃣ Validation
│   ├── Verify structure with BeautifulSoup
│   ├── Ensure all tags and IDs are unique
│
└── 5️⃣ Export
    ├── Write HTML to `LLM2.html`
    ├── Print validation summary
