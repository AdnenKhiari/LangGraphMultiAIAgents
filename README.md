# Multi-Agent Communication and Execution Project

A multi-agent system designed to execute complex tasks through specialized tools and agents, utilizing advanced natural language processing ( LLMS ) .

## System Components and Tool Integration

The system features several key agents, each equipped with specific tools:

- **Input Assistant:** Uses NLP ( LLMS )  to process user commands, translating them into structured tasks.
- **Task Planner:** Plans and organizes tasks, delegating them to appropriate execution agents.
- **Execution Agents:** Specialized agents execute tasks, employing tools like:
  - **Travel Search Tool (Travily Search):** Retrieves travel-related data and booking options.
  - **Weather API:** Provides real-time weather updates and forecasts.
  - **Simple Math Calculator:** Performs arithmetic and basic mathematical calculations.
  - **Supplementary LLM:** Handles complex queries and additional tasks not covered by primary tools.
- **Memory and Learning Agent:** Manages data storage, retrieval, and system learning to improve response accuracy.

Agents communicate through a message-passing interface, ensuring clear and precise task handling across the system.
