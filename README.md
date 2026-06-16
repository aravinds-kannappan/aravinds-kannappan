# Hi, I'm Aravind Kannappan 👋

I’m a Statistics master’s student at NYU with a background in sports analytics and machine learning. I’m interested in building production ML systems in domains like sports, healthcare & AI Safety where decisions are time-sensitive and data is messy, high-dimensional, and constantly shifting.

I’m especially drawn to work that makes complex models reliable in real-world environments — whether that’s powering live analytics or supporting clinical decision systems — and I care about building infrastructure that teams can trust and iterate on safely.

## 🎓 Education
* **M.S. in Applied Statistics** (ML Specialization), NYU (2024–2026)
* **B.S. in Statistics** (Sports Analytics), Baylor University (2020–2024)

## 🔍 Interests
* LLM serving, inference & evaluation
* AI safety, interpretability & model reliability
* MLOps & production ML systems
* PyTorch, distributed training, model optimization
* Causal inference & experimental design
* Biostatistics & healthcare ML

## 🚀 Startups
* **[Replays AI](https://replays-ai.vercel.app/)** – Personalized sports fan platform that turns live ESPN play-by-play into AI-generated recaps, predictions, and fan experiences. Built a four-agent pipeline (event extraction, Claude Vision play classification, parallel LLM summarization, and team-perspective recaps) running concurrently for sub-second responses, plus a gamification layer of predictions, rosters, and leaderboards. React/TypeScript + FastAPI, deployed on Vercel with no database (data derived live from public ESPN endpoints).
* **[Synthure](https://synthure.vercel.app/)** – Multi-agent clinical AI platform: a single clinical note enters once and specialized agents handle prior authorizations, claims routing, denial prediction, patient education, and appeals across patient, physician, hospital, and employer portals. RAG over 1.43M ICD-10 codes (MRR@5 0.91), a gradient-boosting denial predictor (AUC 0.87), and citation-validated generation behind a three-tier autonomy model. NER accuracy 94.2%, insurance-plan match 91.3%, p95 latency 1.8s, zero fabricated clinical facts.

## 🛠️ Projects
* **[Popper](https://github.com/aravinds-kannappan/Popper)** – Open-source tool that hunts for counterexamples to mathematical and logical specifications *before* they’re formally proven; Monte-Carlo math engine plus live Lean/AXLE spec checks. Catches 99% of unfaithful specs with zero false alarms and always returns a concrete counterexample.
* **[MOSAIC](https://github.com/aravinds-kannappan/MOSAIC)** – Bayesian multi-stream outbreak early warning that fuses wastewater, genomic, and outbreak-text data into a calibrated `P(Rt > 1)` (ECE 0.086, AUROC 0.917 on the CDC record, ~68-day median lead).
* **[RallyScope](https://github.com/aravinds-kannappan/Rally-Scope)** – Tennis ML & in-browser computer vision over 36K+ ATP/WTA matches: a from-scratch PCA playstyle map, an exactly-explainable win-probability model, and a canvas ball tracker — trained at build time, inferred client-side.
* **[Context Forge](https://github.com/aravinds-kannappan/Context-Forge)** – Reproducible benchmark of prompt/context compression (tokens saved vs. quality retained vs. latency) across the GPT-4o, GPT-4, and GPT-2 tokenizers, plus a learned per-token droppability classifier (ROC-AUC 0.964).
* **[PodBench](https://github.com/aravinds-kannappan/PodBench)** – Deterministic, resettable task environments for LLM agents with a programmatic verifier, per-run token/cost metering, and Kubernetes (KEDA) autoscaling — pod health and model behavior on one pane.
* **[VeriGrad RL](https://github.com/aravinds-kannappan/VeriGrad-RL)** – Mechanistic-interpretability lab for safety RL: a policy chooses activation-level interventions on a transparent residual-stream circuit, scored for safety, utility retention, and mechanistic faithfulness.
* **TrafficFlowOpt** – City-scale traffic simulator in CUDA (25X speedup); PyTorch signal optimizer reducing network delay 23%.

## 💻 Tech Stack
**Languages:** Python • R • SQL • C++ • CUDA • TypeScript / Next.js

**ML & Data:** PyTorch • TensorFlow • Scikit-learn • XGBoost • Hugging Face • Pandas • NumPy

**Cloud & Infra:** AWS • GCP • Vercel • Supabase • Kubernetes • Snowflake • Apache Airflow

## 📚 Related Activities
* Technical writer on ML optimization & probabilistic modeling at NYU
* Coding instructor teaching algorithms & logic to middle school students

## Additional Interests 
* Chess, Sports Analytics (NFL & NBA) 

---

🌐 **[LinkedIn](https://linkedin.com/in/aravind-kannappan)**
