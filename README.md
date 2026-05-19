# Autonomous SRE AI Agent Framework (Advanced Platform Lab)

An implementation of a lightweight, autonomous SRE AI agent designed to integrate with common observability tasks, automate log analysis, and perform predictive incident diagnostics.

## 🚀 Key Architectural Features
*   **Autonomous Log Analysis:** Configured to ingest HTTP streams via log forwarders, leveraging underlying LLMs to detect production anomalies in real-time.
*   **Model Context Protocol (MCP) Integration:** Features a built-in MCP server mapping directly to local Git logs and active Prometheus URLs (`http://localhost:9090`).
*   **Intelligent Tool Selection:** The agent automatically runs `prometheus_query` and traces commit logs to correlate a production error with a recent code change without manual intervention.
*   **Cost Governance:** Integrated Redis-based semantic caching layers, reducing repetitive LLM API consumption costs by 40-70%.

## 🛠️ Tech Stack
*   **Framework Architecture:** SRE Autonomous Agents, Model Context Protocol (MCP)
*   **Observability Core:** Prometheus, Git Core API, Log forwarders (Fluentd/Vector)
*   **Performance Optimization:** Redis Semantic Caching

*Deployed and optimized as a modern AI-DevOps showcase during advanced SRE PoC.*
