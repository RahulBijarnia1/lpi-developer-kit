# Level 3 — Rahul Bijarnia

## Repository Link
https://github.com/RahulBijarnia1/lpi-level3-agent

## Overview
This project implements an AI agent that connects to the LPI sandbox and generates useful, explainable answers by combining multiple tools with a local LLM.

## What the Agent Does
- Accepts a user query as input  
- Calls multiple LPI tools:
  - smile_overview  
  - query_knowledge  
  - get_case_studies  
- Collects and combines outputs from these tools  
- Uses a local LLM (Ollama) to generate a final response  
- Displays tool outputs clearly to ensure explainability  

## Explainability
The agent shows:
- Which tools were used  
- What data each tool returned  
- Final answer generated using those sources  

This ensures the user can trace how the answer was formed.

## How to Run
pip install -r requirements.txt  
python agent.py "your query"

## Notes
- The agent uses at least two LPI tools as required  
- Output is structured and explainable  
- Built using Python and a local LLM (Ollama)
