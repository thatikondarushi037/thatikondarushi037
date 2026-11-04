Hi, I'm Rushi Thatikonda 👋
AI & Machine Learning Systems | Secure Backend Engineering | Network Security

I'm a Computer Science graduate and CCNA-certified engineer building hands-on projects at the intersection of machine learning, security, networking, and reliable software systems. I focus on how systems work end to end—from data and models to APIs, databases, orchestration, testing, and deployment.
🚀 Featured Projects
🛡️ AegisOps — AI-Powered Incident Investigation
Python · FastAPI · PostgreSQL · SQLAlchemy · Alembic · Docker · n8n · Ollama · RAG
- Built an incident-ingestion and investigation backend with PostgreSQL persistence, service-level deduplication, protected REST endpoints, and migration-tested database integrity.
- Added RAG-assisted root-cause investigations using local Ollama models and runbook retrieval, with stored evidence, recommendations, investigation history, and a human-approval boundary.
- Implemented a durable automatic investigation worker with PostgreSQL job claims, recovery leases, bounded retries, and atomic result persistence.
- Integrated authenticated n8n alert ingestion with input validation, retry handling, and local runtime verification. The v0.16 regression suite reports 95 passed, 1 skipped.
🔐 TrustShield AI Gateway — Privacy-Aware LLM Gateway
Python · scikit-learn · FastAPI · Streamlit · SQLite · Ollama
- Developed hybrid TF-IDF + Logistic Regression and rule-based detection for potentially sensitive prompts.
- Enforced ALLOW / BLOCK / HOLD decisions before model forwarding, with a review queue, redaction endpoints, and fail-closed handling.
- Built a Streamlit dashboard with authenticated, metadata-only SQLite audit monitoring and encrypted local token configuration.
- Evaluation currently relies on a small synthetic sample; broader independent validation and deployment hardening remain future work.
🌐 SentinelForge AI — Network Packet Intelligence
Python · Linux · PCAP · TShark · Network Protocols · Security Testing
- Completed a streaming, metadata-only PCAP processing engine that extracts packet facts without exporting payload contents.
- Added bounded parsing, malformed-packet handling, and atomic output publication to support safer offline investigations.
- Verified milestone one with 53 passing tests, 96 TShark-matched synthetic packet records, and deterministic robustness checks.
- Current scope: packet intelligence foundation; ML and RAG capabilities have not yet been implemented.
🧠 BitForge-300M — Ternary Transformer Research
Python · PyTorch · CUDA · Transformers · Quantization · Reproducible Benchmarks
- Completed five engineering milestones covering ternary-weight quantization, a tiny decoder-only Transformer, offline text training, controlled FP32-versus-ternary comparisons, and a versioned packed-checkpoint format.
- Implemented reproducible evaluation tools, checkpoint validation, offline generation, and integrity-checked packed-weight reconstruction.
- Measured 87,324 bytes for a packed tiny-model weights file versus 335,225 bytes for its original weights-only file.
- Scope: the approximately 300M-parameter architecture is an estimated target; no 300M model has been trained or instantiated.
🧰 Technical Toolkit
Area	Technologies
AI / ML	PyTorch, scikit-learn, Transformers, quantization, embeddings, RAG, Ollama
Backend & Data	Python, FastAPI, SQLAlchemy, PostgreSQL, SQLite, Alembic, REST APIs
DevOps & Automation	Docker, n8n, Git, GitHub, pytest, Linux, Windows
Networking & Security	TCP/IP, DNS, routing, switching, Wireshark/TShark, PCAP analysis, access controls
Other	AWS fundamentals, HTML, CSS, JavaScript, Streamlit


🎓 Background
- B.Tech in Computer Science Engineering (2024)
- Cisco Certified Network Associate (CCNA) — completed September 2024
- Previous academic projects: Secure Mobile Edge Computing Networks and Secure Decentralized IIoT Data Marketplace.
📌 Current Focus
I'm strengthening the evaluation, reliability, and security of practical AI systems while expanding my knowledge of machine learning engineering and network security. Each repository documents what is implemented, what has been tested, and what remains experimental.
📫 Connect
Email: thatikondarushi037@gmail.com
Thanks for visiting. I enjoy building systems that I can explain, test, and improv
