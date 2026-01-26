# N8N Snowflake Agentic AI Workflows
<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/b8918944-5069-4bd4-8d38-47df1b298a26" />

## Overview
**Agentic AI workflows for Snowflake** built using the **n8n Starter Kit**, leveraging **Ollama**, **Qdrant**, and **n8n** to enable intelligent, autonomous, and event-driven data operations on snowflake platform.

The goal of this project is to demonstrate how **Agentic AI patterns** can be applied to Snowflake data platforms to automate data engineering, governance, monitoring, and analytics workflows using open-source AI infrastructure.

---

## What Is Agentic AI?

Agentic AI refers to systems where AI agents can:

* Reason and plan tasks
* Interact with tools and APIs
* Maintain memory and context
* Take autonomous actions based on goals and events

In this repository, AI agents are used to **observe Snowflake events**, **reason over metadata and data**, and **take actions** such as running queries, validating data, optimizing operations, and generating insights.

---

## Architecture

The solution is built on the **n8n Agentic AI Starter Kit** and includes the following core components:

### 1. n8n (Workflow Orchestration)

* Acts as the control plane for workflows
* Orchestrates AI agents, Snowflake operations, and integrations
* Handles triggers (schedule, webhook, events)

### 2. Ollama (Local LLM Runtime)

* Runs open-source large language models locally
* Used for reasoning, planning, SQL generation, and analysis
* Enables secure, offline-friendly AI execution

### 3. Qdrant (Vector Database)

* Stores embeddings for:

  * Snowflake metadata
  * Past conversations and agent memory
  * Query context and documentation
* Enables semantic search and long-term memory for agents

### 4. Snowflake

* Cloud data platform used for:

  * Data storage and analytics
  * Metadata inspection
  * Query execution and optimization

---

## Key Capabilities

* 🤖 **Agentic AI for Snowflake Operations**
* 🧠 **LLM-powered SQL generation and validation**
* 📊 **Automated data quality checks**
* 🔍 **Semantic search over Snowflake metadata**
* 🛠️ **Autonomous troubleshooting and recommendations**
* 🔄 **Event-driven and scheduled workflows**

---

## Example Use Cases

* Automated and context aware Snowflake object deployment 
* AI-driven query control and execution
* Natural language to SQL for Snowflake
* Metadata-aware data discovery agents
* AI-assisted incident analysis and root cause detection
* Cost and usage analysis with recommendations

---

## Repository Structure

```text
.
├── N8NWorkflows/              # n8n workflow JSON files
├── Prompts/                   # Custom Prompts used in workflows
├── VectorDBCollections        # Qdrant collections documents
├── Guides/              # Helper documentation
├── Architecture/                   # To be added
├── LICENSE           # Environment variable template
└── README.md
```
