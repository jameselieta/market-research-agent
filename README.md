# Market Research Agent Built with the Crewai Framework

This AI agent is designed to conduct comprehensive market research and facilitate the analysis of findings. The agent performs two main tasks:

## Key Functions

1. **Market Research**: The agent investigates current trends within a specific topic or industry, gathering relevant data on areas of interest.
2. **Analysis and Reporting**: The agent forwards its findings to an Analyst, who reviews the data and compiles a detailed report.

## Task Descriptions

### Research Task

- **Description**:  
  Conduct a thorough market analysis on the specified topic. Ensure you uncover interesting and relevant information pertaining to `{topic}`, considering the current year is 2024.
  
- **Expected Output**:  
  A list of 10 bullet points highlighting the most relevant information about `{topic}`.

- **Agent**: Researcher

### Reporting Task

- **Description**:  
  Review the findings from the research phase and expand each bullet point into a comprehensive section for a report. Ensure that the report is detailed and includes all pertinent information.

- **Expected Output**:  
  A fully developed report containing main topics, each elaborated in a complete section of information, formatted in Markdown (without code blocks).

- **Agent**: Reporting Analyst
