# MCP Project

Course Notes and Code from https://learn.deeplearning.ai/courses/mcp-build-rich-context-ai-apps-with-anthropic

## Instruction for MCP Server Setup and Inspector Launch

-   uv init
-   uv venv
-   source .venv/bin/activate
-   uv add mcp arxiv
-   npx @modelcontextprotocol/inspector uv run research_server.py
    -   If you get a message asking "need to install the following packages", type: y
    -   You will get a message saying that the inspector is up and running at a specific address. To open the inspector, click on that given address. The inspector will open in another tab.

## Instructions for MCP Chatbot

-   Everything in MCP Server Setup if not already done
-   uv add anthropic python-dotenv nest_asyncio
-   uv run mcpchatbot.py
