# Advanced AI Agents

**A curated collection of production-ready AI agent applications built with modern frameworks (Phidata, CrewAI, LangChain, Google ADK, Anthropic, OpenAI) showcasing single agents, multi-agent teams, and autonomous game-playing systems.**

[![Python](https://img.shields.io/badge/Python-57%25-3776AB?style=flat-square&logo=python)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-34%25-F7DF1E?style=flat-square&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TypeScript](https://img.shields.io/badge/TypeScript-8%25-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![GitHub Stars](https://img.shields.io/github/stars/fiv3fingers/Advanced-AI-Agents?style=flat-square)](https://github.com/fiv3fingers/Advanced-AI-Agents/stargazers)

---

## Table of Contents

- [Overview](#overview)
- [What Are Advanced AI Agents?](#what-are-advanced-ai-agents)
- [Repository Structure](#repository-structure)
- [Featured Agent Categories](#featured-agent-categories)
  - [Single Agent Applications](#single-agent-applications)
  - [Multi-Agent Systems](#multi-agent-systems)
  - [Autonomous Game-Playing Agents](#autonomous-game-playing-agents)
- [Technology Stack](#technology-stack)
- [Prerequisites](#prerequisites)
- [Installation & Quick Start](#installation--quick-start)
- [Use Cases & Applications](#use-cases--applications)
- [Architecture Patterns](#architecture-patterns)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [License](#license)
- [Resources & Further Learning](#resources--further-learning)

---

## Overview

The **Advanced AI Agents** repository is a comprehensive collection of intelligent, autonomous AI systems that demonstrate the cutting edge of agentic AI development. These applications move beyond simple chatbots and showcase how Large Language Models (LLMs) can be equipped with tools, reasoning capabilities, memory, and multi-agent collaboration to solve complex, real-world problems autonomously.

This repository features agents built with:
- **OpenAI GPT-4** / **GPT-4o** / **o1** models
- **Anthropic Claude** (Claude 3.5 Sonnet, Claude 4)
- **Google Gemini** (Gemini Pro, Gemini 1.5, Gemini 2.0)
- **DeepSeek R1** (reasoning-optimized models)
- **xAI Grok**
- **Open-source models** (Llama, Qwen, Mistral) for local deployment

Each agent application includes:
- Complete, runnable code with minimal setup
- Detailed documentation and usage examples
- Real-world problem-solving scenarios
- Production-ready patterns and best practices

---

## What Are Advanced AI Agents?

**AI Agents** are autonomous systems that can:

1. **Perceive** their environment (via APIs, databases, web scraping, file systems)
2. **Reason** about tasks using LLMs with advanced prompting techniques
3. **Act** using tools (APIs, code execution, web browsers, databases)
4. **Learn** from feedback and past interactions (memory, self-improvement)
5. **Collaborate** with other agents in multi-agent workflows

### Why "Advanced"?

Unlike basic chatbots or single-turn LLM calls, these agents demonstrate:
- **Tool use** — calling external APIs, executing Python code, querying databases
- **Multi-step reasoning** — chain-of-thought, planning, reflection
- **Persistent memory** — conversation history, knowledge accumulation
- **Agentic workflows** — autonomous task decomposition and execution
- **Multi-agent orchestration** — specialized agents working together
- **Self-evolution** — agents that improve their own prompts and workflows

---

## Repository Structure

```
Advanced-AI-Agents/
├── single_agent_apps/          # Standalone AI agents solving specific tasks
│   ├── ai_deep_research_agent/         # Multi-source web research agent
│   ├── ai_consultant_agent/            # Business strategy consultant
│   ├── ai_system_architect_r1/         # Software architecture design agent
│   ├── ai_investment_agent/            # Stock analysis and comparison
│   ├── ai_journalist_agent/            # News gathering and article generation
│   ├── ai_meeting_agent/               # Meeting preparation and intelligence
│   ├── ai_health_fitness_agent/        # Personalized health and fitness coach
│   └── ai_movie_production_agent/      # End-to-end film production workflow
│
├── multi_agent_apps/           # Multi-agent systems and agent teams
│   ├── agent_teams/                    # Specialized multi-agent teams
│   │   ├── ai_legal_agent_team/        # Contract analysis and legal advice
│   │   ├── ai_finance_agent_team/      # Financial analysis and planning
│   │   ├── ai_recruitment_agent_team/  # Candidate sourcing and screening
│   │   ├── ai_teaching_agent_team/     # Personalized education system
│   │   ├── multimodal_coding_agent_team/     # Code generation from images/specs
│   │   └── multimodal_design_agent_team/     # UI/UX design from descriptions
│   │
│   ├── ai_financial_coach_agent/       # Personal finance management
│   ├── ai_mental_wellbeing_agent/      # Mental health support system
│   ├── ai_news_and_podcast_agents/     # Content creation pipeline
│   ├── ai_Self-Evolving_agent/         # Agent that optimizes itself
│   └── product_launch_intelligence_agent/ # Market analysis for product launches
│
└── autonomous_game_playing_agent_apps/ # Agents that play games autonomously
    ├── ai_3dpygame_r1/                 # 3D game navigation and strategy
    ├── ai_chess_agent/                 # Chess playing with reasoning
    └── ai_tic_tac_toe_agent/           # Tic-tac-toe strategy agent
```

---

## Featured Agent Categories

### Single Agent Applications

These agents operate independently to solve focused, domain-specific problems.

| Agent | Description | Framework | Key Features |
|-------|-------------|-----------|--------------|
| **Deep Research Agent** | Conducts comprehensive web research across multiple sources and synthesizes findings into detailed reports | Phidata + Firecrawl | Multi-source aggregation, citation tracking, depth enhancement |
| **Business Consultant** | Provides strategic business analysis with real-time market data and competitive intelligence | Google ADK + Perplexity | Market analysis, risk assessment, strategic recommendations |
| **System Architect** | Generates software architecture proposals with technology stack recommendations | Agno + DeepSeek R1 + Claude | Dual-model reasoning, implementation roadmaps, technical specs |
| **Investment Analyst** | Compares stock performance and generates investment insights using live financial data | Phidata + Yahoo Finance | Real-time data, comparative analysis, risk metrics |
| **AI Journalist** | Researches topics and writes publication-ready articles with citations | CrewAI + Serper | Multi-stage workflow, fact-checking, editorial polish |
| **Meeting Intelligence** | Prepares comprehensive briefings for meetings with participant research and talking points | Phidata + Claude | Background research, agenda preparation, key insights |
| **Health & Fitness Coach** | Creates personalized workout and nutrition plans based on user goals and constraints | Phidata + OpenAI | Goal tracking, plan adaptation, progress monitoring |
| **Movie Production Agent** | Manages end-to-end film production workflow from script to post-production planning | CrewAI | Multi-stage pipeline, resource allocation, timeline management |

### Multi-Agent Systems

Collaborative teams of specialized agents working together to solve complex problems.

| Team | Description | Agents | Orchestration |
|------|-------------|--------|---------------|
| **Legal Agent Team** | Analyzes contracts, identifies risks, and provides legal recommendations | Document Analyst, Risk Assessor, Compliance Checker | CrewAI sequential workflow |
| **Finance Agent Team** | Comprehensive financial planning with budgeting, investment, and tax strategies | Budget Analyst, Investment Advisor, Tax Specialist | Phidata hierarchical coordination |
| **Recruitment Team** | End-to-end hiring pipeline from job description to candidate recommendations | JD Writer, Sourcer, Screener, Interviewer | CrewAI task delegation |
| **Teaching Agent Team** | Personalized education with curriculum planning, tutoring, and assessment | Curriculum Designer, Subject Tutor, Assessment Creator | Multi-agent collaboration |
| **Coding Agent Team** | Generates production-ready code from specifications, wireframes, or screenshots | Requirements Analyst, Code Generator, Reviewer, Documenter | Phidata + vision models |
| **Design Agent Team** | Creates UI/UX designs from natural language descriptions | UX Researcher, UI Designer, Accessibility Auditor | Multimodal processing |
| **Financial Coach** | Personal finance management with expense tracking and savings optimization | Expense Analyzer, Budget Optimizer, Debt Strategist | Google ADK coordination |
| **Self-Evolving Agent** | Meta-agent that optimizes other agents' prompts and workflows automatically | Workflow Analyzer, Prompt Optimizer, Performance Evaluator | EvoAgentX framework |

### Autonomous Game-Playing Agents

Agents that learn and execute game strategies without human intervention.

| Agent | Game Type | Strategy | Model |
|-------|-----------|----------|-------|
| **3D Pygame Agent** | 3D navigation and strategy | Spatial reasoning, pathfinding, goal optimization | DeepSeek R1 |
| **Chess Agent** | Classical chess | Opening theory, tactical analysis, endgame strategy | GPT-4o + chess engines |
| **Tic-Tac-Toe Agent** | Classic board game | Minimax strategy, pattern recognition | GPT-4 + game tree search |

---

## Technology Stack

### AI Frameworks & Orchestration
- **[Phidata](https://www.phidata.com/)** — Production-ready agent framework with tool integration
- **[CrewAI](https://www.crewai.com/)** — Multi-agent orchestration and role-playing agents
- **[LangChain](https://www.langchain.com/)** — LLM application development framework
- **[Google ADK (Agent Development Kit)](https://ai.google.dev/adk)** — Google's agent building platform
- **[Agno](https://agno.dev/)** — Agentic AI application framework
- **[EvoAgentX](https://github.com/JinSeoung-Oh/EvoAgentX)** — Self-evolving agent optimization framework

### LLM Providers
- **OpenAI** (GPT-4, GPT-4o, o1-preview, o1-mini)
- **Anthropic** (Claude 3.5 Sonnet, Claude 4)
- **Google** (Gemini Pro, Gemini 1.5, Gemini 2.0)
- **DeepSeek** (DeepSeek R1, DeepSeek Chat)
- **xAI** (Grok-1, Grok-2)
- **Perplexity AI** (real-time web search)
- **Open Source** (Llama, Qwen, Mistral via Ollama)

### Tools & Integrations
- **Web Search & Scraping**: Serper, DuckDuckGo, Firecrawl, Newspaper4k
- **Data Sources**: Yahoo Finance, ArXiv, GitHub API, Gmail API
- **Development**: Streamlit (UI), FastAPI (backend), Poetry/pip (dependency management)
- **Databases**: PostgreSQL, SQLite, Vector DBs (Pinecone, Weaviate)
- **Voice**: ElevenLabs, OpenAI TTS, Whisper

---

## Prerequisites

- **Python 3.10+** (most agents use Python)
- **Node.js 18+** (for JavaScript/TypeScript agents)
- **API Keys** for LLM providers (OpenAI, Anthropic, Google, etc.)
- **Optional**: Docker (for containerized deployment)
- **Optional**: PostgreSQL (for database-backed agents)

---

## Installation & Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/fiv3fingers/Advanced-AI-Agents.git
cd Advanced-AI-Agents
```

### 2. Choose an Agent Application

Navigate to any agent directory:

```bash
cd single_agent_apps/ai_deep_research_agent
```

### 3. Install Dependencies

Most agents include a `requirements.txt`:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file:

```bash
cp .env.example .env  # If example exists
# Or create manually:
```

```env
# Example .env file
OPENAI_API_KEY=sk-...
ANTHROPIC_API_KEY=sk-ant-...
GOOGLE_API_KEY=...
FIRECRAWL_API_KEY=...  # For research agents
SERPER_API_KEY=...      # For web search
```

### 5. Run the Agent

```bash
# For Streamlit apps
streamlit run app.py

# For CLI agents
python main.py

# For FastAPI backends
uvicorn main:app --reload
```

### 6. Access the Interface

- **Streamlit**: Opens automatically at `http://localhost:8501`
- **FastAPI**: API docs at `http://localhost:8000/docs`
- **CLI**: Follow terminal instructions

---

## Use Cases & Applications

### Business & Enterprise
- **Strategic Planning** — Business consultant agent provides market analysis and competitive intelligence
- **Legal Operations** — Contract review, compliance checking, risk assessment (Legal Agent Team)
- **Financial Planning** — Personal finance coaching, investment analysis, budget optimization
- **Recruitment** — Automated candidate sourcing, resume screening, interview scheduling

### Software Development
- **System Design** — Architecture proposals, technology stack recommendations
- **Code Generation** — Multi-modal coding from specs, wireframes, or natural language
- **Documentation** — Automated technical writing and API documentation

### Research & Analysis
- **Deep Research** — Multi-source web research with citation tracking
- **Market Intelligence** — Product launch analysis, competitor monitoring
- **Investment Research** — Stock analysis, portfolio recommendations

### Content Creation
- **Journalism** — News gathering, article writing, fact-checking
- **Podcasts** — Script generation, audio production workflows
- **Film Production** — End-to-end production planning and resource management

### Personal Productivity
- **Meeting Preparation** — Briefing generation, participant research
- **Health & Fitness** — Personalized workout and nutrition planning
- **Mental Wellbeing** — Therapeutic conversation and coping strategy suggestions

### Education & Training
- **Personalized Tutoring** — Adaptive curriculum, subject-specific teaching
- **Assessment** — Quiz generation, performance tracking

### Gaming & Entertainment
- **Game AI** — Autonomous game-playing agents with strategic reasoning
- **Game Design** — Automated game concept development and mechanics design

---

## Architecture Patterns

### 1. Single-Agent Architecture (ReAct Pattern)

```
┌──────────────────────────────────────────────────┐
│              User Input / Query                  │
└─────────────────┬────────────────────────────────┘
                  │
                  ▼
┌──────────────────────────────────────────────────┐
│           LLM Agent (ReAct Loop)                 │
│  ┌────────────────────────────────────────────┐ │
│  │  Reasoning: Think about the task           │ │
│  │  Action: Choose tool to use                │ │
│  │  Observation: Process tool result          │ │
│  │  (Repeat until task complete)              │ │
│  └────────────────────────────────────────────┘ │
└─────────────────┬────────────────────────────────┘
                  │
         ┌────────┴────────┐
         │                 │
         ▼                 ▼
    ┌────────┐      ┌─────────────┐
    │ Tools  │      │   Memory    │
    │ (APIs, │      │ (Context,   │
    │  Code) │      │  History)   │
    └────────┘      └─────────────┘
         │                 │
         └────────┬────────┘
                  ▼
          ┌───────────────┐
          │ Final Output  │
          └───────────────┘
```

### 2. Multi-Agent Architecture (Hierarchical)

```
┌──────────────────────────────────────────────────┐
│            Manager Agent (Orchestrator)          │
│  - Task decomposition                            │
│  - Agent selection & routing                     │
│  - Result synthesis                              │
└─────────────────┬────────────────────────────────┘
                  │
        ┌─────────┼─────────┐
        │         │         │
        ▼         ▼         ▼
   ┌────────┐ ┌────────┐ ┌────────┐
   │Agent 1 │ │Agent 2 │ │Agent 3 │
   │(Expert)│ │(Expert)│ │(Expert)│
   └───┬────┘ └───┬────┘ └───┬────┘
       │          │          │
       │   ┌──────┴──────┐   │
       │   │             │   │
       ▼   ▼             ▼   ▼
   ┌────────────────────────────┐
   │   Shared Memory / Context  │
   └────────────────────────────┘
                  │
                  ▼
          ┌───────────────┐
          │ Final Output  │
          └───────────────┘
```

### 3. Self-Evolving Architecture

```
┌──────────────────────────────────────────────────┐
│           Performance Monitoring Layer           │
│  - Task success rate                             │
│  - Response quality metrics                      │
│  - User feedback collection                      │
└─────────────────┬────────────────────────────────┘
                  │
                  ▼
┌──────────────────────────────────────────────────┐
│        Optimization Agent (Meta-Agent)           │
│  - Analyze performance data                      │
│  - Generate improved prompts                     │
│  - Propose workflow changes                      │
└─────────────────┬────────────────────────────────┘
                  │
                  ▼
┌──────────────────────────────────────────────────┐
│            Validation & A/B Testing              │
│  - Compare old vs. new versions                  │
│  - Benchmark on test cases                       │
│  - Deploy if performance improves                │
└─────────────────┬────────────────────────────────┘
                  │
                  ▼
┌──────────────────────────────────────────────────┐
│        Updated Production Agent                  │
└──────────────────────────────────────────────────┘
```

---

## Contributing

Contributions are welcome! This repository thrives on community collaboration. Here's how you can help:

### Ways to Contribute

1. **Add New Agents** — Build and submit new agent applications
2. **Improve Existing Agents** — Enhance functionality, add features, fix bugs
3. **Documentation** — Improve README files, add tutorials, create guides
4. **Bug Reports** — Open issues for problems you encounter
5. **Feature Requests** — Suggest new agent types or capabilities

### Contribution Guidelines

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-agent`
3. Follow the existing project structure
4. Include a detailed `README.md` in your agent directory
5. Add a `requirements.txt` with all dependencies
6. Include example `.env` configuration
7. Test thoroughly before submitting
8. Submit a pull request with clear description

### Code Standards

- **Python**: Follow PEP 8 style guide
- **JavaScript/TypeScript**: Follow Airbnb style guide
- **Documentation**: Clear, concise, with examples
- **Dependencies**: Pin versions in `requirements.txt`
- **Security**: Never commit API keys or secret.

---

## Resources & Further Learning

### Official Framework Documentation
- [Phidata Documentation](https://docs.phidata.com/)
- [CrewAI Documentation](https://docs.crewai.com/)
- [LangChain Documentation](https://python.langchain.com/)
- [Google ADK Documentation](https://ai.google.dev/adk)

### Learn More About AI Agents
- [The Unwind AI Blog](https://www.theunwindai.com) — AI agent tutorials and insights
- [OpenAI Agents Guide](https://platform.openai.com/docs/guides/agents)
- [Anthropic Claude Documentation](https://docs.anthropic.com/)
- [LangChain Agent Types](https://python.langchain.com/docs/modules/agents/)

---

## Project Statistics

![GitHub Stats](https://img.shields.io/github/stars/fiv3fingers/Advanced-AI-Agents?style=social)
![Forks](https://img.shields.io/github/forks/fiv3fingers/Advanced-AI-Agents?style=social)
![Issues](https://img.shields.io/github/issues/fiv3fingers/Advanced-AI-Agents)
![Pull Requests](https://img.shields.io/github/issues-pr/fiv3fingers/Advanced-AI-Agents)
![Last Commit](https://img.shields.io/github/last-commit/fiv3fingers/Advanced-AI-Agents)

---

**Start building advanced AI agents today!** 🚀

Explore the agents, experiment with frameworks, and join the growing community of developers building autonomous AI systems.
