# Audit & Inspection Rights Clause Extractor

This project extracts all occurrences of the "Audit & Inspection Rights" clause from a given contract document (`.docx`) using the **Groq LPU engine** and **LangChain**. The extracted clauses are saved in an Excel file for further analysis.

---

## Features
- **Document Loading**: Supports `.docx` files using LangChain's built-in document loaders.
- **Text Chunking**: Splits large documents into smaller chunks for processing by the LLM.
- **Clause Extraction**: Uses the Groq LPU engine to extract "Audit & Inspection Rights" clauses based on predefined rules.
- **Excel Output**: Saves the extracted clauses in an Excel file, with each clause in a separate cell.

---

## Prerequisites
- Python 3.8 or higher
- Groq API key (for using the Groq LPU engine)
---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Tushar01-repo/cognizer_ai_assessment.git
   cd cognizer_ai_assessment

2. Export your api key
   ```bash
   export GROQ_API_KEY="your_groq_api_key"

3. Setup enviroment from environment.yaml file
   ```bash
   conda env create -f environment.yaml

4. Activate your environment
   ```bash
   conda activate audit-inspection-clause-extractor

## files

Tushar_Pal_Assessment/
├── extraction.ipynb               # Main .ipynb script for audit & clause extraction
├── contract_interview.docx        # dataset for extraction
├── environment.yml                # Conda environment configuration
├── README.md                      # This file
└── extracted_content.xlsx         # Output Excel file (generated after running the script)


