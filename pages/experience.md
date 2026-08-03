# 👨‍💻 Experience

**Software Engineer Intern** @ [Amazon Web Services (AWS)](https://aws.amazon.com/) _(Jun. 2026 – Sept. 2026)_, Cupertino, CA

Designing and building Helion, a serverless AWS service automating firmware recovery for lab hardware.
- Detailed achievements:
  - Designed and built Helion, a serverless AWS service automating firmware recovery for lab hardware, replacing a ~6-hour manual process with a single API call for 5+ hardware engineering teams.
  - Architected a 4-layer system with 5 secured REST APIs across 3 lab hardware environments, backed by 6 DynamoDB tables designed to sustain 10,000 writes/sec peak load.
  - Cut hardware recovery to a sub-5s go/no-go decision and a ~2-4 hour fully automated restore with zero manual intervention, via serverless compute auto-scaling to 1,000 concurrent functions.
  - Owned full AWS infrastructure as code (CDK) across 4 environments, including private networking, least-privilege IAM, encryption at rest, and CloudWatch monitoring/alarms.
- _**Technologies used:**_ AWS Lambda, DynamoDB, CDK, IAM, CloudWatch, Serverless

&nbsp;

**Software Engineer Intern** @ [Amazon Web Services (AWS)](https://aws.amazon.com/) _(Jun. 2025 – Sept. 2025)_, Santa Clara, CA

Built a serverless monitoring system for AWS Bedrock to keep production LLMs within benchmark and catch regressions automatically.
- Detailed achievements:
  - Developed a serverless monitoring system for AWS Bedrock, orchestrating end-to-end Lambda + Step Functions workflows keeping LLMs within 10% of industry benchmarks and eliminating manual testing by 100%.
  - Performed ETL in AWS Glue, partitioning logs and enabling sub-second Athena SQL queries across 100K+ records.
  - Automated regression detection with CloudWatch alerts and hypothesis tests, and enabled real-time dashboards for p99 latency, BLEU, and error-rate, cutting detection time by 90%.
  - Prototyped MCP-style connectors for AWS Bedrock Flows, a visual orchestration tool for multi-step AI workflows, enabling external API integration with execution handled by Lambda + Step Functions and packaged in Docker.
- _**Technologies used:**_ AWS Bedrock, Lambda, Step Functions, Glue, Athena, CloudWatch, Docker

&nbsp;

**AI Engineering Intern** @ Chelle AI _(Jan. 2025 – Jun. 2025)_, Los Angeles, CA

Benchmarked and fine-tuned LLMs to power an AI education platform.
- Detailed achievements:
  - Benchmarked 10+ local and API-based LLMs with NLP metrics to select models that powered an AI education platform, improving content accuracy by 30%.
  - Developed and trained a neural network using the REINFORCE algorithm in PyTorch, applying Bayesian Optimization for hyperparameters to fine-tune LLM prompt outputs, raising performance by 25% on BLEU and task success metrics.
  - Integrated Hugging Face + PyTorch pipelines to automate evaluation, reducing iteration time by 40% across 100+ experiments.
- _**Technologies used:**_ PyTorch, Hugging Face, REINFORCE, Bayesian Optimization, LLMs

&nbsp;

**AI/ML Intern** @ [interactly.ai](https://www.interactly.ai/) _(Jun. 2024 – Sept. 2024)_, Milpitas, CA

Built and fine-tuned custom small language models tailored to client-specific needs across industries.
- Detailed achievements:
  - Built and fine-tuned 10+ SLMs (Small Language Models) using PyTorch + Hugging Face and 1M+ generated synthetic datapoints, improving accuracy by 30% for client apps in healthcare, finance, and support.
  - Built vector databases (FAISS) to support retrieval-augmented generation and domain-specific knowledge grounding.
- _**Technologies used:**_ Python, PyTorch, Hugging Face, FAISS, RAG

&nbsp;

**Undergraduate Research Assistant** @ UCLA Trustworthy AI Lab _(Dec. 2024 – Present)_, Los Angeles, CA

Researching adversarial robustness and failure attribution in LLM agents.
- Detailed achievements:
  - Engineered a Dockerized Python testbed with FastAPI + SQL to run 500+ reproducible jailbreak evaluations.
  - Designed modular multi-agent workflows with roles in LangChain + REST, enabling testing in 4+ scenarios.
  - Developed a Divide-and-Conquer jailbreak with 24% higher success rates on GPT-4.1, Claude 3.5, and Gemini 2.0.
- _**Technologies used:**_ Python, FastAPI, Docker, LangChain, SQL
