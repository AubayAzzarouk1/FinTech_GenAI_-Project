## AI - Powered Financial ChatBot: Analyzing 10-k and 10-Q Filings with Generative AI

This project explores the intersection of generative AI and financial data analysis, with a focus on extracting insights from SEC filings and delivering them through an interactive AI chatbot.

---
## Key Components: 

1. Data Extraction:
  - Parsing SEC 10-K and 10-Q documents for Tesla, Apple, and Microsoft using Python and Microsoft Excel
  - Extracting structured financial data and narrative disclosures
2. Data Analysis:
  - Identifying trends in revenue, net income, operating cash flow, and more
  - Calculating year-over-year growth, profitability ratios, and liquidity measures
  - Cleaning and preparing data for downstream NLP tasks
3. ChatBot Development:
 - Implemented using Python and natural language processing libraries
 - Designed to answer questions like:
    - “What were the major drivers of revenue growth last year?”
    - “How does this quarter’s net income compare to the previous quarter?”
    - “What financial risks are highlighted in the 10-K?”
- Focused on clarity, context, integrity, and user engagement.

4. Consulting Alignment:
   - Insights are presented in a way that supports strategic recommendations
   - Focus on making financial data actionable for consulting teams and clients 


---
## The repository is organized into the following folders:

data_extraction: Scripts for parsing and structuring SEC filings

financial_analysis: Jupyter notebooks with key metric calculations and trend analysis

chatbot: Core chatbot logic, prompts, and interaction examples

demo: Sample conversations and usage scenarios

docs: Project notes and architecture diagrams

To try out the chatbot or run the analysis pipeline locally, follow the setup instructions in the docs/setup_guide.md file.

---

# Frameworks, Languages, and Libraries Used: 
- Python
- Juypter Notebook
- Pandas and Numpy - financial analysis at components 1 and 2.
- spaCy and NLTK for NLP Tasks.
- LangChain and OpenAI for chatbot integration
- Excel for interm data extraction, cleaning, analysis, and validation.


---
## Future Work
Expand chatbot capabilities to support industry-specific financial insights

Integrate peer comparison and benchmarking

Deploy as a web app for internal consulting use

