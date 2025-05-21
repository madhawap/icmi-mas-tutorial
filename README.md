# Content for Tutorial on Multi Modal Agentic Workflow

> _"Great snakes! A local AI chat agent that knows all about Tintin!"_ - Captain Haddock (probably)

Welcome to this tutorial on developing multi modal agentic workflows. We setup this project in a way that it can completely on your local machine using Ollama, LangChain, and LangGraph.

## Quick Start Guide

### Step 1: Install Ollama

Choose your platform:
- **Windows**: [Download Ollama for Windows](https://ollama.com/download/windows)
- **macOS**: [Download Ollama for Mac](https://ollama.com/download/mac)
- **Linux**: [Download Ollama for Linux](https://ollama.com/download/linux)

After installation, make sure Ollama is running in the background!

### Step 2: Download the Gemma 3 Model

Open a terminal or command prompt and run:

```bash
ollama pull gemma3:latest
```

This might take a few minutes to download (around 5-10GB depending on the model size).

### Step 3: Set Up Your Python Environment

We recommend using a virtual environment:

```bash
# Create a virtual environment (optional but recommended)
python -m venv venv

# Activate it:
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### Step 4: Open and Run the Notebook

1. Open the `local_chat_agent.ipynb` file in Jupyter Notebook or VS Code with Jupyter extension
2. Run the first cell to install required dependencies:
   ```python
   %pip install -r requirements.txt
   ```
3. Run each cell in order (you can use Shift+Enter to run cells)
4. At the end, you'll be able to chat with your very own Tintin expert!

## Example Conversation

```
You: Who is Snowy?
assistant: Snowy is 🔸Tintin🔸’s faithful, intelligent, and incredibly loyal white fox. He’s a vital part of 🔸Tintin🔸’s adventures, often assisting with tracking and providing companionship.
```

## Troubleshooting

>ToDo
