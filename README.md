# Portfolio Analysis: Keyword Extraction and Network Analysis

## Overview
This repository provides a two-stage analysis framework for evaluating research portfolios and understanding program effectiveness. The analysis addresses fundamental questions about research portfolios: What are the dominant research themes? How are projects interconnected?  How do research topics evolve over time? 

The analysis pipeline consists of two complementary scripts to transform a collection of individual projects into a connected ecosystem of knowledge, revealing hidden patterns, thematic clusters, and temporal trends.

## Repository Structure
```
Portfolio-analysis/
├── keyword_extraction.ipynb       # Stage 1: Topical keyword extraction
├── network_analysis.ipynb         # Stage 2: Network analysis and visualization
└── README.md
```

## Two-Stage Analysis Pipeline

### Stage 1: Keyword Extraction (`keyword_extraction.ipynb`)
**Purpose**: Extract topical keywords from 12-page of project proposals and summaries to identify core research themes and concepts.

**Methods**:
- **KeyBERT**: Utilizes BERT embeddings to extract semantically relevant keywords that best represent document content
- **KeyLLM**: Leverages large language models for context-aware keyword extraction with deeper semantic understanding

**Input**: text of project proposals
**Output**: Structured keyword lists for each project, enabling thematic categorization

### Stage 2: Network Analysis (`network_analysis.ipynb`)
**Purpose**: Analyze relationships between projects based on extracted keywords and temporal patterns.

**Methods**:
- **Network Construction**: Creates project networks based on connectedness of keywords
- **Community Detection**: Identifies clusters of related projects
- **Temporal Analysis**: Tracks evolution of research themes over time


## Comprehensive Analysis Capabilities

### Research Portfolio Analysis
- **Project Interconnectedness**: Maps relationships between projects based on shared themes, methodologies, or research areas
- **Topic Identification**: Identifies major research themes and subject areas across the entire portfolio
- **Temporal Evolution**: Tracks how research topics and themes change and evolve over time
- **Thematic Clustering**: Groups related projects into coherent research clusters

### Program Evaluation Applications
- **Strategic Assessment**: Evaluates portfolio balance and identifies research gaps
- **Impact Analysis**: Measures influence and connectivity of different research areas
- **Trend Forecasting**: Predicts emerging research directions based on historical patterns
- **Resource Allocation**: Informs decision-making for future program funding and direction

### Network Analysis Applications
- **Centrality Analysis**: Identifies the most influential topics within the portfolio
- **Community Detection**: Discovers natural groupings of related projects
- **Trend Analysis**: Visualizes how research focus shifts across different time periods
- **Gap Analysis**: Identifies underexplored areas or potential research opportunities
