# TITLE: ASTRAMIND-WEB-AI-AGENT
## Problem statement choosen:
Build an AI agent that can take natural language instructions and autonomously drive the web on a local computer. The system should combine a locally running LLM (for understanding and planning) with a browser automation setup such as Chrome Headless or a browser inside a local VM. Users should be able to give simple commands (e.g., ''search for laptops under 50k and list top 5'') and the agent should execute them by controlling the browser, extracting results, and returning structured outputs.
```
SUMMARY:
```
A person can just type what they want in plain words, like asking for news, products, or recipes. The AI agent understands the request and opens a browser on its own. It searches online, looks at all the results, and picks only the useful information. Then it organizes everything clearly, showing names, short descriptions, prices if needed, and links. Finally, it gives the complete answer in one place, so the person does not have to search or check websites themselves.
The Web Navigator AI Agent is like a smart helper on your computer. You just type what you want in simple words, such as news, products, or recipes. The agent understands your request and then goes online by itself. It searches, checks the results, and picks only the useful information. After that, it organizes everything neatly, showing names, short details, prices if needed, and links. Finally, it gives you the complete answer in one place, so you don’t have to search manually or open many websites.Our solution is the Web Navigator AI Agent — an assistant that goes beyond advice and acts like a digital intern. The agent takes natural language instructions from the user, understands them with a locally running LLM (LangChain + Ollama), and breaks them into clear steps. Through browser automation (Playwright or Selenium), it autonomously opens websites, applies filters, searches for results, and finally lands the user directly on the exact product or page they need. The backend, built with Flask, orchestrates the process, while the frontend provides a simple input interface. Optional features like memory, retries, and voice input make the interaction smooth and human-like.Uniqueness and Impact The uniqueness of our solution lies in its direct action: unlike existing AI systems that stop at giving links or summaries, our agent takes users straight into the live webpage they need — whether it’s the cheapest flight booking page, a specific product on an e-commerce site, or the latest relevant news article. This creates a seamless bridge from intent to action, reducing effort, saving time, and transforming user experience. In essence, our project redefines AI assistance: from being just an “information provider” to becoming an action-taker that navigates the web for you.
```
TECHOLOGIES
```
Backend:Built using Python to handle all the main logic and processes of the AI agent.Uses a local Large Language Model (LLM), optionally with LangChain, to understand user commands and plan tasks.<img width="1950" height="63" alt="image" src="https://github.com/user-attachments/assets/b41a8f61-0e53-447a-8623-494171585d74" />

Frontend :A simple interface using React or any basic UI framework to let users type commands and view results easily.

```
DEMO WORK
```
Step-by-Step Flow:
User Command → The user types or speaks a natural language instruction.
System Execution → The AI agent understands the command, plans the steps, and uses browser automation to perform tasks.
Result Output → The agent collects the required information, organizes it, and displays it in a clean format (table, Excel, or PDF).
Example:
User: “Find top 5 laptops under 50k”
Agent:
Opens Google or shopping sites
Searches for laptops under 50k
Extracts relevant data (names, prices, ratings)
Shows results in a table for easy reading
