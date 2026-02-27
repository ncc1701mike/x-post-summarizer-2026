# x-post-summarizer-2026

This repository summarizes a public figure's 2026 X posts using AI.

## Analyzed Account
- Handle: @llm_wizard

## Project Overview
This project was built using a LangGraph agent with GitHub MCP tools for repository operations and the X API v2 for retrieving posts.

## How to Replicate
1. Set up your X API Bearer Token as an environment variable named `X_BEARER_TOKEN`.
2. Install Python dependencies:
   ```
   pip install requests
   ```
3. Run the `x_search.py` script to fetch recent posts from the desired X handle.

This setup allows you to generate summaries of public figures' posts using AI and automate repository management with MCP tools.
