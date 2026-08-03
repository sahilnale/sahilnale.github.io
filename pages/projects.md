# 🧪 Projects

### [Transformer Graph Compiler](https://github.com/sahilnale/transformer-graph-compiler) 🔗
A small ML compiler built from scratch: traces a GPT-2 block with torch.fx, lowers it into a custom SSA-style tensor IR, and runs classical compiler optimization passes over the graph — dead node elimination, constant folding, elementwise fusion, and add+layernorm fusion — each backed by correctness tests (36/36 passing). Paired with a standalone track of hand-written Triton GPU kernels (vector add, fused softmax) proving out the memory-bandwidth argument the fusion passes are motivated by.

**Technologies:** Python, PyTorch, torch.fx, Triton, pytest

### [Distributed LLM Inference Server](https://github.com/sahilnale/distributed-llm-inference-server) 🔗
A production-style LLM serving stack for Mistral-7B — FastAPI batching API, Redis request queue, and Prometheus/Grafana monitoring, all running on a custom distributed inference engine. Implemented four progressively better GPU tensor-parallelism strategies from scratch (Megatron-style MLP + attention head splitting across 2x V100 GPUs with NCCL/NVLink), taking throughput from a 0.64x regression to a 1.05x speedup over a single GPU.

**Technologies:** Python, PyTorch, FastAPI, NCCL, Redis, Docker, Prometheus, Grafana

### [TradeWhiz](https://github.com/sahilnale/TradeWhiz)
TradeWhiz allows users to simulate stock trading in a risk-free environment. It provides real-time stock data, market sentiment analysis, and helps users make informed trading decisions and practice their strategies without financial risk.

**Technologies:** React, Flask, MongoDB, NLTK, BeautifulSoup, AWS EC2

### [FindMyFood](https://github.com/sahilnale/FindMyFood) 🔗
FindMyFood is a full-stack iOS application to manage and share restaurant visits. It leverages Swift for the front-end, Firebase for user authentication, and MongoDB for data storage. AWS S3 is used for efficient storage and retrieval of user profile images and post photos.

**Technologies:** SwiftUI, Firebase, MapKit, MongoDB, AWS S3

### [react-vscode-portfolio](https://github.com/sahilnale/sahilnale.github.io) 🔗
- What you are looking at now
- A VS Code inspired portfolio project
- Responsive Web Design 
- React, TypeScript

### [Uber Fare Prediction](https://github.com/sahilnale/FindMyFood) 🔗
This project aims to predict the fare of Uber rides in New York City using various machine learning algorithms. It involves data preprocessing, feature engineering, and model evaluation to build a reliable fare prediction model. Gradient Boosting and XGBoost models were used, achieving an R² score of 0.85 and 0.87 respectively.

**Technologies:** Python, Jupyter Notebook, pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost

### RickGPT(https://github.com/sahilnale/RickGPT/blob/main/GPTRick.ipynb) 🔗
Developed a chatbot using Transformers and fine-tuning Microsoft’s DialoGPT to emulate Rick Sanchez’s personality from the TV show “Rick and Morty,” achieving 85% response relevance on NLP metrics such as BLEU and METEOR. Processed over 1000 unique dialogue inputs, optimizing the model for realistic conversational responses.

**Technologies:** Python, Pytorch, DialoGPT, Transformers, Hugging Face

### Custom Tweet Sentiment Analysis Transformer(https://github.com/sahilnale/twitter_sentiment/blob/main/sentiment_analysis.ipynb) 🔗
Developed a sentiment analysis BERT-like transformer model, achieving 90% accuracy and F1 score of 0.90 on the test data. Optimized transformer model performance, reducing evaluation loss to 0.25, with 89% precision and 91% recall.

**Technologies:** Python, PyTorch, scikit-learn, Pandas, Hugging Face

### Los Angeles Crime Analysis(https://github.com/sahilnale/la-crime-analysis) 🔗
Conducted analysis on over 1 million LA crime data points from the past three years, using statistical methods such as random tree forests, hypothesis testing, and bootstrapping with 95% confidence to analyze patterns and trends in crime. Created a Tableau Dashboard providing visual insights into LA crime, summarizing timings, areas, and victim demographics.

**Technologies:** R, SQL, Tableau, RStudio
