# Cloud-Based Intelligent Resource Allocation System for Campus Facilities

A multi-agent AI system that simulates a virtual software development team 
to automatically generate Waterfall and Scrum project plans using LLMs.

## Project Overview
Built as part of the Software Project Management (CS587) course at 
Illinois Institute of Technology. The system uses collaborative AI agents 
to automate software project planning for a campus facility booking platform 
supporting 5,000+ concurrent users.

## Multi-Agent Architecture
- **Customer Proxy Agent** — submits the project problem statement
- **Project Manager Agent** — delegates tasks to specialist agents
- **Requirements Engineer Agent** — generates use-cases, requirements, and estimates

## Experiments
| Experiment | Framework | LLM Used |
|-----------|-----------|----------|
| Exp1 | AutoGen | GPT-4.1 mini |
| Exp2 | LangChain | Claude Sonnet (Anthropic) |
| Exp3 | Ollama | Llama 3 (local) |

## Tech Stack
- AutoGen, LangChain, Ollama
- Anthropic Claude Sonnet API, OpenAI API, Llama 3
- Python, Jupyter Notebook
- RAG-style context injection and prompt engineering

## My Contribution
- Implemented **Experiment 3** using Ollama and Llama 3 as a local LLM backend
- Set up Ollama environment and configured Llama 3 for multi-agent communication
- Generated and evaluated Scrum project plans including sprint backlogs, 
  story point estimates, and role-based agent outputs

## Team
Built collaboratively as part of Illinois Tech MCS program

## How to Run
```bash
# Install dependencies
pip install langchain langchain-anthropic autogen ollama

# Pull Llama 3 model (for Exp3)
ollama pull llama3

# Open notebooks in Jupyter
jupyter notebook
```

## Author
Nithishkannan Kuppal Thulasiraman | MCS @ Illinois Tech
