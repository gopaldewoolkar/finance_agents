## Building an AI Financial Agents 😀

### Agent Architecture
The system is composed of two primary agents orchestrated to work together:

1. Research Agent
  - Role: Gathers broad, general information from the web.
  
  - Tools: DuckDuckGoTools and Newspaper4kTools.
  
  - Purpose: To provide the initial context and the latest news on a company.

2. Finance Agent
  - Role: Focuses on retrieving and analyzing specific financial data.
  
  - Tools: YFinanceTools.
  
  - Purpose: To provide detailed financial metrics, stock prices, and other relevant data points.

The system's core logic handles the delegation of tasks between these two agents, allowing for a structured and efficient workflow for financial reporting.
