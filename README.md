Multi-Agentic System with Dynamic Decision Making

 Overview
This project builds a multi-agent AI system that dynamically decides which agents (PDF RAG, Web Search, ArXiv) to call for user queries. It features:
- Flask or FastAPI backend
- Minimal frontend with search box and PDF upload
- LLM orchestration via Groq or Google AI Studio Gemini
- Controller logs decisions with rationale

Features
- Intelligent controller routing queries and logging decisions
- PDF RAG agent extracts and retrieves information from uploaded PDFs
- Web Search agent fetches real-time web results
- ArXiv agent fetches and summarizes academic papers
- Secure PDF upload and data privacy
- Traceable logs and deployment-ready

Setup
1. Clone repo
2. Install dependencies: `pip install -r requirements.txt`
3. Set API keys as environment variables
4. Run backend server: `python run.py`
5. Access frontend UI to upload PDFs or input queries

Usage
Upload PDFs or type queries to get answers routed by agents with rationale and full logging.

Folder Structure
- `agents/` – individual agents and controller
- `frontend/` – UI components
- `samplepdfs/` – demo PDFs for RAG
- `logs/` – decision and interaction logs
- `tests/` – unit and integration tests
- `deployment/` – deployment scripts and instructions

Deliverables
- Modular backend and frontend
- Deployment scripts and instructions
- Sample PDFs and logs
- Documentation including architecture and decision logic
