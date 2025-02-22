# 🦜🕸️ Awesome LangGraph ![Awesome](https://awesome.re/badge.svg)

LangGraph is a framework for building stateful multi-actor applications, modeling steps as graph nodes and edges. It offers interfaces for agent creation and custom flow composition.

> Inspired by [awesome-langchain](https://github.com/kyrolabs/awesome-langchain), this is a curated list of tools and projects using Langchain.![GitHub stars](https://img.shields.io/github/stars/kyrolabs/awesome-langchain)



## LangChain Ecosystem

LangChain simplifies LLM application development with:

- **langchain-core**: Core abstractions
- **langchain**: Chains and agents
- **Integration Packages**: Specific integrations
- **langchain-community**: Third-party integrations

## LangSmith

LangSmith enhances LangGraph with tools for debugging, testing, and monitoring, offering commercial solutions for optimization.

## LangGraph Platform

LangGraph Platform is a commercial solution for deploying agentic applications to production, built on the open-source LangGraph framework.

The LangGraph Platform consists of several components that support development, deployment, debugging, and monitoring:

- **[LangGraph Server](https://langchain-ai.github.io/langgraph/concepts/langgraph_platform/#overview)**: Defines an opinionated API and architecture for deploying agentic applications.
- **LangGraph Studio**: A specialized IDE for visualization, interaction, and debugging.
- **LangGraph CLI**: A command-line interface for interacting with a local LangGraph.
- **Python/JS SDK**: Provides a programmatic way to interact with deployed LangGraph applications.
- **Remote Graph**: Allows interaction with deployed LangGraph applications as if they were running locally.

## LangGraph Templates

- [New LangGraph Project](https://github.com/langchain-ai/new-langgraph-project) - Simple, minimal chatbot with memory. [Python](https://github.com/langchain-ai/new-langgraph-project) | [JavaScript](https://github.com/langchain-ai/new-langgraphjs-project)
- [ReAct Agent](https://github.com/langchain-ai/react-agent) - Agent that can be flexibly extended to many tools. [Python](https://github.com/langchain-ai/react-agent) | [JavaScript](https://github.com/langchain-ai/react-agent-js)
- [Memory Agent](https://github.com/langchain-ai/memory-agent) - ReAct-style agent with cross-thread memory storage. [Python](https://github.com/langchain-ai/memory-agent) | [JavaScript](https://github.com/langchain-ai/memory-agent-js)
- [Retrieval Agent](https://github.com/langchain-ai/retrieval-agent-template) - Agent with retrieval-based QA system. [Python](https://github.com/langchain-ai/retrieval-agent-template) | [JavaScript](https://github.com/langchain-ai/retrieval-agent-template-js)
- [Data-enrichment Agent](https://github.com/langchain-ai/data-enrichment) - Agent for web searches and structured data organization. [Python](https://github.com/langchain-ai/data-enrichment) | [JavaScript](https://github.com/langchain-ai/data-enrichment-js)
- [Full-Stack Python Chatbot with LangGraph](https://github.com/langchain-ai/langgraph-fullstack-python) - This template demonstrates how to build a full-stack chatbot application using LangGraph's HTTP configuration capabilities. It showcases how to combine a React-style agent with a modern web UI, all hosted within a single LangGraph deployment. [Python](https://github.com/langchain-ai/langgraph-fullstack-python)

## Community Agents

### AI Assistants
- [AI-Data-Analysis-MultiAgent](https://github.com/starpig1129/AI-Data-Analysis-MultiAgent) - Advanced multi-agent system for data analysis, visualization, and report generation with innovative Note Taker agent. ![GitHub stars](https://img.shields.io/github/stars/starpig1129/AI-Data-Analysis-MultiAgent)
- [AI Coding Assistant](https://github.com/AbhinavTheDev/coding-agent) - Development tool that uses LangGraph agents to supercharge coding workflow through natural language AI interactions. ![GitHub stars](https://img.shields.io/github/stars/AbhinavTheDev/coding-agent)
- [Brainstormers](https://github.com/Azzedde/brainstormers) - Enhanced brainstorming tool with curated, optimized chains inspired by real-world brainstorming techniques. ![GitHub stars](https://img.shields.io/github/stars/Azzedde/brainstormers)
- [Clevrr Computer](https://github.com/Clevrr-AI/Clevrr-Computer) - Automation agent designed to perform basic computer tasks with safety and accuracy. ![GitHub stars](https://img.shields.io/github/stars/Clevrr-AI/Clevrr-Computer)
- [ContentMind AI](https://github.com/lgesuellip/researcher_agent) - Transform websites into LLM-ready research material with automated documentation indexing. ![GitHub stars](https://img.shields.io/github/stars/lgesuellip/researcher_agent)
- [CopilotMate](https://github.com/AkashJana18/copilotmate) - Personal assistant with intuitive interface using Groq LLM and CopilotKit UI. ![GitHub stars](https://img.shields.io/github/stars/AkashJana18/copilotmate)
- [RD-Agent](https://github.com/microsoft/RD-Agent) - Microsoft's R&D automation tool for data mining, research paper analysis, and model tuning. ![GitHub stars](https://img.shields.io/github/stars/microsoft/RD-Agent)
+ **[Agent Inbox](https://github.com/langchain-ai/agent-inbox)** - Open source Agent Inbox UI for human-in-the-loop LangGraph agents. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/agent-inbox)
+ **[WebRover](https://github.com/hrithikkoduri/WebRover)** - Autonomous AI agent for web task automation and research. ![GitHub stars](https://img.shields.io/github/stars/hrithikkoduri/WebRover)
+ **[langgraph-mcp](https://github.com/esxr/langgraph-mcp)** - Universal Assistant built with LangGraph and Model Context Protocol (MCP). ![GitHub stars](https://img.shields.io/github/stars/esxr/langgraph-mcp)
+ **[LangGraph Multi-Agent Supervisor](https://github.com/langchain-ai/langgraph-supervisor)** - A Python library for creating hierarchical multi-agent systems using LangGraph. Hierarchical systems are a type of multi-agent architecture where specialized agents are coordinated by a central supervisor agent. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-supervisor)

### Content & Media
- [AgentWrite](https://github.com/denser-org/denser-chat) - Automated content generation tool breaking down complex writing tasks into manageable steps. ![GitHub stars](https://img.shields.io/github/stars/denser-org/denser-chat)
- [Podcastfy.ai](https://github.com/souzatharsis/podcastfy) - Transform multi-modal content into engaging, multi-lingual audio conversations using GenAI. ![GitHub stars](https://img.shields.io/github/stars/souzatharsis/podcastfy)
- [Robo-blogger](https://github.com/langchain-ai/robo-blogger) - Voice-to-content pipeline for converting spoken thoughts into structured blog content. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/robo-blogger)
- [Social Media Agent](https://github.com/langchain-ai/social-media-agent) - Generate Twitter & LinkedIn posts from URLs with human-in-the-loop workflow. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/social-media-agent)

### Development & Tools
- [AI Agent Service Toolkit](https://github.com/JoshuaC215/agent-service-toolkit) - Framework for simplifying AI agent deployment with FastAPI and Streamlit. ![GitHub stars](https://img.shields.io/github/stars/JoshuaC215/agent-service-toolkit)
- [Browser Use: Web AI](https://github.com/browser-use/browser-use) - Library for AI agents to naturally interact with websites and automate web tasks. ![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use)
- [Khoj](https://github.com/khoj-ai/khoj) - Self-hostable AI second brain for answers from web or docs with custom agents. ![GitHub stars](https://img.shields.io/github/stars/khoj-ai/khoj)
+ **[Hyperbolic-AgentKit](https://github.com/HyperbolicLabs/Hyperbolic-AgentKit)** - AI agent framework with blockchain and compute capabilities. ![GitHub stars](https://img.shields.io/github/stars/HyperbolicLabs/Hyperbolic-AgentKit)
+ **[Agent Protocol](https://github.com/langchain-ai/agent-protocol)** - Agent Protocol is our attempt at codifying the framework-agnostic APIs that are needed to serve LLM agents in production. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/agent-protocol)

### Finance & Business
- [AI Case Study Analyzer](https://github.com/muratcankoylan/AI-Investigator) - Discovers and analyzes enterprise AI case studies using Claude 3.5 Sonnet. ![GitHub stars](https://img.shields.io/github/stars/muratcankoylan/AI-Investigator)
- [AI Hedge Fund](https://github.com/virattt/ai-hedge-fund) - Six AI agents collaborating through LangChain for smart trading decisions. ![GitHub stars](https://img.shields.io/github/stars/virattt/ai-hedge-fund)
- [gotoHuman Lead Agent](https://github.com/gotohuman/gotohuman-langgraph-lead-example) - AI-powered sales solution for automated personalized email drafting with human oversight. ![GitHub stars](https://img.shields.io/github/stars/gotohuman/gotohuman-langgraph-lead-example)

### Knowledge & Retrieval
- [bRAG](https://github.com/bRAGAI/bRAG-langchain) - Comprehensive RAG tutorial series from basics to advanced implementations. ![GitHub stars](https://img.shields.io/github/stars/bRAGAI/bRAG-langchain)
- [Demo Bank Support Bot](https://github.com/multinear-demo/demo-bank-support-lc-py) - RAG-powered banking customer support chatbot with hallucination prevention. ![GitHub stars](https://img.shields.io/github/stars/multinear-demo/demo-bank-support-lc-py)
- [Denser Chat](https://github.com/denser-org/denser-chat) - Chatbot for answering questions from PDFs and webpages with text extraction capabilities. ![GitHub stars](https://img.shields.io/github/stars/denser-org/denser-chat)
- [IdentityRAG Insights](https://github.com/tilotech/identity-rag-customer-insights-chatbot) - Chatbot unifying customer data into "golden records" for context-aware responses. ![GitHub stars](https://img.shields.io/github/stars/tilotech/identity-rag-customer-insights-chatbot)
- [Reply gAI](https://github.com/langchain-ai/reply_gAI) - AI clone for X/Twitter profiles using long-term memory and RAG for personalized responses. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/reply_gAI)
+ **[RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques)** - Advanced RAG tutorials enhancing accuracy and efficiency. ![GitHub stars](https://img.shields.io/github/stars/NirDiamant/RAG_Techniques)
+ **[r1-reasoning-rag](https://github.com/deansaco/r1-reasoning-rag/)** - Recursive RAG system using r1 reasoning for comprehensive question answering. ![GitHub stars](https://img.shields.io/github/stars/deansaco/r1-reasoning-rag/)

### Sustainability
- [GreenMe](https://github.com/vivek-suryavanshi/GreenMeGenAIApp) - AI-powered sustainability guide analyzing lifestyle for carbon footprint reduction. ![GitHub stars](https://img.shields.io/github/stars/vivek-suryavanshi/GreenMeGenAIApp)

## Tools

- **[Gen AI Toolbox for Databases](https://github.com/googleapis/genai-toolbox)** - A public beta tool server for database tools, enabling agents to easily call these tools. Excited to partner with Google on this launch! Special thanks to Hamsa Buvaraghan, Kurtis Van Gent, and the team!

--- 

## Learning

- [Introduction to LangGraph](https://academy.langchain.com/courses/intro-to-langgraph) - Comprehensive course to get started with LangGraph, covering fundamental concepts, workflows, and practical use cases.

---

## 🤝 Contributing

Found an awesome LangGraph project? We'd love to see it! Feel free to open a pull request to add new projects to this list. Whether it's a tool, application, or innovative use case, if it's built with LangGraph, it belongs here.

Remember to:
- Check if the project isn't already listed
- Make sure it's actively maintained
- Add a concise description of what makes it awesome

