# 🤖 hello_agent_01

Welcome to `hello_agent_01` — an intelligent, modular AI agent built using state-of-the-art Python tools.  
This project is part of the **GIAIC Quarter 4 Capstone** and demonstrates real-world AI task delegation.

---

## 🚀 Features

- 🧠 AI Agents using [CrewAI](https://github.com/joaomdmoura/crewAI)
- 🔗 Tool & Task delegation via LangChain
- 🤖 LLM integration (OpenAI, etc.)
- 📦 Modular, extendable architecture
- 🐍 Built with Python

---

## 🏗 Tech Stack

| Tool         | Purpose                  |
|--------------|---------------------------|
| Python       | Core programming language |
| CrewAI       | Multi-agent framework     |
| LangChain    | Agent logic & tools       |
| OpenAI API   | LLM backend               |
| uv           | Dependency management     |

---

## 📁 Project Structure

```bash
hello_agent_01/
├── main.py               # Entry point
├── .env                  # Environment variables
├── .gitignore
├── pyproject.toml        # Dependencies
├── uv.lock               # Locked deps
└── README.md             # You're here!




# Go to project directory
cd GIAIC_Q4_Project/hello_agent_01

# Create virtual environment
uv venv

# Activate (Windows)
.venv\Scripts\activate

# Install dependencies
uv pip install -r uv.lock

# Run the agent
python main.py
