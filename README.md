# Ai Agent with LangChain

This repo contains two Jupyter Notebooks for exploring and creating agents using LangChain.

## Requirements

The project requires the following dependencies:

- `langchain==0.1.20`
- `langchain-community==0.0.38`
- `langchain-groq==0.1.2`
- `python-dotenv`
- `jupyterlab`
- `ddgs`

## Installation

### macOS

To set up the environment on macOS, run the following commands:

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### WindowsOS

To set up the environment on WindowsOS, follow these steps for either PowerShell or Git-Bash CLI:

**PowerShell:**

```powershell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

**Git-Bash:**

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Usage

To run the project, open one of the Jupyter Notebooks:

- [`1_intro_agents.ipynb`](1_intro_agents.ipynb) for an introduction to Agents with LangChain.
- [`2_more_agents.ipynb`](2_more_agents.ipynb) for creating Agents with built-in tools.

Both notebooks require credentials to be loaded from a `.env` file, which should contain the following line:

```
GROQ_API_KEY=your_groq_api_key
```

You can generate a Groq API Key [here](https://console.groq.com/playground).