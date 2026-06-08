# SmartInvoice AI – Automating Invoice Processing with GPT-4o

## Overview

SmartInvoice AI is an intelligent invoice processing system that automates the extraction, analysis, and reporting of financial data from PDF invoices using GPT-4o, Python, and Pandas.

The application processes multiple invoices, extracts key information such as vendor details, invoice numbers, dates, and amounts, performs basic financial analysis, and generates structured reports for business decision-making.

## Features

* Automated PDF invoice processing
* AI-powered data extraction using GPT-4o
* Invoice classification and validation
* Revenue and expense tracking
* Financial summary generation
* Excel report generation
* Batch processing of multiple invoices
* Structured data export for further analysis

## Tech Stack

* Python
* GPT-4o API
* Pandas
* OpenPyXL
* Poetry
* PDF Processing Libraries

## Project Structure

```text
SmartInvoice-AI/
│
├── main.py
├── extraction.py
├── processing.py
├── config.py
├── prompt.py
│
├── data/
│   └── invoices/
│
├── reports/
│
├── pyproject.toml
└── README.md
```

### File Description

**main.py**

* Entry point of the application.
* Coordinates invoice extraction, processing, and report generation.

**extraction.py**

* Uses GPT-4o to extract structured information from PDF invoices.

**processing.py**

* Validates invoice data.
* Performs financial analysis.
* Generates Excel reports.

**config.py**

* Stores application configuration settings.

**prompt.py**

* Contains prompts used for GPT-4o invoice understanding and extraction.

## Installation

### Prerequisites

* Python 3.11+
* Poetry
* OpenAI API Key

### Install Dependencies

```bash
poetry install
```

### Configure Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key
```

## Running the Application

Place invoice PDFs inside:

```text
data/invoices/
```

Run the application:

```bash
poetry run process-invoices
```

## Example Workflow

1. Upload PDF invoices.
2. GPT-4o extracts invoice information.
3. Invoice data is validated and structured.
4. Financial metrics are calculated.
5. Excel reports are automatically generated.

## Future Enhancements

* Financial dashboard using Power BI
* AI-generated financial narratives
* Expense categorization
* Invoice fraud detection
* Monthly financial report generation
* Predictive cash-flow analysis

## Author

Anmol Kankarwal

B.Tech CSE (AI)
Galgotias University
