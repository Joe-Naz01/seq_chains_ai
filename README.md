# LangChain Mastery: Sequential Chains & AI Agents 

This repository explores advanced orchestration within the **LangChain** ecosystem, specifically focusing on **Sequential Chains** and **Agentic Workflows**. It demonstrates how to move beyond single-prompt interactions to build complex, multi-step AI systems that can reason and interact with data.

## Project Overview
The project is divided into two major architectural patterns:
1. **Sequential Skill-Building System**: A workflow built using **LangChain Expression Language (LCEL)** that sequentially processes user preferences and constraints to generate tailored learning plans.
2. **Autonomous Customer Agents**: An implementation of an AI Agent designed to act as a natural language interface for databases. It can autonomously retrieve, filter, and summarize specific customer entities (e.g., "Peak Performance Co.") based on conversational input.

## Key Features
* **LCEL Implementation**: Utilizing the LangChain Expression Language for clean, readable, and efficient chain composition.
* **Sequential Logic**: Designing multi-stage prompt templates where the output of one step informs the context of the next.
* **Tool-Augmented Agents**: Building agents that can "think" and use external tools to fetch real-world data before formulating a response.
* **Data Summarization**: Automated extraction of key metrics (ID, Subscription Type, Active Users) from structured data via natural language.



## Tech Stack
* **Language**: Python
* **Framework**: LangChain (LCEL)
* **LLM Integration**: Google Gemini / ChatGoogleGenerativeAI
* **Tools**: LangChain Community Tools, Pandas

## Setup & Installation

### 1. Environment Configuration
It is recommended to use a dedicated environment for LangChain projects:

```bash
# Create and activate the environment
git clone https://github.com/Joe-Naz01/seq_chains_ai.git
cd seq_chains_ai

conda create -n chains_agents python=3.10 -y
conda activate chains_agents

jupyter notebook

# Install dependencies
pip install -r requirements.txt