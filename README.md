# Conversational RAG with PDF Chat History  

## 📌 Overview  
This project implements **Conversational RAG (Retrieval-Augmented Generation)** using **Groq-powered LLMs**, allowing users to **upload PDFs and chat with their content** while maintaining conversation history.  

## 🚀 Features  
- ✅ **Chat with Your PDFs** – Upload multiple PDF files and ask questions directly.  
- ✅ **Context-Aware Conversations** – Maintains chat history for better understanding of follow-ups.  
- ✅ **Groq-Powered AI** – Uses `Gemma2-9b-It` for natural language responses.  
- ✅ **Efficient Retrieval System** – Uses **LangChain, ChromaDB, and Hugging Face Embeddings**.  
- ✅ **Easy-to-Use UI** – Built with **Streamlit** for an interactive experience.  

## 🛠️ Installation & Setup  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-repo/rag-pdf-chatbot.git
   cd rag-pdf-chatbot
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt


3. **Set up environment variables:**
   Create a .env file and add your API keys:
   
   ```bash
   HF_TOKEN=your-huggingface-token


4.  **Run the application**
    ```bash
    streamlit run app.py

 
# 📝 Usage
1. **Enter your Groq API key to enable the chatbot.**
   
2. **Upload PDFs and start asking questions.**


3. **Follow-up questions are context-aware thanks to LangChain’s memory management.**
   
4. **Get instant answers with advanced AI retrieval!**
   
# 🎯 Future Enhancements

1. **Support for multiple LLM models.**
   
2. **Advanced summarization for long documents.**
   
3. **Deployment options for cloud-based services.**
