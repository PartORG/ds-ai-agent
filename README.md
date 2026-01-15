[![Shipping files](https://github.com/neuefische/ds-ai-agent/actions/workflows/workflow-02.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-ai-agent/actions/workflows/workflow-02.yml)
## Ai Agent with LangChain

This repo contains two notebooks:

- [`1_intro_agents.ipynb`](1_intro_agents.ipynb) - Introduction to Agents with LangChain
- [`2_more_agents.ipynb`](2_more_agents.ipynb) - Creating Agents with Built-in Tools

Either notebook requires credentials to be loaded from a `.env` file, which should contain the following lines:

```
GROQ_API_KEY=<your groq api key>
```

- [Groq API Key](https://console.groq.com/playground) can be generated and used free of charge

## Environment

### **`macOS`** type the following commands :

- Install the virtual environment and the required packages by following commands:

  ```BASH
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/bin/activate
  pip install --upgrade pip
  pip install -r requirements.txt
  ```

### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

  For `PowerShell` CLI :

  ```PowerShell
  pyenv local 3.11.3
  python -m venv .venv
  .venv\Scripts\Activate.ps1
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```
  For `Git-Bash` CLI :

  ```
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/Scripts/activate
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```
