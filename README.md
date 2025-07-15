# Eventra-AI

**Eventra-AI** is an agentic AI-powered framework for automating and enriching Level 1 SOC (Security Operations Center) workflows. Built on LangGraph and LangChain, the system uses modular LLM-based agents to process raw logs, detect anomalies, enrich threat data, and orchestrate responses with human-in-the-loop capability and explainability.

---

## 🚀 Features

- 🔍 **Log Ingestion & Detection** – Analyze raw security logs to identify suspicious activity
- 🧠 **MITRE ATT&CK Mapping** – Classify alerts into tactics & techniques
- 📊 **Contextual Enrichment** – Add user, geo, and behavioral insights
- 🤖 **Remediation Planning** – Generate and simulate response actions (block, isolate, notify)
- 🧑‍💼 **Human-in-the-Loop** – Wait for analyst approval when trust is medium/low
- 📚 **Explainability** – Translate complex findings into clear, SOC-ready summaries
- 🧪 **Simulation & Training** – Learn from past alerts to improve detection logic

---

## 🧱 Architecture Overview

Eventra-AI uses a layered agentic structure:
Level 1: Omni Agent - Oversees all workflows
Level 2: Log Parsing & Detection
Level 3: Enrichment (TI, context, correlation)
Level 4: Validation & Explainability
Level 5: Decision & Response
Level 6: Trust Calibration & Feedback
Level 7: Case Summarization & Analyst Copilot


Use Case Examples
Summarize a suspicious login attempt

Classify a brute-force attack with MITRE technique

Suggest automated remediation steps with LLM reasoning

Provide analyst-ready case summaries for reporting

📜 Disclaimer
This project was created independently for research and learning purposes. No company data, systems, or intellectual property were used. All development occurred on personal time using personal hardware, in alignment with professional ethical standards.

🤝 Contributing
Contributions are welcome! Feel free to submit pull requests or open issues with ideas or improvements.


