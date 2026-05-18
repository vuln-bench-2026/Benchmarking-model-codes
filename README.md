<div align="center">

# Benchmarking Model Codes

### Comprehensive Benchmarking Framework for Software Vulnerability Detection  
### using Machine Learning, Deep Learning, Transformers, and Large Language Models

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Cybersecurity-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Task-Vulnerability%20Detection-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Research-Benchmarking-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Framework-PyTorch-orange?style=for-the-badge">
</p>

</div>

---

# Overview

This repository presents a large-scale **research-oriented benchmarking framework** for automated software vulnerability detection across multiple learning paradigms, including:

- Traditional Machine Learning
- Deep Learning Architectures
- Transformer-Based Models
- Open-Source Large Language Models (LLMs)

The framework is designed to systematically evaluate:
- Model performance
- Representation learning capability
- Contextual semantic understanding
- Cross-dataset generalization behavior
- Security-oriented code intelligence

across widely used vulnerability detection datasets such as **Devign** and **PrimeVul**.

---

# Research Motivation

Software vulnerabilities remain one of the most critical challenges in modern software engineering and cybersecurity. Recent advances in transformer architectures and code-specialized LLMs have significantly improved automated vulnerability detection; however, comprehensive comparative benchmarking across heterogeneous model families remains limited.

This repository aims to provide:
- A unified experimental infrastructure
- Reproducible benchmarking workflows
- Cross-paradigm comparative analysis
- Modular research pipelines for future extensions

---

# Repository Architecture

```text
Benchmarking-model-codes/
│
├── Devign/
│   │
│   ├── MachineLearning/
│   │   ├── LogisticRegression/
│   │   ├── SVM/
│   │   ├── XGBoost/
│   │   ├── RandomForest/
│   │   └── DecisionTree/
│   │
│   ├── DeepLearning/
│   │   ├── CNN/
│   │   ├── LSTM/
│   │   ├── BiLSTM/
│   │   ├── GRU/
│   │   ├── DGCNN/
│   │   └── GCN/
│   │
│   ├── Transformers/
│   │   ├── CodeBERT/
│   │   ├── GraphCodeBERT/
│   │   ├── CodeT5/
│   │   ├── PLBart/
│   │   └── UniXCoder/
│   │
│   └── LLMs/
│       ├── CodeLlama/
│       ├── Mistral/
│       └── DeepSeekCoder/
│
├── PrimeVul/
│   ├── MachineLearning/
│   ├── DeepLearning/
│   ├── Transformers/
│   └── LLMs/
│
├── preprocessing/
├── utils/
├── results/
├── plots/
├── docs/
├── requirements.txt
└── README.md
```

---

# Implemented Models

## Traditional Machine Learning

| Category | Models |
|---|---|
| Classical ML | Logistic Regression, SVM, XGBoost, Random Forest, Decision Tree |

These models serve as foundational baselines for comparative evaluation against neural and transformer-based approaches.

---

## Deep Learning Architectures

| Category | Models |
|---|---|
| Sequence Learning | LSTM, BiLSTM, GRU |
| Spatial Learning | CNN |
| Graph Neural Networks | DGCNN, GCN |

These architectures are evaluated for their ability to capture:
- syntactic structures
- semantic representations
- contextual vulnerability patterns
- graph-based code relationships

---

## Transformer-Based Models

| Model Family | Implementations |
|---|---|
| Encoder-Based | CodeBERT, GraphCodeBERT |
| Encoder-Decoder | CodeT5, PLBart |
| Unified Representation Models | UniXCoder |

The benchmark investigates transformer effectiveness for:
- contextual code understanding
- semantic representation learning
- vulnerability localization
- source code intelligence

---

## Large Language Models (LLMs)

| Model | Purpose |
|---|---|
| CodeLlama | Instruction-based vulnerability reasoning |
| Mistral | Fine-tuned code understanding |
| DeepSeekCoder | Security-oriented code intelligence |

The LLM experiments explore:
- zero-shot vulnerability detection
- instruction-tuned classification
- semantic reasoning
- contextual vulnerability analysis

---

# Datasets

## Devign

A widely adopted benchmark dataset containing real-world vulnerable and non-vulnerable functions extracted from open-source software projects.

### Evaluation Focus
- Binary vulnerability classification
- Semantic understanding
- Neural representation learning

---

## PrimeVul

A large-scale vulnerability detection dataset designed for modern security-oriented source code analysis.

### Evaluation Focus
- Large-scale benchmarking
- Transformer experimentation
- LLM-based security analysis
- Cross-dataset generalization

---

# Experimental Pipeline

The repository includes modular implementations for:

- Data preprocessing
- Tokenization pipelines
- Feature engineering
- Graph construction
- Model training
- Fine-tuning workflows
- Inference pipelines
- Benchmark evaluation
- Visualization generation

---

# Evaluation Metrics

All models are evaluated using standardized classification metrics:

| Metric | Purpose |
|---|---|
| Accuracy | Overall prediction correctness |
| Precision | Vulnerability prediction reliability |
| Recall | Vulnerability detection capability |
| F1-Score | Balanced classification performance |

Additional analysis includes:
- Confusion Matrices
- Training Curves
- Validation Curves
- Comparative Benchmark Graphs
- Cross-Architecture Analysis

---

# Research Contributions

This benchmark framework aims to contribute toward:

- Unified benchmarking for vulnerability detection
- Comparative analysis across heterogeneous architectures
- Investigation of contextual source code intelligence
- Reproducible security-oriented ML experimentation
- Open-source benchmarking infrastructure for future research

---

# Installation

Clone the repository:

```bash
git clone https://github.com/vuln-bench-2026/Benchmarking-model-codes.git
```

Move into the repository:

```bash
cd Benchmarking-model-codes
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Usage

Each implementation directory contains:
- training workflows
- preprocessing scripts
- evaluation pipelines
- inference utilities

Navigate to the corresponding dataset and architecture directory to execute experiments.

---

# Reproducibility

The repository is structured to promote reproducible experimentation through:
- modular pipeline design
- isolated dataset configurations
- standardized evaluation protocols
- reproducible benchmark workflows

---

# Notes

- Large datasets and pretrained checkpoints are intentionally excluded due to storage limitations.
- Certain experimental or unpublished implementations may not be publicly released.
- Performance may vary depending on preprocessing configuration, hardware environment, and hyperparameter settings.

---

# Research Scope

This benchmark framework focuses on advancing research in:

- Software Vulnerability Detection
- Secure Code Intelligence
- AI for Cybersecurity
- Transformer-Based Code Analysis
- Graph Neural Networks for Security
- Large Language Models for Software Engineering

---

<div align="center">

### Research-Oriented Benchmarking for Secure AI-Driven Software Analysis

</div>
