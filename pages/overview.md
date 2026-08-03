
# Hi, I'm Sahil Nale 👋

I'm a passionate developer and researcher currently studying at the University of California, Los Angeles, pursuing a Bachelor of Science in Computer Science. I have a strong interest in machine learning, natural language processing, Large Language Models and building impactful software solutions.

# 🧪 Projects

### [Distributed LLM Inference Server](https://github.com/sahilnale/distributed-llm-inference-server) 🔗
A production-style LLM serving stack for Mistral-7B — FastAPI batching API, Redis request queue, and Prometheus/Grafana monitoring, all running on a custom distributed inference engine. Implemented four progressively better GPU tensor-parallelism strategies from scratch (Megatron-style MLP + attention head splitting across 2x V100 GPUs with NCCL/NVLink), taking throughput from a 0.64x regression to a 1.05x speedup over a single GPU.

**Technologies:** Python, PyTorch, FastAPI, NCCL, Redis, Docker, Prometheus, Grafana

### [Black-Scholes Pricing Model](https://sahilnale-black-scholes-option-pricing-streamlit-app-mvr2xe.streamlit.app/)
This repository provides an interactive Black-Scholes Pricing Model dashboard that helps in visualizing option prices under varying conditions. The dashboard is designed to be user-friendly and interactive, allowing users to explore how changes in spot price, volatility, and other parameters influence the value of options.

**Technologies:** Streamlist, numpy, yfinance, matplotlib

### [TradeWhiz](https://github.com/sahilnale/TradeWhiz)
TradeWhiz allows users to simulate stock trading in a risk-free environment. It provides real-time stock data, market sentiment analysis, and helps users make informed trading decisions and practice their strategies without financial risk.

**Technologies:** React, Flask, MongoDB, NLTK, BeautifulSoup, AWS EC2

### [FindMyFood](https://github.com/sahilnale/FindMyFood) 🔗
FindMyFood is a full-stack iOS application to manage and share restaurant visits. It leverages Swift for the front-end, Firebase for user authentication, and MongoDB for data storage. AWS S3 is used for efficient storage and retrieval of user profile images and post photos.

**Technologies:** SwiftUI, Firebase, MapKit, MongoDB, AWS S3

### [react-vscode-portfolio](https://sahil.github.io) 🔗
- A VS Code inspired portfolio project
- Responsive Web Design 
- React, TypeScript

### [Uber Fare Prediction](https://github.com/sahilnale/FindMyFood) 🔗
This project aims to predict the fare of Uber rides in New York City using various machine learning algorithms. It involves data preprocessing, feature engineering, and model evaluation to build a reliable fare prediction model. Gradient Boosting and XGBoost models were used, achieving an R² score of 0.85 and 0.87 respectively.

**Technologies:** Python, Jupyter Notebook, pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost

### [RickGPT](https://github.com/sahilnale/RickGPT/blob/main/GPTRick.ipynb) 🔗
Developed a chatbot using Transformers and fine-tuning Microsoft’s DialoGPT to emulate Rick Sanchez’s personality from the TV show “Rick and Morty,” achieving 85% response relevance on NLP metrics such as BLEU and METEOR. Processed over 1000 unique dialogue inputs, optimizing the model for realistic conversational responses.

**Technologies:** Python, Pytorch, DialoGPT, Transformers, Hugging Face

### [Custom Tweet Sentiment Analysis Transformer](https://github.com/sahilnale/twitter_sentiment/blob/main/sentiment_analysis.ipynb) 🔗
Developed a sentiment analysis BERT-like transformer model, achieving 90% accuracy and F1 score of 0.90 on the test data. Optimized transformer model performance, reducing evaluation loss to 0.25, with 89% precision and 91% recall.

**Technologies:** Python, PyTorch, scikit-learn, Pandas, Hugging Face

### [Los Angeles Crime Analysis](https://github.com/sahilnale/la-crime-analysis) 🔗
Conducted analysis on over 1 million LA crime data points from the past three years, using statistical methods such as random tree forests, hypothesis testing, and bootstrapping with 95% confidence to analyze patterns and trends in crime. Created a Tableau Dashboard providing visual insights into LA crime, summarizing timings, areas, and victim demographics.

**Technologies:** R, SQL, Tableau, RStudio


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


## Technical Skills

**Languages:** Python, Java, C++, JavaScript, TypeScript, SQL (PostgreSQL), HTML/CSS, R, Swift  
**Frameworks:** React.js, Node.js, Flask, Express.js, Django, MongoDB, SwiftUI, Firebase, Next.js  
**Developer Tools:** Git, Docker, AWS, VS Code, Xcode, RStudio, Eclipse, Figma, Postman, Jupyter, GDB, Vercel  
**Libraries:** pandas, NumPy, Matplotlib, scikit-learn, TensorFlow, PyTorch, Seaborn, NLTK, Hugging Face, LangChain

## Connect with Me
- [LinkedIn](https://www.linkedin.com/in/sahil-nale-158813205/)
- [GitHub](https://github.com/sahilnale)
- [Email](mailto:sahilnale@ucla.edu)

---

Thank you for visiting my GitHub profile! Feel free to explore my repositories and reach out if you have any questions or collaboration ideas.
