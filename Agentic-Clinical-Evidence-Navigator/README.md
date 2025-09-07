# Agentic Clinical Evidence Navigator

🚀 **Overview**  
This project is a Retrieval-Augmented Generation (RAG) system designed for biomedical research. It dynamically scrapes PubMed and ClinicalTrials.gov, embeds findings in a Chroma vector database, and uses Ollama-powered LLMs with CrewAI agents to analyze and synthesize results into actionable clinical reports.

---

## 🔑 Key Features
- 🔍 **Dynamic Retrieval:** Live scraping of PubMed and ClinicalTrials.gov  
- 🧠 **Agentic Orchestration:** Multi-step reasoning via CrewAI  
- 📚 **Structured Storage:** SQLite metadata DB + Chroma vector store  
- 💡 **LLM-Powered Analysis:** Summaries, grading, recommendations, and evidence gaps  
- 💻 **CLI Interface:** Simple commands for querying and exploring results  

---

## 🛠️ Tech Stack
- **LLMs:** Ollama (Mistral, Llama, etc.)  
- **Agents:** CrewAI  
- **Vector DB:** Chroma  
- **Scrapers:** PubMed & ClinicalTrials.gov APIs  
- **Backend:** Python 3.9+, SQLite, BeautifulSoup, Requests
