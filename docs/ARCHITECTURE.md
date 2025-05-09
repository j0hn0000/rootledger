
# RootLedger: Architecture Brief (v0.1)

## Purpose
Translate legacy healthcare data into structured, interoperable formats using AI-assisted schema mapping and a transparent local ledger system.

## Components
1. Ingestor: Parses legacy CSV/PDF/XML.
2. Translator: Uses GPT-4 for schema mapping.
3. API Layer: Exposes FHIR-like endpoints.
4. Ledger: Records mapping logic and prompt history.
5. Output: Generates transformed data (FHIR-lite JSON).

## Stack
- Python 3.11+
- FastAPI or Flask
- OpenAI GPT-4 (or local LLM)
- SQLite or file-based JSON storage
