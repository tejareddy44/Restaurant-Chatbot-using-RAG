# Restaurant-Chatbot-using-RAG
# 🍴 RAG-Powered Restaurant Chatbot  
 
A **Retrieval-Augmented Generation (RAG) Chatbot** that helps restaurants deliver instant, conversational, and context-aware responses to customer queries. It provides quick answers about menus, policies, and services using semantic search and a powerful language model.  
 
---
 
## 🚀 Features  



- 🔍 **Semantic Search with FAISS** – Retrieves the most relevant restaurant info.  



- 🤖 **AI-Powered Conversations** – Natural responses powered by **Gemini 2.5 Flash**.  



- 📖 **Menu & FAQ Support** – Instantly answers customer questions.  



- 💻 **User-Friendly UI** – Built with **Gradio** for seamless interaction.  



- ⚡ **Lightweight & Scalable** – Easy to adapt for other domains.  
 
---
 
## 🛠️ Tech Stack  



- **Embedding Model** – All-MiniLM-L6-v2  



- **Vector Database** – FAISS  



- **LLM (AI Model)** – Gemini 2.5 Flash  



- **Chatbot UI** – Gradio  
 
---
 
## 📄 How It Works  



1. User submits a query (e.g., *“Is parking available?”*).  



2. Query is embedded using **MiniLM**.  



3. **FAISS** retrieves the most relevant restaurant knowledge.  



4. **Gemini 2.5 Flash** generates a natural, context-aware answer.  



5. Response is shown instantly in the **Gradio UI**.  
 
✅ Example:  



*User:* “Is parking available?”  



*Bot:* “Yes! Parking is available. Complimentary valet and secure underground parking are offered.”  
 
---
 
## 🏗️ Architecture  
 
The system is built using RAG principles with embeddings, vector search, and an AI model working together to generate precise answers.  
 
<img width="1485" height="710" alt="image" src="https://github.com/user-attachments/assets/98b814b3-e124-45df-a16e-9bc03d8c3c33" />
 
 
---
 
## 📈 Future Enhancements  



- Multi-turn conversation memory  



- Real-time integration with restaurant databases  



- Deployment with **FastAPI** or **Streamlit**  



- Voice-enabled chatbot  
 
---
 
## 💻 How to Run  



1. Clone the repository:



   ```bash



   git clone https://github.com/dhairya48ML/RAG_chatbot_for_Restaurant.git



   cd restaurant-rag-chatbot
 
2. Run the code.
 
 
