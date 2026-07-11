# NexusRCA – AI-Powered Cross-Tower Root Cause Intelligence Platform

## Overview

NexusRCA is an AI-powered Cross-Tower Root Cause Intelligence Platform designed to accelerate enterprise incident investigation by automatically correlating observability signals across **Network, Storage, Compute, and Application** layers.

Unlike traditional monitoring solutions that primarily detect alerts, NexusRCA transforms fragmented infrastructure events into actionable Root Cause Intelligence by combining graph-based correlation, historical incident learning, and Generative AI-powered reasoning.

The platform leverages **DeepSeek-R1-Distill-Qwen-32B**, **ChromaDB**, **Graph Analytics**, and **AMD MI300X GPU acceleration** to generate human-readable Root Cause Analysis (RCA), confidence scores, and remediation recommendations.

---

# Problem Statement

Modern enterprise environments generate thousands of infrastructure alerts every day.

Operations teams often spend significant time manually correlating incidents across multiple technology towers before identifying the actual root cause, resulting in:

* Increased Mean Time To Resolution (MTTR)
* Fragmented troubleshooting
* Operational downtime
* Reduced productivity

NexusRCA addresses these challenges through intelligent, AI-driven cross-tower incident correlation and automated root cause reasoning.

---

# Key Features

* Cross-Tower Correlation Engine
* Graph-Based Dependency Analysis
* Historical Incident Learning using ChromaDB
* AI-Powered Root Cause Analysis using DeepSeek-R1
* Confidence Scoring Framework
* Human-Readable RCA Reports
* Remediation Recommendation Generation
* Enterprise-Scale Validation (100,000 Synthetic Incidents)
* Interactive Dashboard & Analytics
* AMD MI300X Accelerated Inference

---

# Solution Workflow

```text
Observability Events
(Network | Storage | Compute | Application)
                │
                ▼
Unified Event Ingestion
                │
                ▼
Cross-Tower Correlation Engine
                │
                ▼
Graph Analytics
                │
                ▼
Historical Incident Retrieval (ChromaDB)
                │
                ▼
DeepSeek-R1 Reasoning Engine
                │
                ▼
Confidence Scoring
                │
                ▼
Human-Readable RCA
                │
                ▼
Remediation Recommendations
                │
                ▼
Dashboard & Operational Insights
```

---

# Technology Stack

### AI & Machine Learning

* DeepSeek-R1-Distill-Qwen-32B
* SGLang
* ChromaDB

### Data Processing

* Python
* Polars
* DuckDB
* Pandas

### Analytics

* NetworkX
* Graph Analytics

### Visualization

* Streamlit
* Plotly
* Matplotlib

### Infrastructure

* AMD MI300X GPU
* ROCm 7.0
* Python 3.10+

---

# Project Components

* Synthetic Enterprise Incident Generator
* Cross-Tower Correlation Engine
* Historical Incident Memory
* AI Reasoning Engine
* Confidence Scoring Module
* Interactive Dashboard
* RCA Evaluation Framework
* Fault Injection Framework

---

# Demonstration

The project demonstrates:

* Enterprise-scale observability simulation
* Cross-tower dependency analysis
* Historical incident retrieval
* AI-generated Root Cause Analysis
* Confidence-based decision support
* Interactive operational dashboards

---

# Performance Highlights

* Enterprise-scale dataset containing **100,000 synthetic incidents**
* AI-powered RCA generation using **DeepSeek-R1-Distill-Qwen-32B**
* Accelerated inference using **AMD MI300X GPU**
* Historical incident retrieval using **ChromaDB**
* Graph-based correlation across multiple infrastructure towers

---

# Repository Structure

```text
Notebook 01 - Environment Setup
Notebook 02 - Synthetic Incident Generation
Notebook 03 - Cross-Tower Correlation
Notebook 04 - AI-Powered RCA Generation
Notebook 05 - Historical Incident Learning
Notebook 06 - Dashboard & Analytics
Notebook 07 - End-to-End Workflow
Notebook 08 - Enhanced RCA Logic
Notebook 09 - Enterprise Scale Validation
Notebook 10 - RCA Evaluation Framework
```

---

# Future Enhancements

* Real-time observability platform integration
* Temporal causal intelligence
* Predictive failure detection
* Autonomous AI-driven remediation
* Self-healing AIOps workflows

---

# Project Vision

NexusRCA aims to evolve from an AI-powered Root Cause Analysis solution into a comprehensive **Root Cause Intelligence Platform** capable of enabling autonomous enterprise operations through continuous learning, predictive analytics, and intelligent remediation.

---

# Acknowledgements

Developed as part of an AI Hackathon leveraging AMD AI infrastructure, DeepSeek-R1, ROCm, and modern open-source AI technologies to demonstrate enterprise-scale observability and intelligent incident management.
