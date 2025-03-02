# Advance CrewAI

Advance CrewAI is a multi-agent orchestration platform that automates complex workflows in project planning, support data analysis, and sales pipeline management. With a modular design, the project leverages AI agents to handle tasks ranging from lead qualification and email engagement to project breakdown and resource estimation.

## Project Overview

This project integrates several core functionalities:
- **Project Planning & Estimation**: Break down project requirements into tasks with detailed timelines and resource allocations.
- **Support Data Insight Analysis**: Analyze support tickets to generate actionable suggestions, tables, charts, and final comprehensive reports.
- **Agentic Sales Pipeline**: An end-to-end sales pipeline that qualifies leads, scores them based on criteria, drafts personalized emails, and triggers follow-up actions.

## Project Structure
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
- **Notebooks**:  
  - `Automated-Project.ipynb`: Handles project planning, estimation, and resource allocation tasks using AI agents.
  - `Support-Data-Insight-Analysis.ipynb`: Analyzes support ticket data and generates visual insights & reports.
  - `Agentic-Sales-Pipeline.ipynb`: Orchestrates lead qualification and email engagement through multiple AI agents.
  
- **Config Directory (`config/`)**:  
  Contains YAML configuration files for agents and tasks related to project planning, lead qualification, email engagement, and support analysis.
  
- **Data Files**:  
  - `support_tickets_data.csv`: Raw support ticket data used for analysis in the support metrics workflow.

## Getting Started

### Prerequisites

- Python 3.12+
- [Crew AI](path/to/crewai) package
- [Langchain OpenAI](path/to/langchain_openai) package
- Other dependencies as listed in your environment (e.g., dotenv, pydantic)

### Installation

1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd Advance-Crewai

2. Create and activate a virtual environment:
    python -m venv .venv
    source .venv/bin/activate  # On Windows use: .venv\Scripts\activate

3. Install the required packages:
    pip install -r requirements.txt

4. Set up your environment variables by creating a .env file. Make sure to include your OPENAI_API_KEY.

### Usage
Run any of the provided Jupyter notebooks in Visual Studio Code to understand the workflow:

* Open Automated-Project.ipynb for project planning and estimation.
* Open Support-Data-Insight-Analysis.ipynb to generate insights from support data.
* Open Agentic-Sales-Pipeline.ipynb to run the sales pipeline workflow.
