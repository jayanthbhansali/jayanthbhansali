# Hi, I'm Jayanth Bhansali!

💻 I'm an Applied AI/ML and data engineering professional specializing in GenAI orchestration, LLMOps on cloud platforms, and RAG pipelines. My work focuses on improving machine learning systems and deploying robust data solutions. Co-authored three papers accepted at IEEE SmartNets 2026 spanning deep learning, computer vision, and edge AI.

---

## 🚀 Projects

- 🎓 **TerpAgent: Your Autonomous College Life Agent (UMD)**
  - Built a FastAPI + Pydantic backend on Claude Sonnet 4.5 with 35 tool schemas across 53 endpoints for 11 UMD services; engineered an 8-round agentic loop with conversation memory and parallel tool dispatch to resolve multi-step requests in a single turn.
  - Designed /match endpoints returning score, and blockers sourced from data to prevent LLM rationale hallucination; deployed on EC2 with Docker Compose with a heuristic fallback for 100% uptime, validated by a 13-case pytest suite.
 
  - [Repository →](https://github.com/jayanthbhansali/terp-agent)

- 🛡️ **PatchGuard.ai: Risk-Aware Software Upgrade Orchestrator**
  - Designed a responsible AI-informed risk scoring model ingesting live CVE/KEV/EPSS feeds across 1500+ CVEs, ranking upgrade plans by exploit probability, dependency blast radius, and operational impact.
  - Built a 6-agent LangGraph + Gemini ReAct pipeline with an evaluation harness measuring patch precision and rollback rates under canary deployment, exposed via a FastAPI service with 35+ endpoints.
  - [Repository →](https://github.com/jayanthbhansali/PatchGuard.ai)
 
- 🚛 **Scania Component X: Predictive Failure Detection & Time Series Modeling**
  - Built BiLSTM and Deep LSTM models on Scania truck sensor time series; tuned decision thresholds to cut evaluation cost by 37% vs. baseline while minimizing false negatives on safety-critical failures.

- 🎵 **Stream Your Mood: Multimodal Recommendation System**
  - Developed a multimodal emotion-based music recommendation system using Haar Cascades + VGG16, achieving 83.2% accuracy with low-latency Streamlit deployment.
  - [Publication →](https://www.ijltemas.in/DigitalLibrary/Vol.9Issue11/18-23.pdf)
  - [Repository →](https://www.github.com/JayanthBhansali/StreamYourMood)

- 📚 **K-12 ML Support: Personalized Lesson Planning with Multilingual RAG**
  - Architected a personalization-aware RAG pipeline with Llama 3.3 70B for curriculum-aligned K-12 lesson plans and a retrieval evaluation framework scoring chunk relevance and alignment accuracy, cutting prep time by 2–3 hours per plan.
  - [Repository →](https://github.com/jayanthbhansali/k-12mlsupport)

- 🌱 **TezFarming: CNN-Based Crop Pest Detection**
  - Conducted a comparative analysis of AlexNet, Inception-V3, ResNet-50, and VGG-16 for early-stage leaf pest identification, identifying ResNet-50 as the top performer with up to 99.3% accuracy across crops like grapes, potato, and bell pepper.
  - [Publication →](https://ieeexplore.ieee.org/document/9686499/)

---

## 💼 Experience

- **Graduate Teaching Assistant @ University of Maryland**
  - Graduate Researcher under Dr. Nestor Tiglao 
  - Led weekly lab sessions for 30+ students in Machine Learning, designing PyTorch exercises covering neural networks, classification metrics, and hyperparameter tuning.
  - Co-mentored undergraduate research, contributing to 3 papers accepted for oral presentation at IEEE SmartNets 2026.


- **AI Developer Intern @ Methix**
  - Optimized production inference pipeline through prompt restructuring, tool routing, and LangSmith trace analysis, cutting P95 latency by 465ms and token cost by 40% with no quality regression.
  - Evaluated a NoSQL-driven collaboration recommender built from natural-language requests on Azure AI Foundry endpoints using an LLM-as-a-Judge framework, establishing proxy relevance metrics in the absence of labeled ground truth.
  - Designed a hierarchical RAG retrieval pipeline over Azure Cosmos DB data stores using dense retrieval, cross-encoder reranking, and MMR diversification, improving Precision@8 from 0.74 to 0.82 while reducing redundant context.
  - Architected a LangGraph + ReAct multi-agent orchestrator across RAG, collaborator, and web search agents, benchmarking routing on a labeled evaluation dataset of 200+ diverse queries to reach 92% routing accuracy against ground truth.


- **Data Scientist @ Infosys Limited**
  - Built an end-to-end ML training pipeline using XGBoost for booking-cancellation prediction on 3M+ records, engineering 40+ features and tuning via stratified k-fold cross-validation to drive an estimated ~1.2% OpEx impact across APAC.
  - Re-engineered ETL and data ingestion workflows using SQL and QVD, setting up scheduled cron jobs to automate refreshes, eliminating a legacy bottleneck to deliver 4x daily refresh frequency and cut reload latency by 70%.
  - Partnered with business stakeholders to diagnose demurrage and detention (D&D) spend via cohort analysis and production SQL data models, which was adopted as a source of truth by ops and finance teams and drove an 8% cost reduction.
  - Led a 5-member analytics team designing Power BI and Qlik Sense executive dashboards for 25+ business teams, replacing manual reporting and saving 225+ weekly hours.


- **Software Developer Intern @ TCS**
  - Developed a dynamic pricing prediction pipeline using XGBoost, compared performance against Decision Tree and Polynomial Regression models, and achieved a best ROC-AUC of 0.83.

---

## Contact
- 🌐 [LinkedIn](https://www.linkedin.com/in/jayanthbhansali/)
- 📧 Email: jayanthb@terpmail.umd.edu
