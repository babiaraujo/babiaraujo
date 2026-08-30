# Bárbara Araújo

### Senior AI Engineer · Agentic AI and LLM systems in production

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/barbaravivian)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:barbaravivian.araujo@gmail.com)
[![AWS Certified](https://img.shields.io/badge/AWS_Certified-GenAI_Developer-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)](#)

I build LLM agents that run in production and survive contact with real users.

That means multi-agent orchestration, tool calling and function schemas, RAG, prompt and context engineering, evaluation, and the observability and cost control that keep an agent fleet accountable. I got here through data and backend engineering, which is usually what separates an agent that works in a notebook from one that works at scale.

## Problems I work on

A demo agent answers the question. A production agent has to survive everything else.

- **Silent failure.** A tool schema that resolves to nothing, a step prompt that never reaches the model, a turn that dies past a tool-call limit and logs nothing. The dashboard stays green and the user is left waiting.
- **Leakage.** Reasoning traces, tool payloads and internal instructions finding their way into user-facing text, in shapes no sanitizer anticipated.
- **Cost that moves without a deploy.** Prompt duplication, context that grows every turn, thinking tokens billed against the same budget as output. Cost per conversation is a metric, not a footnote.
- **Attribution.** When quality drops, telling apart the model, the prompt, the retrieval, the orchestration and the data underneath, before anyone starts guessing.

Most of this work is measurement first and code second. The fix is usually small once you can prove which of the five layers actually broke.

## Stack

**AI and LLM**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

**Backend**
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)

**Cloud**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)


## Currently exploring

Evaluation harnesses for agents (offline evals, LLM-as-judge, regression suites) · long-horizon memory and context management for multi-turn agents · small and local models for cost-sensitive workloads.
