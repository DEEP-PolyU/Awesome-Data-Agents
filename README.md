# Awesome Data Agents


Research papers, benchmarks, and projects on **Data Agents**, collected from our survey 📖<em>"**Towards Reliable AI Data Scientists: Data Agents with Workflow Harnesses**"</em>.

🤗 Contributions are welcome! Submit an issue or pull request to suggest papers, add resource links, or correct an entry.

📫 **Contact:** `huachi.zhou@connect.polyu.hk`

---

<div align="center">
     <img width="100%" src="figures/data_agent_workflow.png" alt="Data Agent workflow illustrated through regional sales analysis">
     <p><em>The workflow harness of AI Data Scientists: perception, planning, execution, verification, and repair maintain the evolving data state, localize failures, and retain validated corrections across data tasks. The regional sales example illustrates how a join-key error is detected and repaired.</em></p>
</div>

## 📜 Catalog

> **[Awesome Data Agents](#awesome-data-agents)**
>
> - **[📖 Overview](#-overview)**
> - **[📚 Related Survey](#-related-survey-papers)**
> - **[🪴 Taxonomy](#-taxonomy)**
>   - [Perception](#perception)
>   - [Planning](#planning)
>   - [Execution](#execution)
>   - [Verification](#verification)
>   - [Repair](#repair)
> - **[🔎 Open Reliability Problems](#-open-reliability-problems)**
> - **[🏆 Benchmark](#-benchmark)**
> - **[📦 Projects](#-projects)**
> - **[📃 Citation](#-citation)**

---

## 📖 Overview

A Data Agent is an LLM-driven system that executes end-to-end data science tasks through interaction with a data environment and computational tools. It observes execution results and iteratively refines its actions to produce analytical artifacts, including cleaned datasets, visualizations, and reports. The survey organizes these systems by five workflow stages and three data types: structured, semi-structured, and unstructured data.

## 📚 Related Survey Papers

- (arXiv'25) **Autonomous Data Agents: A New Opportunity for Smart Data** [[Paper]](https://arxiv.org/abs/2509.18710)
- (arXiv'25) **A Survey of LLM × DATA** [[Paper]](https://arxiv.org/abs/2505.18458)
- (arXiv'25) **A Survey of Data Agents: Emerging Paradigm or Overstated Hype?** [[Paper]](https://arxiv.org/abs/2510.23587)
- (arXiv'25) **A Survey of Reasoning and Agentic Systems in Time Series with Large Language Models** [[Paper]](https://arxiv.org/abs/2509.11575)
- (arXiv'25) **LLM-Based Data Science Agents: A Survey of Capabilities, Challenges, and Future Directions** [[Paper]](https://arxiv.org/abs/2510.04023)
- (arXiv'25) **LLM/Agent-as-Data-Analyst: A Survey** [[Paper]](https://arxiv.org/abs/2509.23988)
- (arXiv'26) **Can LLMs Clean Up Your Mess? A Survey of Application-Ready Data Preparation with LLMs** [[Paper]](https://arxiv.org/abs/2601.17058)
- (arXiv'26) **Data Agents: Levels, State of the Art, and Open Problems** [[Paper]](https://arxiv.org/abs/2602.04261)

## 🪴 Taxonomy

### Perception

<div align="center">
     <img width="100%" src="figures/fig2_perception.png" alt="Perception through data structure probing, cross-source evidence linking, and risk-calibrated state scoring">
     <p><em>Perception builds a risk-calibrated data state through data structure probing, cross-source evidence linking, and risk-calibrated state scoring. The figure shows these operations across structured, semi-structured, and unstructured data.</em></p>
</div>

#### Structured Data

- (VLDB'26, to appear) **Arming Data Agents with Tribal Knowledge** [[Paper]](https://arxiv.org/abs/2602.13521)
- (arXiv'26) **PV-SQL: Synergizing Database Probing and Rule-based Verification for Text-to-SQL Agents** [[Paper]](https://arxiv.org/abs/2604.17653)
- (COLM'26) **FlexSQL: Flexible Exploration and Execution Make Better Text-to-SQL Agents** [[Paper]](https://arxiv.org/abs/2605.02815)
- (arXiv'26) **TSQAgent: Rating Time Series Data Quality via Dedicated Agentic Reasoning** [[Paper]](https://arxiv.org/abs/2606.03629)
- (arXiv'26) **TimeClaw: A Time-Series AI Agent with Exploratory Execution Learning** [[Paper]](https://arxiv.org/abs/2605.10038)
- (arXiv'26) **OmniTQA: A Cost-Aware System for Hybrid Query Processing over Semi-Structured Data** [[Paper]](https://arxiv.org/abs/2604.02444v1)
- (SIGMOD Companion'26) **Cortex AISQL: A Production SQL Engine for Unstructured Data** [[Paper]](https://arxiv.org/abs/2511.07663)
- (arXiv'26) **SEMA-SQL: Beyond Traditional Relational Querying with Large Language Models** [[Paper]](https://arxiv.org/abs/2604.23477)
- (arXiv'26) **Blue Data Intelligence Layer: Streaming Data and Agents for Multi-source Multi-modal Data-Centric Applications** [[Paper]](https://arxiv.org/abs/2604.15233)
- (arXiv'26) **PExA: Parallel Exploration Agent for Complex Text-to-SQL** [[Paper]](https://arxiv.org/abs/2604.22934)
- (arXiv'26) **Learning to Retrieve: Dual-Level Long-Term Memory for Text-to-SQL Agents** [[Paper]](https://arxiv.org/abs/2606.00547)
- (EDBT'25) **Entity Matching using Large Language Models** [[Paper]](https://arxiv.org/abs/2310.11244)
- (arXiv'26) **Cast-R1: Learning Tool-Augmented Sequential Decision Policies for Time Series Forecasting** [[Paper]](https://arxiv.org/abs/2602.13802)
- (Findings of EMNLP'24) **R³-NL2GQL: A Model Coordination and Knowledge Graph Alignment Approach for NL2GQL** [[Paper]](https://aclanthology.org/2024.findings-emnlp.800/)

#### Semi-Structured Data

- (arXiv'26) **TabClaw: An Interactive and Self-Evolving Agent for Spreadsheet Manipulation and Table Reasoning** [[Paper]](https://arxiv.org/abs/2606.10316)
- (WSDM'26) **TableMind: An Autonomous Programmatic Agent for Tool-Augmented Table Reasoning** [[Paper]](https://arxiv.org/abs/2509.06278)
- (HILDA'24) **Cocoon: Semantic Table Profiling Using Large Language Models** [[Paper]](https://arxiv.org/abs/2404.12552)
- (arXiv'25) **RubikSQL: Lifelong Learning Agentic Knowledge Base as an Industrial NL2SQL System** [[Paper]](https://arxiv.org/abs/2508.17590)
- (arXiv'25) **AgenticData: An Agentic Data Analytics System for Heterogeneous Data** [[Paper]](https://arxiv.org/abs/2508.05002)
- (arXiv'25) **An LLM Agent-Based Complex Semantic Table Annotation Approach** [[Paper]](https://arxiv.org/abs/2508.12868)
- (arXiv'26) **TABQAWORLD: Optimizing Multimodal Reasoning for Multi-Turn Table Question Answering** [[Paper]](https://arxiv.org/abs/2604.03393)
- (arXiv'26) **SemPiper: Interactive Code Synthesis for Semantic Operators in Machine Learning Pipelines** [[Paper]](https://arxiv.org/abs/2606.14361)
- (arXiv'26) **DataSTORM: Deep Research on Large-Scale Databases using Exploratory Data Analysis and Data Storytelling** [[Paper]](https://arxiv.org/abs/2604.06474)
- (arXiv'25) **TAGAL: Tabular Data Generation using Agentic LLM Methods** [[Paper]](https://arxiv.org/abs/2509.04152)
- (arXiv'26) **Beyond Linear LLM Invocation: An Efficient and Effective Semantic Filter Paradigm** [[Paper]](https://arxiv.org/abs/2603.04799)
- (ADBIS'24) **LLMClean: Context-Aware Tabular Data Cleaning via LLM-Generated OFDs** [[Paper]](https://arxiv.org/abs/2404.18681)
- (arXiv'26) **TwinBI: An Agentic Digital Twin for Efficient Augmented Interactions with Business Intelligence Dashboards** [[Paper]](https://arxiv.org/abs/2606.13731)

#### Unstructured Data

- (arXiv'26) **MimirRAG: A Multi-Agent RAG Framework for Financial Data Retrieval with Metadata Integration** [[Paper]](https://arxiv.org/abs/2605.25030)
- (arXiv'26) **MAVEN: A Multi-stage Agentic Annotation Pipeline for Video Reasoning Tasks** [[Paper]](https://arxiv.org/abs/2605.21917)
- (arXiv'25) **HARMON-E: Hierarchical Agentic Reasoning for Multimodal Oncology Notes to Extract Structured Data** [[Paper]](https://arxiv.org/abs/2512.19864)
- (arXiv'26) **Navigating the Mirage: A Dual-Path Agentic Framework for Robust Misleading Chart Question Answering** [[Paper]](https://arxiv.org/abs/2603.28583)
- (arXiv'25) **Code-in-the-Loop Forensics: Agentic Tool Use for Image Forgery Detection** [[Paper]](https://arxiv.org/abs/2512.16300)
- (arXiv'25) **Doc-Researcher: A Unified System for Multimodal Document Parsing and Deep Research** [[Paper]](https://arxiv.org/abs/2510.21603)
- (PACMMOD'26) **AgenticScholar: Agentic Data Management with Pipeline Orchestration for Scholarly Corpora** [[Paper]](https://arxiv.org/abs/2603.13774)
- (arXiv'26) **LongDA: Benchmarking LLM Agents for Long-Document Data Analysis** [[Paper]](https://arxiv.org/abs/2601.02598)
- (EMNLP'24) **PDFTriage: Question Answering over Long, Structured Documents** [[Paper]](https://aclanthology.org/2024.emnlp-industry.13/)

### Planning

<div align="center">
     <img width="100%" src="figures/fig3_planning.png" alt="Planning through tree search, heuristic search, and strategy routing">
     <p><em>Planning turns the perceived data state into an executable plan through tree search, heuristic search, or strategy routing. The figure illustrates value backpropagation, candidate scoring and refinement, and selection from predefined strategies.</em></p>
</div>

#### Structured Data

- (arXiv'25) **MARS-SQL: A multi-agent reinforcement learning framework for Text-to-SQL** [[Paper]](https://arxiv.org/abs/2511.01008)
- (COLM'26) **FlexSQL: Flexible Exploration and Execution Make Better Text-to-SQL Agents** [[Paper]](https://arxiv.org/abs/2605.02815)
- (ICLR'25) **CHASE-SQL: Multi-Path Reasoning and Preference Optimized Candidate Selection in Text-to-SQL** [[Paper]](https://arxiv.org/abs/2410.01943)
- (PACMMOD'25) **OpenSearch-SQL: Enhancing Text-to-SQL with Dynamic Few-shot and Consistency Alignment** [[Paper]](https://arxiv.org/abs/2502.14913)
- (COLM'25) **EllieSQL: Cost-Efficient Text-to-SQL with Complexity-Aware Routing** [[Paper]](https://arxiv.org/abs/2503.22402)
- (VLDB'25) **SiriusBI: A Comprehensive LLM-Powered Solution for Data Analytics in Business Intelligence** [[Paper]](https://www.vldb.org/pvldb/vol18/p4860-xie.pdf)
- (Findings of EMNLP'24) **R³-NL2GQL: A Model Coordination and Knowledge Graph Alignment Approach for NL2GQL** [[Paper]](https://aclanthology.org/2024.findings-emnlp.800/)

#### Semi-Structured Data

- (AAAI'26) **Jupiter: Enhancing LLM Data Analysis Capabilities via Notebook and Inference-Time Value-Guided Search** [[Paper]](https://arxiv.org/abs/2509.09245)
- (arXiv'26) **SemPipes – Optimizable Semantic Data Operators for Tabular Machine Learning Pipelines** [[Paper]](https://arxiv.org/abs/2602.05134)
- (arXiv'25) **ArchPilot: A Proxy-Guided Multi-Agent Approach for Machine Learning Engineering** [[Paper]](https://arxiv.org/abs/2511.03985)
- (arXiv'26) **M²-Miner: Multi-Agent Enhanced MCTS for Mobile GUI Agent Data Mining** [[Paper]](https://arxiv.org/abs/2602.05429)
- (ICLR'26) **TaTToo: Tool-Grounded Thinking PRM for Test-Time Scaling in Tabular Reasoning** [[Paper]](https://arxiv.org/abs/2510.06217)
- (KDD'26) **Rewarding the Scientific Process: Process-Level Reward Modeling for Agentic Data Analysis** [[Paper]](https://arxiv.org/abs/2604.24198)
- (AAAI'25) **Evolutionary Large Language Model for Automated Feature Transformation** [[Paper]](https://arxiv.org/abs/2405.16203)
- (VLDB'24) **RetClean: Retrieval-Based Data Cleaning Using LLMs and Data Lakes** [[Paper]](https://www.vldb.org/pvldb/vol17/p4421-eltabakh.pdf)
- (arXiv'25) **Dataforge: Agentic Platform for Autonomous Data Engineering** [[Paper]](https://arxiv.org/abs/2511.06185)
- (VLDB'24) **Chat2Data: An Interactive Data Analysis System with RAG, Vector Databases and LLMs** [[Paper]](https://www.vldb.org/pvldb/vol17/p4481-li.pdf)
- (EMNLP'24) **DataNarrative: Automated Data-Driven Storytelling with Visualizations and Texts** [[Paper]](https://aclanthology.org/2024.emnlp-main.1073/)

#### Unstructured Data

- (Findings of EMNLP'25) **MCTS-RAG: Enhancing Retrieval-Augmented Generation with Monte Carlo Tree Search** [[Paper]](https://aclanthology.org/2025.findings-emnlp.672/)
- (VLDB'25) **DocETL: Agentic Query Rewriting and Evaluation for Complex Document Processing** [[Paper]](https://arxiv.org/abs/2410.12189)
- (NeurIPS'24) **UQE: A Query Engine for Unstructured Databases** [[Paper]](https://arxiv.org/abs/2407.09522)
- (CAIS'26) **Do Agents Need to Plan Step-by-Step? Rethinking Planning Horizon in Data-Centric Tool Calling** [[Paper]](https://arxiv.org/abs/2605.08477)
- (arXiv'26) **DeepXiv-SDK: An Agentic Data Interface for Scientific Literature** [[Paper]](https://arxiv.org/abs/2603.00084)
- (arXiv'25) **Doc-Researcher: A Unified System for Multimodal Document Parsing and Deep Research** [[Paper]](https://arxiv.org/abs/2510.21603)
- (PACMMOD'26) **AgenticScholar: Agentic Data Management with Pipeline Orchestration for Scholarly Corpora** [[Paper]](https://arxiv.org/abs/2603.13774)
- (arXiv'26) **OmniRAG-Agent: Agentic Omni-modal Reasoning for Low-Resource Long Audio-Video Question Answering** [[Paper]](https://arxiv.org/abs/2602.03707)

### Execution

<div align="center">
     <img width="100%" src="figures/fig4_execution.png" alt="Execution through tool capability boundaries, compositional tool reasoning, and feedback-adaptive tool calling">
     <p><em>Execution turns a plan into tool calls over heterogeneous data. The figure organizes the methods around tool capability boundaries, compositional tool reasoning, and feedback-adaptive tool calling.</em></p>
</div>

#### Structured Data

- (ICML'26) **NaviAgent: Graph-Driven Bilevel Planning for Scalable Tool Orchestration** [[Paper]](https://arxiv.org/abs/2506.19500)
- (arXiv'26) **TimeART: Towards Agentic Time Series Reasoning via Tool-Augmentation** [[Paper]](https://arxiv.org/abs/2601.13653)
- (arXiv'26) **TimeClaw: A Time-Series AI Agent with Exploratory Execution Learning** [[Paper]](https://arxiv.org/abs/2605.10038)

#### Semi-Structured Data

- (NAACL'25) **EASYTOOL: Enhancing LLM-based Agents with Concise Tool Instruction** [[Paper]](https://aclanthology.org/2025.naacl-long.44/)
- (ACL'26) **OctoTools: A Multi-Agent Framework with Extensible Tools for Complex Reasoning** [[Paper]](https://aclanthology.org/2026.acl-long.1/)
- (Findings of ACL'26) **Failure Makes the Agent Stronger: Enhancing Accuracy through Structured Reflection for Reliable Tool Interactions** [[Paper]](https://arxiv.org/abs/2509.18847)
- (arXiv'25) **ToolCritic: Detecting and Correcting Tool-Use Errors in Dialogue Systems** [[Paper]](https://arxiv.org/abs/2510.17052)
- (ICLR'25) **Learning Evolving Tools for Large Language Models** [[Paper]](https://arxiv.org/abs/2410.06617)
- (Findings of ACL'24) **MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization** [[Paper]](https://aclanthology.org/2024.findings-acl.701/)

#### Unstructured Data

- (arXiv'25) **ToolFuzz: Automated Agent Tool Testing** [[Paper]](https://arxiv.org/abs/2503.04479)
- (arXiv'26) **ToolOmni: Enabling Open-World Tool Use via Agentic Learning with Proactive Retrieval and Grounded Execution** [[Paper]](https://arxiv.org/abs/2604.13787)
- (arXiv'26) **Can Agents Generalize to the Open World? Unveiling the Fragility of Static Training in Tool Use** [[Paper]](https://arxiv.org/abs/2607.01084)
- (arXiv'26) **Towards On-Policy Data Evolution for Visual-Native Multimodal Deep Search Agents** [[Paper]](https://arxiv.org/abs/2605.10832)
- (ICASSP'26) **ReTools: Reflection-Enhanced Tool Invocation for Domain-Specific QA** [[Paper]](https://doi.org/10.1109/icassp55912.2026.11463575)
- (arXiv'26) **AudioRouter: Data Efficient Audio Understanding via RL based Dual Reasoning** [[Paper]](https://arxiv.org/abs/2602.10439)
- (PACMMOD'26) **AgenticScholar: Agentic Data Management with Pipeline Orchestration for Scholarly Corpora** [[Paper]](https://arxiv.org/abs/2603.13774)
- (arXiv'26) **LongDA: Benchmarking LLM Agents for Long-Document Data Analysis** [[Paper]](https://arxiv.org/abs/2601.02598)
- (arXiv'26) **ReTool-Video: Recursive Tool-Using Video Agents with Meta-Augmented Tool Grounding** [[Paper]](https://arxiv.org/abs/2605.13228)
- (arXiv'26) **OmniRAG-Agent: Agentic Omni-modal Reasoning for Low-Resource Long Audio-Video Question Answering** [[Paper]](https://arxiv.org/abs/2602.03707)
- (arXiv'25) **DeepSport: A Multimodal Large Language Model for Comprehensive Sports Video Reasoning via Agentic Reinforcement Learning** [[Paper]](https://arxiv.org/abs/2511.12908)

### Verification

<div align="center">
     <img width="100%" src="figures/fig5_process.png" alt="Process-level verification across the Data Agent execution trajectory">
     <p><em>Process-level verification inspects intermediate states, actions, and artifacts throughout the execution trajectory. The figure presents learned process scorers, multi-agent deliberative review, trace auditing with recovery, and process-oriented benchmarks, together with the feedback they provide for repair.</em></p>
</div>

#### Structured Data

- (arXiv'26) **Learning to Retrieve: Dual-Level Long-Term Memory for Text-to-SQL Agents** [[Paper]](https://arxiv.org/abs/2606.00547)
- (PACMMOD'26) **Reward-SQL: Boosting Text-to-SQL via Stepwise Execution-Aware Reasoning and Process-Supervised Rewards** [[Paper]](https://arxiv.org/abs/2505.04671)
- (ICLR'25) **CHASE-SQL: Multi-Path Reasoning and Preference Optimized Candidate Selection in Text-to-SQL** [[Paper]](https://arxiv.org/abs/2410.01943)
- (PACMMOD'25) **OpenSearch-SQL: Enhancing Text-to-SQL with Dynamic Few-shot and Consistency Alignment** [[Paper]](https://arxiv.org/abs/2502.14913)
- (PACMMOD'25) **λ-Tune: Harnessing Large Language Models for Automated Database System Tuning** [[Paper]](https://arxiv.org/abs/2411.03500)
- (VLDB'25) **E2ETune: End-to-End Knob Tuning via Fine-Tuned Generative Language Model** [[Paper]](https://www.vldb.org/pvldb/vol18/p5540-huang.pdf)
- (arXiv'26) **CausalFlow: Causal Attribution and Counterfactual Repair for LLM Agent Failures** [[Paper]](https://arxiv.org/abs/2605.25338)
- (PNAS'26) **Many AI Analysts, One Dataset: Navigating the Agentic Data Science Multiverse** [[Paper]](https://arxiv.org/abs/2602.18710)

#### Semi-Structured Data

- (VLDB'24) **D-Bot: Database Diagnosis System using Large Language Models** [[Paper]](https://arxiv.org/abs/2312.01454)
- (ACL'25) **Table-Critic: A Multi-Agent Framework for Collaborative Criticism and Refinement in Table Reasoning** [[Paper]](https://aclanthology.org/2025.acl-long.853/)
- (Findings of ACL'25) **STeCa: Step-level Trajectory Calibration for LLM Agent Learning** [[Paper]](https://arxiv.org/abs/2502.14276)
- (arXiv'26) **TabClaw: An Interactive and Self-Evolving Agent for Spreadsheet Manipulation and Table Reasoning** [[Paper]](https://arxiv.org/abs/2606.10316)
- (arXiv'26) **DataClaw: An Autonomous Data Agent with Instant Messaging Integration** [[Paper]](https://arxiv.org/abs/2604.24067)
- (VLDB'24) **RetClean: Retrieval-Based Data Cleaning Using LLMs and Data Lakes** [[Paper]](https://www.vldb.org/pvldb/vol17/p4421-eltabakh.pdf)
- (PACMMOD'25) **ST-Raptor: LLM-Powered Semi-Structured Table Question Answering** [[Paper]](https://arxiv.org/abs/2508.18190)
- (ACL'24) **TaPERA: Enhancing Faithfulness and Interpretability in Long-Form Table QA by Content Planning and Execution-based Reasoning** [[Paper]](https://aclanthology.org/2024.acl-long.692/)
- (arXiv'26) **FAMA: Failure-Aware Meta-Agentic Framework for Open-Source LLMs in Interactive Tool Use Environments** [[Paper]](https://arxiv.org/abs/2604.25135)
- (ADBIS'24) **LLMClean: Context-Aware Tabular Data Cleaning via LLM-Generated OFDs** [[Paper]](https://arxiv.org/abs/2404.18681)
- (EMNLP'24) **DataNarrative: Automated Data-Driven Storytelling with Visualizations and Texts** [[Paper]](https://aclanthology.org/2024.emnlp-main.1073/)
- (arXiv'26) **Towards Reliable Agentic Progressive Text-to-Visualization with Verification Rules** [[Paper]](https://arxiv.org/abs/2605.29692)
- (Findings of ACL'24) **MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization** [[Paper]](https://aclanthology.org/2024.findings-acl.701/)

#### Unstructured Data

- (arXiv'26) **Sanity Checks for Agentic Data Science** [[Paper]](https://arxiv.org/abs/2604.11003)
- (NeurIPS'24) **UQE: A Query Engine for Unstructured Databases** [[Paper]](https://arxiv.org/abs/2407.09522)
- (arXiv'26) **Failure is Feedback: History-Aware Backtracking for Agentic Traversal in Multimodal Graphs** [[Paper]](https://arxiv.org/abs/2602.03432)

### Repair

<div align="center">
     <img width="100%" src="figures/fig6_repair.png" alt="Verification-driven repair through data state reconstruction, reusable memory skills, and search-guided interventions">
     <p><em>Repair uses verification signals to reconstruct the data state, retain reusable memory skills, and guide intervention search. The figure shows checkpoint rollback, storage and retrieval of validated repairs, and the refinement of candidate interventions through re-execution and outcome feedback.</em></p>
</div>

#### Structured Data

- (arXiv'26) **AION: Next-Generation Tasks and Practical Harness for Time Series** [[Paper]](https://arxiv.org/abs/2605.25045)
- (VLDB'25) **SagaLLM: Context Management, Validation, and Transaction Guarantees for Multi-Agent LLM Planning** [[Paper]](https://arxiv.org/abs/2503.11951)
- (arXiv'26) **Learning to Retrieve: Dual-Level Long-Term Memory for Text-to-SQL Agents** [[Paper]](https://arxiv.org/abs/2606.00547)
- (arXiv'26) **CausalFlow: Causal Attribution and Counterfactual Repair for LLM Agent Failures** [[Paper]](https://arxiv.org/abs/2605.25338)
- (arXiv'26) **REFLECT: Intervention-Supported Error Attribution for Silent Failures in LLM Agent Traces** [[Paper]](https://arxiv.org/abs/2606.09071)
- (arXiv'26) **AgentFixer: From Failure Detection to Fix Recommendations in LLM Agentic Systems** [[Paper]](https://arxiv.org/abs/2603.29848)

#### Semi-Structured Data

- (arXiv'26) **kRAIG: A Natural Language-Driven Agent for Automated DataOps Pipeline Generation** [[Paper]](https://arxiv.org/abs/2603.20311)
- (arXiv'26) **Unsupervised Skill Discovery for Agentic Data Analysis** [[Paper]](https://arxiv.org/abs/2606.06416)
- (arXiv'26) **Robust Tool Use via Fission-GRPO: Learning to Recover from Execution Errors** [[Paper]](https://arxiv.org/abs/2601.15625)
- (Findings of ACL'26) **Failure Makes the Agent Stronger: Enhancing Accuracy through Structured Reflection for Reliable Tool Interactions** [[Paper]](https://arxiv.org/abs/2509.18847)
- (arXiv'25) **Multi-Objective Agentic Rewrites for Unstructured Data Processing** [[Paper]](https://arxiv.org/abs/2512.02289)
- (arXiv'26) **A Self-Healing Framework for Reliable LLM-Based Autonomous Agents** [[Paper]](https://arxiv.org/abs/2605.06737)
- (arXiv'26) **Towards Reliable Agentic Progressive Text-to-Visualization with Verification Rules** [[Paper]](https://arxiv.org/abs/2605.29692)
- (Findings of ACL'24) **MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization** [[Paper]](https://aclanthology.org/2024.findings-acl.701/)

#### Unstructured Data

- (arXiv'26) **DART: Semantic Recoverability for Structured Tool Agents** [[Paper]](https://arxiv.org/abs/2605.23311)
- (arXiv'25) **DeepAnalyze: Agentic Large Language Models for Autonomous Data Science** [[Paper]](https://arxiv.org/abs/2510.16872)
- (arXiv'26) **VectraFlow: Long-Horizon Semantic Processing over Data and Event Streams with LLMs** [[Paper]](https://arxiv.org/abs/2604.03855)
- (arXiv'26) **Doctor-RAG: A Failure-Aware Repair Framework for Agentic Retrieval-Augmented Generation** [[Paper]](https://arxiv.org/abs/2604.00865)
- (SIGIR'25) **Insight Agents: An LLM-Based Multi-Agent System for Data Insights** [[Paper]](https://arxiv.org/abs/2601.20048)
- (arXiv'26) **ReTool-Video: Recursive Tool-Using Video Agents with Meta-Augmented Tool Grounding** [[Paper]](https://arxiv.org/abs/2605.13228)

## 🔎 Open Reliability Problems

<div align="center">
     <img width="100%" src="figures/fig7_gaps.png" alt="Reliability problems in semantic calibration, clarification, experience transfer, and a shared verification–repair repository">
     <p><em>The figure illustrates four reliability problems: uncertainty is lost between stages, ambiguous requests proceed without sufficient clarification, stored repairs fail to transfer to new data environments, and a shared verification–repair repository is missing.</em></p>
</div>

## 🏆 Benchmark

| Dataset | Analytical Task | Focus | Evaluation | Paper | Repo |
| --- | --- | --- | --- | --- | --- |
| StockGQL | Data Querying and Information Seeking | Natural-language-to-GQL translation over structured financial knowledge, requiring interpretation of user questions and executable graph query generation. | Evaluates query correctness and whether generated queries retrieve the information required by the question. | [Paper](https://aclanthology.org/2024.findings-emnlp.800/) | — |
| TableBench | Data Querying and Information Seeking | Complex table question answering covering fact checking, numerical reasoning, data analysis, and visualization. | Evaluates TableQA performance across multiple reasoning categories using curated test cases. | [Paper](https://arxiv.org/abs/2408.09174) | [Code](https://github.com/TableBench/TableBench) |
| Visual-TableQA | Visualization and Multi-modal Analysis | Visual reasoning over rendered table images, including table structure understanding and multi-step reasoning. | Measures question-answering and reasoning accuracy on visually presented tables. | [Paper](https://arxiv.org/abs/2509.07966) | — |
| TopBench | Analysis and Prediction | Implicit predictive reasoning over tabular data, including prediction, decision making, and treatment-effect analysis. | Evaluates whether models can infer analytical objectives beyond direct table lookup. | [Paper](https://arxiv.org/abs/2604.28076) | [Data](https://huggingface.co/datasets/LAMDA-Tabular/TopBench) |
| PrepBench | Data Preparation and Transformation | Natural-language-driven data preparation involving cleaning, restructuring, and table transformation. | Evaluates the correctness of generated output tables across different preparation settings. | [Paper](https://arxiv.org/abs/2605.08687) | — |
| LongDS-Bench | Analysis and Prediction | Long-horizon, multi-turn data science tasks with evolving analytical states and intermediate results. | Measures turn-level accuracy and the ability to complete extended analytical trajectories. | [Paper](https://arxiv.org/abs/2605.30434) | — |
| DAComp | Cross-task | Data engineering and open-ended data analysis across the data-intelligence lifecycle. | Combines execution-based metrics for data engineering with rubric-based evaluation for open-ended analysis. | [Paper](https://arxiv.org/abs/2512.04324) | [Code](https://github.com/ByteDance-Seed/DAComp) |
| FDABench | Cross-task | Data analysis over heterogeneous structured, unstructured, and multimodal sources. | Evaluates analytical correctness, report quality, latency, and token consumption. | [Paper](https://arxiv.org/abs/2509.02473) | [Code](https://github.com/fdabench/FDAbench) |
| CODA-BENCH | Analysis and Prediction | Data-intensive code-agent tasks requiring data discovery, code generation, and execution. | Evaluates data discovery and successful completion of executable analytical tasks. | [Paper](https://arxiv.org/abs/2606.15300) | [Website](https://coda-bench.github.io/) |
| DataSciBench | Analysis and Prediction | Data science tasks requiring agents to generate and execute analytical programs. | Uses programmatic evaluation of generated programs and their execution results. | [Paper](https://arxiv.org/abs/2502.13897) | [Website](https://datascibench.github.io/) |
| AgentGym | Cross-task | Real-world agent tasks involving tool discovery, selection, and multi-step interaction with external resources. | Evaluates task success and tool-use behavior across interactive environments. | [Paper](https://arxiv.org/abs/2406.04151) | [Website](https://agentgym.github.io/) |
| FinRpt | Analysis and Prediction | Equity research report generation integrating information from multiple financial data sources. | Evaluates generated reports using a multi-dimensional assessment of report quality. | [Paper](https://arxiv.org/abs/2511.07322) | — |
| PolitNuggets | Data Querying and Information Seeking | Agentic discovery and synthesis of long-tail facts from dispersed information sources. | Evaluates evidence discovery, fine-grained factual accuracy, and information-seeking efficiency. | [Paper](https://arxiv.org/abs/2605.14002) | — |

### Additional Benchmark Papers

- (arXiv'25) **Beyond Seeing: Evaluating Multimodal LLMs on Tool-Enabled Image Perception, Transformation, and Reasoning** [[Paper]](https://arxiv.org/abs/2510.12712)
- (arXiv'26) **Navigating Large-Scale Document Collections: MuDABench for Multi-Document Analytical QA** [[Paper]](https://arxiv.org/abs/2604.22239)
- (arXiv'26) **DSAEval: Evaluating Data Science Agents on a Wide Range of Real-World Data Science Problems** [[Paper]](https://arxiv.org/abs/2601.13591)
- (ACL'26) **UniDataBench: Evaluating Data Analytics Agents Across Structured and Unstructured Data** [[Paper]](https://aclanthology.org/2026.acl-long.1556.pdf)
- (arXiv'26) **AllocBench: Measuring Online Tool Allocation Capability in LLM Agents** [[Paper]](https://arxiv.org/abs/2607.23332)
- (arXiv'26) **6GAgentGym: Tool Use, Data Synthesis, and Agentic Learning for Network Management** [[Paper]](https://arxiv.org/abs/2603.29656)
- (ICLR'26) **ReWatch-R1: Boosting Complex Video Reasoning in Large Vision-Language Models through Agentic Data Synthesis** [[Paper]](https://arxiv.org/abs/2509.23652)

## 📦 Projects

### Open-source Projects

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ucbepic/docetl) DocETL: Agentic Query Rewriting and Evaluation for Complex Document Processing
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/microsoft/Jupiter) Jupiter: Enhancing LLM Data Analysis Capabilities via Notebook and Inference-Time Value-Guided Search
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TencentBigData-SiriusAI/SiriusBI) SiriusBI: A Comprehensive LLM-Powered Solution for Data Analytics in Business Intelligence
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RUCKBReasoning/E2ETune) E2ETune: End-to-End Knob Tuning via Fine-Tuned Generative Language Model
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Chen-GX/ToolEVO) Learning Evolving Tools for Large Language Models
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yale-nlp/MCTS-RAG) MCTS-RAG: Enhancing Retrieval-Augmented Generation with Monte Carlo Tree Search
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/thunlp/MatPlotAgent) MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDataBox/ST-Raptor) ST-Raptor: LLM-Powered Semi-Structured Table Question Answering
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TsinghuaDatabaseGroup/DB-GPT) D-Bot: Database Diagnosis System using Large Language Models

### Interactive Data Assistance

- [Fabi Analyst Agent](https://www.fabi.ai/product/analyst-agent): Natural-language analysis, Python and SQL computation, dashboards, and collaborative access.
- [V7 AI Spreadsheet Analysis Agent](https://www.v7labs.com/agents/ai-spreadsheet-analysis-agent): Spreadsheet questions, calculations, summaries, and visualizations.

### Collaborative Analytical Work

- [GPT for Work](https://gptforwork.com/about): Formula generation and repair, data cleaning, charts, pivot tables, and bulk row processing in Excel and Google Sheets.
- [Codex](https://openai.com/codex/): Data, code, and analytical artifacts within a shared workflow.

### Autonomous Data Workflows

- [Snowflake CoCo](https://www.snowflake.com/en/developers/guides/getting-started-with-coco-desktop/): Multi-step data engineering, analytics, machine learning, and agent-building tasks.
- [Snowflake Cortex Agents](https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents): Structured data access, unstructured retrieval, and code execution within a governed workflow.
- [Databricks Genie Code](https://docs.databricks.com/aws/en/genie-code): Planning, data retrieval, code generation and execution, output inspection, and error recovery.
- [Manus](https://manus.im/): Spreadsheet and CSV analysis, charts, reports, and reusable workflows.

### Knowledge-Intensive Discovery

- [Manus](https://manus.im/): External research, evidence synthesis, structured analysis, and report generation.
- [Pelayar Spreadsheet Agent](https://pelayar.ai/ai-excel/): Extracting information from PDFs, invoices, images, and other documents into spreadsheets for analysis.

## 📃 Citation


