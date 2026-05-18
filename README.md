Benchmarking Model Codes
A Comprehensive Benchmark Suite for Software Vulnerability Detection Using Machine Learning, Deep Learning, Transformer Architectures, and Large Language Models
Overview

This repository presents a large-scale benchmarking framework for automated software vulnerability detection across multiple learning paradigms, including:

Traditional Machine Learning
Deep Learning Architectures
Transformer-Based Models
Open-Source Large Language Models (LLMs)

The benchmark is designed to evaluate and compare model performance, contextual understanding, representation learning capability, and generalization behavior across widely used vulnerability detection datasets.

The repository emphasizes:

Reproducible experimentation
Unified evaluation workflows
Cross-model comparative analysis
Security-oriented code intelligence research
Research Objectives

The primary objectives of this benchmark framework are:

To evaluate the effectiveness of diverse learning paradigms for software vulnerability detection
To compare classical machine learning methods with modern transformer and LLM-based architectures
To analyze model generalization across heterogeneous vulnerability datasets
To establish a unified and reproducible experimental framework for vulnerability detection research
To investigate contextual semantic understanding in source-code-focused models
Repository Structure
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
│   │
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
Benchmark Categories
Traditional Machine Learning

The repository includes classical machine learning baselines widely used for structured feature-based vulnerability classification:

Logistic Regression
Support Vector Machine (SVM)
XGBoost
Random Forest
Decision Tree

These models serve as foundational baselines for comparative evaluation against neural and transformer-based architectures.

Deep Learning Architectures

Deep learning implementations focus on sequence learning, structural representation learning, and semantic feature extraction from source code:

Convolutional Neural Networks (CNN)
Long Short-Term Memory Networks (LSTM)
Bidirectional LSTM (BiLSTM)
Gated Recurrent Units (GRU)
Deep Graph Convolutional Neural Networks (DGCNN)
Graph Convolutional Networks (GCN)

These architectures are evaluated for their ability to capture syntactic and contextual vulnerability patterns.

Transformer-Based Models

Transformer architectures are evaluated for contextual code understanding and semantic representation learning:

CodeBERT
GraphCodeBERT
CodeT5
PLBart
UniXCoder

The benchmark investigates the effectiveness of pre-trained code representation models for vulnerability detection tasks.

Large Language Models (LLMs)

The repository also includes experimentation pipelines for instruction-tuned and code-specialized open-source LLMs:

CodeLlama
Mistral
DeepSeekCoder

These models are explored for:

contextual vulnerability reasoning
semantic code understanding
instruction-based classification
zero-shot and fine-tuned vulnerability detection
Datasets
Devign Dataset

The Devign dataset is a widely adopted benchmark dataset containing vulnerable and non-vulnerable real-world functions extracted from open-source software projects.

The dataset is used to evaluate:

binary vulnerability classification
contextual code understanding
neural representation learning
PrimeVul Dataset

PrimeVul is a large-scale vulnerability detection dataset designed for modern source code security analysis and benchmarking.

The dataset supports:

large-scale vulnerability classification
transformer-based experimentation
LLM-oriented security research
cross-dataset generalization studies
Experimental Pipeline

The repository includes implementations for:

Data preprocessing
Tokenization pipelines
Feature engineering
Model training
Fine-tuning workflows
Inference pipelines
Evaluation and benchmarking
Visualization generation

Additional utilities are provided for:

reproducibility
experiment tracking
result aggregation
comparative analysis
Evaluation Metrics

All models are evaluated using standardized classification metrics:

Accuracy
Precision
Recall
F1-Score

Additional analytical artifacts may include:

Confusion Matrices
Training and Validation Curves
Comparative Benchmark Graphs
Cross-Model Performance Analysis
Research Contributions

This repository aims to contribute toward:

Unified benchmarking for vulnerability detection research
Comparative analysis across heterogeneous model families
Investigation of representation learning in source code intelligence
Reproducible security-oriented machine learning experimentation
Open-source benchmarking infrastructure for future research
Installation

Clone the repository:

git clone https://github.com/vuln-bench-2026/Benchmarking-model-codes.git

Move into the repository:

cd Benchmarking-model-codes

Install dependencies:

pip install -r requirements.txt
Usage

Each model implementation contains:

training scripts
preprocessing workflows
evaluation pipelines
inference utilities

Navigate to the corresponding dataset and architecture directory to execute experiments.

Reproducibility

This repository is structured to promote reproducible experimentation through:

modular implementation design
isolated dataset pipelines
consistent evaluation procedures
standardized benchmark configurations
Notes
Large datasets and pretrained checkpoints are intentionally excluded due to storage constraints.
Certain experimental or unpublished implementations may not be publicly released.
Performance may vary depending on hardware configuration, preprocessing strategies, and hyperparameter settings.
Research Scope

This benchmark framework focuses on advancing research in:

Software Vulnerability Detection
Secure Code Intelligence
AI for Cybersecurity
Transformer-Based Code Analysis
Graph-Based Neural Vulnerability Detection
Large Language Models for Software Security
