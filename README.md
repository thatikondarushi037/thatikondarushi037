# Hi, I'm Rushi Thatikonda 👋

**M.Sc. Computer Science @ RPTU | AI & ML Engineering | Backend Systems | Network Security**

I'm pursuing a **Master of Science in Computer Science at RPTU University of Kaiserslautern-Landau, Germany** and hold the **Cisco Certified Network Associate (CCNA)** certification. I build practical systems at the intersection of machine learning, reliable backend engineering, and network security.

I focus on understanding systems end to end - from models and data to APIs, databases, automated workflows, evaluation, security, and deployment. I document what works, how it was tested, and where its limitations are.

## 🚀 Featured Projects

### 🛡️ [AegisOps — AI-Powered Incident Investigation](https://github.com/thatikondarushi037/aegisops)
**Python · FastAPI · PostgreSQL · SQLAlchemy · Alembic · Docker · n8n · Ollama · RAG · JavaScript**

- Built an authenticated incident-ingestion and investigation application with **PostgreSQL deduplication**, atomic job scheduling, migration-tested persistence, and a durable worker with recovery leases and bounded retries.
- Implemented **local Ollama + runbook RAG investigations** that store evidence, recommendations, and human-approval state; AI-generated recommendations never execute remediation automatically.
- Added a browser dashboard with filters, job states, saved evidence, and a **read-only AI assistant with source citations**.
- **v1.0 release candidate:** complete local Python rerun reported **159 passed, 0 failed, 2 skipped**; the two optional real-model tests passed separately, and **6 frontend tests passed**.
- **Scope:** demonstrable local project, not a production deployment or autonomous remediation platform.

### 🔐 [TrustShield AI Gateway — Privacy-Aware LLM Gateway](https://github.com/thatikondarushi037/trustshield-ai-gateway)
**Python · scikit-learn · FastAPI · Streamlit · SQLite · Docker · Ollama**

- Developed **hybrid TF-IDF + Logistic Regression and rule-based detection** for potentially sensitive prompts, supplemented by secret-pattern checks.
- Implemented server-side **ALLOW / HOLD / BLOCK** enforcement before LLM execution, with redaction, review/rewrite flows, conservative failure handling, and metadata-only audit persistence.
- Built a **Streamlit operations console** for prompt analysis, persistent security analytics, reviews, ML experiment reports, and downstream health; containerized API and dashboard services.
- **v1.0 release candidate:** **130 regression tests passed** in local release preparation. Evaluation reports document substantial generalization failures and dataset limitations.
- **Scope:** local engineering and ML research prototype; no independent holdout validation or production-grade privacy guarantee.

### 🌐 [SentinelForge AI — Network Packet Intelligence](https://github.com/thatikondarushi037/sentinelforge-ai)
**Python · Linux · PCAP · TShark · Networking · Security Testing**

- Implemented a **streaming, metadata-only classic Ethernet PCAP parser**, extracting packet facts without exporting payloads or credentials.
- Added bounded parsing, malformed-packet handling, and private atomic output publication without overwriting existing files.
- Verified milestone one with **53 passing tests**, **96 TShark-matched synthetic packet records**, and **2,000 deterministic malformed-packet mutations**.
- **Scope:** packet-intelligence foundation completed; ML, RAG, and live capture remain future work.

### 🧠 [BitForge-300M — Ternary Transformer Research](https://github.com/thatikondarushi037/BitForge-300M)
**Python · PyTorch · CUDA · Transformers · Quantization-Aware Training · Model Compression**

- Built a **297,059,328-parameter BitNet-inspired decoder architecture** and verified real full-model forward execution on **CPU and RTX 4060 Laptop GPU**.
- Implemented ternary-weight quantization, quantization-aware experiments, integrity-checked **two-bit packed checkpoints**, offline generation, and reproducible benchmark tools.
- Measured **6.02× full-model checkpoint compression**: **1,188,291,675 bytes** (dense) versus **197,365,045 bytes** (packed), with validated reconstruction.
- Separately trained a **1.38M-parameter demo model** for 600 updates. Paired quantizer experiments did not demonstrate consistent quality improvement.
- **74 release tests passed**, including 3 full-model tests. **Scope:** the full ~297M architecture is randomly initialized, not pretrained; packed weights reconstruct to dense floating-point tensors and do not use native ternary CUDA kernels.

## 🛠️ Technical Skills

**Programming & Web:** Python, SQL, HTML, CSS, JavaScript  
**Machine Learning & AI:** PyTorch, scikit-learn, NLP, TF-IDF, Logistic Regression, Transformers, embeddings, RAG, weight quantization, Ollama  
**Backend & Data:** FastAPI, REST APIs, SQLAlchemy, Alembic, PostgreSQL, SQLite  
**DevOps & Engineering:** Docker, Docker Compose, Git, GitHub, pytest, n8n, Streamlit, Linux, Windows  
**Networking & Security:** TCP/IP, DNS, routing and switching, OSPF, EIGRP, BGP, VLANs, ACLs, Wireshark, TShark, PCAP analysis  
**Cloud:** AWS fundamentals, Amazon S3, static website hosting

## 🎓 Education & Certifications

- **Master of Science (M.Sc.), Computer Science — In progress**  
  RPTU University of Kaiserslautern-Landau, Germany
- **Bachelor of Technology (B.Tech.), Computer Science Engineering — 2024**
- **Cisco Certified Network Associate (CCNA) — September 2024**

**Earlier academic projects:** Secure Mobile Edge Computing Networks; Secure Decentralized IIoT Data Marketplace.

## 🎯 Current Focus

I'm developing a deeper understanding of **ML evaluation and generalization, secure local AI, backend reliability, and network security**. My repositories distinguish verified engineering work from experiments and proposed improvements.

## 📫 Connect

**Email:** [thatikondarushi037@gmail.com](mailto:thatikondarushi037@gmail.com)  
**GitHub:** [@thatikondarushi037](https://github.com/thatikondarushi037)

---

*I enjoy building systems that I can explain, test, measure, and improve.*
