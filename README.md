# Input Sanitization + Retrieval Hardening for RAG

## Project Overview
This project evaluates and implements defenses against prompt injection attacks in Retrieval-Augmented Generation (RAG) systems. We compare different input sanitization and retrieval hardening strategies to reduce data exfiltration and injection success rates.

## Scope & Target
**In Scope:**
- RAG chatbot with local document knowledge base
- Prompt injection attack simulations
- Defense implementations (input sanitization, retrieval isolation, filters)
- Evaluation metrics (injection success rate, leakage rate, usability impact)

**Out of Scope:**
- Real-world system attacks
- Production deployment

## Setup Plan
1. Clone this repository
2. Install dependencies (Python 3.9+, required packages in `requirements.txt`)
3. Set up a local RAG environment with sample documents
4. Run baseline vulnerability tests
5. Implement defenses and re-test
6. Generate evaluation reports

## Tools
- **Python 3.9+** — Core language
- **LangChain or similar** — RAG framework
- **Prompt injection test suite** — Custom or existing (e.g., OWASP)
- **Local document store** — For RAG knowledge base
- **Metrics collection** — For before/after analysis

## Project Direction
**Week 2:** Set up RAG baseline + document baseline vulnerabilities
**Week 3:** Implement defenses (input sanitization, retrieval filters, prompt firewalls)
**Week 4:** Evaluate effectiveness and compile final report
**Week 5:** Prepare presentation

## Getting Started
```bash
git clone https://github.com/naa39c/Project.git
cd Project
pip install -r requirements.txt
python main.py
```

## Repository Structure
- `/docs` — Project documentation and reports
- `/evidence` — Test results and evaluation metrics
- `/report` — Final report and findings
- `/src` — Source code
- `README.md` — This file
- `requirements.txt` — Python dependencies

