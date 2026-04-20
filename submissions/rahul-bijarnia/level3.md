# Level 3 — Rahul Bijarnia

## Repository Link
https://github.com/RahulBijarnia1/lpi-level3-agent

## Overview
I built an AI agent that connects to the LPI sandbox and generates useful, explainable answers by combining multiple tools with a local LLM.

## What I Built
The agent takes a user query and processes it by calling multiple LPI tools. Instead of relying on a single response, it gathers structured data from different sources and combines them to generate a final answer.

## Tools Used and Their Role
- **smile_overview**  
  Provides the SMILE methodology, which gives structured context for understanding the problem.

- **query_knowledge**  
  Returns domain-specific knowledge related to the user query.

- **get_case_studies**  
  Provides real-world examples showing how the concept is applied.

## How the Agent Works (Step-by-Step)
1. The user enters a query through the command line  
2. The agent calls multiple LPI tools:
   - smile_overview  
   - query_knowledge  
   - get_case_studies  
3. Each tool returns structured information  
4. The agent combines all responses into a single prompt  
5. The combined data is sent to a local LLM (Ollama)  
6. The LLM generates a clear and summarized final answer  

## Explainability (Important Requirement)
The agent ensures explainability by clearly showing:
- Output from each LPI tool  
- How each tool contributes to the final answer  
- The final response generated using all sources  

This allows users to trace exactly how the answer was formed instead of treating it as a black box.

## Example Flow
Input:
python agent.py "What are digital twins in healthcare?"

Output:
- SMILE overview  
- Knowledge explanation  
- Case studies  
- Final combined answer  

## How to Run
pip install -r requirements.txt  
python agent.py "your query"

## Notes
- Uses at least 2 LPI tools (actually 3)  
- Combines structured tool data with LLM output  
- Focuses on explainable AI rather than just generating answers  
