# StratAssist Research Dataset Repository
This repository contains the dataset used in the research paper "Understanding User Perception of Human-LLM Collaboration in AI-Assisted Decision-Making".

### Paper Overview
This study investigates the potential of Large Language Models (LLMs) in facilitating strategic planning through human-AI collaboration. We developed StratAssist, a prototype system that implements three levels of LLM involvement in strategy development: form-based input, chatbot-assisted input, and LLM-driven input.
Dataset Description
The dataset was specifically created for the Retrieval-Augmented Generation (RAG) module of the StratAssist system to enhance LLM's context-dependent thinking in strategic planning tasks. The dataset augments general pre-trained knowledge with recent, task-specific information relevant to business strategy development.

### Dataset Composition
| Category           | Major Sources                                                                 | Number of Entries |
|--------------------|--------------------------------------------------------------------------------|-------------------|
| Strategy/Industry Reports | Consulting firms (McKinsey, Deloitte), Security firms (NH, MAS, SS, KB, KIS) | 433               |
| News              | Daily news, Financial news (MK, KED)                                            | 926               |
| Financial Filings | DART (FSS)                                                                      | 520               |
| **Total**         |                                                                                 | **1,879**         |

### Data Collection Period
Coverage: January 1st - September 1st, 2024
Purpose: Provide recent, task-specific information for strategic planning assistance

### Technical Implementation
Embedding Model: OpenAI's text-embedding-3-small
Vector Database: Meta's FAISS library for efficient similarity search
Architecture: Modular design allowing easy replacement with advanced RAG modules
