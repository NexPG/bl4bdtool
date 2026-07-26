# Borderlands 4 Item Parsers

A lightweight, automated data-extraction utility designed to parse modular item statistics, generation rules, and loot pools directly from Borderlands 4 dNexusConfigStore Dumps. This tool converts complex, nested JSON schemas into clean, flat tables (CSV) optimized for relational database integration.

This is a personal project developed to streamline game data extraction, which is subsequently used to populate and support our **Borderlands 4 Database**.

---

## Project Structure

To run the parsers, ensure your local directory follows this structure:

```text
bl4bdtool/
├── data/
│   ├── raw_things/    <-- Place your raw NCS JSON files here
│   └── output/        <-- Parsed CSV files will be generated here
└── parsers/           <-- Contains parsers for different item classes