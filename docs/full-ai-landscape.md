# Full AI Landscape Sheet

## Concept hierarchy

```text
Artificial Intelligence (AI)
├── Machine Learning (ML)
│   ├── Classic ML
│   │   ├── Supervised Learning
│   │   ├── Unsupervised Learning
│   │   └── Reinforcement Learning
│   ├── Deep Learning
│   │   ├── CNN
│   │   ├── RNN
│   │   ├── Transformers
│   │   │   ├── LLMs
│   │   │   │   ├── NLP
│   │   │   │   └── AI Models (ChatGPT, vision systems)
│   │   │   └── Multimodal models (text + image + audio)
│   └── Generative AI (GenAI)
│       ├── Prompt Engineering
│       ├── Fine-tuning
│       └── RAG (Retrieval-Augmented Generation)
│           ├── Embeddings
│           └── Vector Databases
├── Agentic AI / AI Agents (systems using models + tools)
│   └── MCP (Model Context Protocol)
├── Data Science (uses ML + statistics for insights)
├── Data Engineering (builds data pipelines for everything)
├── MLOps / LLMOps (deploy, monitor, evaluate, and govern AI systems)
└── Foundations
    ├── Python
    ├── NumPy
    ├── Statistics
    ├── Linear Algebra
    └── Probability
```

## Simple human explanation

- **AI** → goal (make machines smart)
- **ML** → how machines learn
- **Supervised Learning** → learns from labeled data (input + correct output)
- **Unsupervised Learning** → finds patterns in unlabeled data
- **Reinforcement Learning** → learns by trial-and-error using rewards
- **Deep Learning** → advanced ML using neural networks
- **CNN** → deep learning for images/spatial data
- **RNN** → deep learning for sequential/time-series data
- **Transformers** → model architecture behind modern LLMs
- **LLMs** → large language models that generate and understand text
- **NLP** → AI for human language
- **Multimodal Models** → models that handle text + image + audio together
- **GenAI** → creates new content (text, image, code, audio)
- **Prompt Engineering** → guiding model behavior with instructions/examples
- **Fine-tuning** → training a base model on task-specific data
- **RAG** → GenAI + external knowledge retrieval for grounded answers
- **Embeddings** → convert text/data into vectors for semantic search
- **Vector DB** → stores and retrieves embeddings efficiently
- **AI Agents** → AI that can act and complete tasks
- **MCP** → standard way for AI/agents to use tools and external data
- **Data Science** → uses data to find insights and build models
- **Data Engineering** → builds the data system behind everything
- **MLOps / LLMOps** → runs AI systems reliably in production
- **Foundations** → math + programming base for ML/DS/AI systems

## How they connect in practice

```text
Foundations → provides math/programming base
	↓
Data Engineering → builds and serves clean data
	↓
Data Science / ML → analyzes data and trains models
	↓
Deep Learning / GenAI / RAG → intelligence layer
	↓
MLOps / LLMOps → deploys and monitors in production
	↓
Agentic AI + MCP → takes actions using tools/data
```