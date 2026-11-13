# Hi, I'm Alexey 👋

I build **AI-powered automations for business processes**. My focus is on reducing manual work, such as copying information between systems, checking multiple data sources, and turning raw data into structured reports.

I use low-code tools like n8n and Albato for straightforward integrations and write Python when a workflow needs custom logic or a dedicated backend. I combine both approaches when that makes the workflow easier to maintain.

I also build data pipelines with Python and Apache Spark, work with analytical data in ClickHouse, and create dashboards in Apache Superset and Power BI.

## Featured project

### [alex_k_org_info](https://github.com/alalexkrr/alex_k_org_info)

`org_info` is a Telegram bot that brings together information about a company or sole proprietor from multiple sources. Enter a Russian taxpayer ID (INN) to get a structured report without looking up each source separately.

I built the Python backend to collect data from external APIs, run rule-based checks, and generate a report with an LLM. The checks run in code, so the model summarizes the findings without deciding the results. The backend limits the data sent to the model, retrieves relevant reference material through Qdrant, validates the model's structured output, and can fall back to another LLM provider.

## Tech stack

- **Workflow automation:** n8n, Albato
- **Backend and integrations:** Python, asyncio, aiogram, httpx, Pydantic, REST APIs
- **LLM and RAG:** LLM integrations, structured outputs, LangChain, Qdrant, FAISS
- **Data engineering:** SQL, Hadoop (HDFS), Apache Spark (PySpark)
- **Databases:** ClickHouse, PostgreSQL, Oracle, SQLite
- **Data analytics and BI:** Apache Superset, Power BI
- **Development and deployment:** Git, Docker, Docker Compose, Linux

## Beyond my projects

I run LLMs locally with Ollama and LM Studio. I like comparing how different models run on my own hardware, especially the trade-offs between speed, memory use, and response quality.
I'm also learning about model training and fine-tuning, with an interest in PyTorch and TensorFlow.
