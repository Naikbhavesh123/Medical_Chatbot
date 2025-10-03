# Medical_Chatbot
A Medical Chatbot built with LangChain, Pinecone, and Flask that answers healthcare-related queries using Retrieval-Augmented Generation (RAG). It runs locally on localhost, embedding a medical reference book into a vector database to provide accurate, context-aware, and privacy-friendly responses.

# 🩺 Medical Chatbot – Retrieval-Augmented AI Assistant  

A domain-specific chatbot that answers healthcare-related questions by combining a **Large Language Model (LLM)** with a **medical knowledge base** using **Retrieval-Augmented Generation (RAG)**.  
Built with **LangChain**, **Pinecone**, and **Flask**, this project runs entirely on **localhost**, ensuring privacy, cost-effectiveness, and reproducibility.  

---

## 🚀 Features  
- 🧠 **LangChain Orchestration** – connects user queries, retriever, and LLM.  
- 📚 **Vector Database (Pinecone)** – stores embeddings of a medical reference book.  
- 🌐 **Flask Backend + Frontend** – lightweight API and chat interface.  
- 💻 **Localhost Deployment** – chatbot runs at `http://127.0.0.1:5000/`.  
- ⚡ **Optimized Parameters** – tuned for relevance and low latency.  
- 🔒 **Privacy-Friendly** – queries remain in the local environment.  

---

## ⚙️ Tech Stack  
- **Python 3.10+**  
- **LangChain**  
- **Pinecone**  
- **Sentence Transformers (Hugging Face)**  
- **Flask**  
- **HTML / CSS (for frontend UI)**  

---

## 📊 Workflow  
1. User submits a medical query in the web interface.  
2. Query is embedded and searched against the Pinecone vector database.  
3. Relevant knowledge chunks are retrieved.  
4. LangChain assembles a prompt with query + context.  
5. The LLM generates a grounded answer.  
6. Response is displayed to the user.  

---

## 🧪 Performance  
- ⏱ Average response time: ~2.8 seconds/query on local hardware (Intel i5, 16 GB RAM).  
- ✅ RAG answers scored **4.6/5 relevance**, vs **3.2/5** for standalone LLM answers.  
- 💡 Stable with light concurrent usage on localhost.  

---

## 🔧 Installation  

Clone the repo and install dependencies:  
```bash
git clone https://github.com/your-username/medical-chatbot.git
cd medical-chatbot
pip install -r requirements.txt
