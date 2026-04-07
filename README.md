# Cargowise-document-intelligence-agent
AI agent that parses shipping documents and checks customs compliance using LangChain + Groq
# 🚢 CargoWise Document Intelligence Agent

An Agentic AI system that automatically parses international 
shipping documents, extracts customs fields, and performs 
compliance checks — built to solve real logistics automation 
problems.

## 🎯 What it does
- Parses Bill of Lading & Commercial Invoice PDFs
- Extracts 20+ customs fields using LLM (Groq/LangChain)
- Checks compliance against international shipping rules
- Flags missing UN declarations, HS code mismatches, 
  incomplete fields
- Generates a risk score (LOW / MEDIUM / HIGH) with 
  actionable recommendations

## 🧠 Tech Stack
- LangChain — Agentic RAG pipeline
- Groq LLM — Field extraction & compliance reasoning
- PyMuPDF — PDF text extraction
- FAISS — Vector similarity search
- Python 3.10+

## 📋 Sample Output
Risk Level: 🟡 MEDIUM (Score: 60/100)
✗ Lithium battery goods missing UN declaration
✗ HS code mismatch with goods description
✓ Declared value has correct currency
✓ Country of origin is specified

## 🚀 How to run
pip install -r requirements.txt
python agent.py sample_shipment.pdf

## 💡 Built for
This project was inspired by WiseTech Global's CargoWise 
platform and the real-world problem of automating customs 
document compliance in international logistics.

## 👩‍💻 Author
Devanshi Raj — AI Engineer
GitHub: github.com/Devanshi-navi
LinkedIn: linkedin.com/in/devanshi-raj-15642a28b
