# AI-Driven Supply Chain Intelligence: Adaptive Web Search with ReAct Prompting and AI Agents

## Overview

This project leverages AI and adaptive web search to assess and manage various risks in the supply chain. It utilizes ReAct prompting, AI agents, and external search tools to provide comprehensive risk evaluations.

## Objectives

- **Financial Risk Assessment**: Evaluate the financial stability and risk of suppliers.
- **Geopolitical Risk Assessment**: Assess the geopolitical risks and stability in regions where suppliers operate.
- **Environmental Risk Assessment**: Evaluate the environmental risks and impacts associated with suppliers.
- **Adaptive Search**: Perform dynamic follow-up searches based on initial search results to gather more detailed information.
- **Automation**: Automate the risk assessment process using AI agents and ReAct prompting.

## Technologies and Tools

- **Python**: The primary programming language used for the project.
- **Dask**: Used for parallel computing and task automation.
- **OpenAI GPT-3.5**: Utilized for generating ReAct prompts and analyzing search results.
- **Tavily API**: Employed for conducting external web searches and gathering relevant data.
- **Autogen**: A framework for generating and managing AI agents and user proxies.
- **LocalCommandLineCodeExecutor**: Used for executing code locally.

## Project Structure

The project is structured into the following components:

- **Configuration**: Settings for OpenAI and Tavily API keys.
- **ReAct Prompts**: Pre-defined prompts for financial, geopolitical, and environmental risk assessments.
- **AI Agents**: Defined agents for each type of risk assessment, which interact with the user and execute searches.
- **Search Function**: A function that uses the Tavily API to conduct searches based on the prompts.
- **Cache and Execution**: Mechanisms for caching results and executing code locally.

## How to Run the Project

### Prerequisites

- **Python 3.8+**: Ensure you have a compatible version of Python installed.
- **Dask**: Install Dask using `pip install "dask[dataframe]"` or `conda install dask -c conda-forge`.
- **OpenAI API Key**: Obtain an API key from OpenAI and set it as an environment variable (`OPENAI_API_KEY`).
- **Tavily API Key**: Obtain an API key from Tavily and set it as an environment variable (`TAVILY_API_KEY`).
- **Autogen and Dependencies**: Install the necessary dependencies using `pip install autogen`.

### Steps to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/AI-SupplyChainRiskAssessor.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd AI-SupplyChainRiskAssessor
   ```

3. **Set Environment Variables:**
   ```bash
   export OPENAI_API_KEY='your-openai-api-key'
   export TAVILY_API_KEY='your-tavily-api-key'
   ```
   



