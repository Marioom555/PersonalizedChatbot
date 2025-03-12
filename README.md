# 🤖 LangChain-Powered AI Assistant  

## 📌 About the Project  
This project is an **AI-powered chatbot** built using **LangChain** and **GPT models** to provide intelligent, context-aware conversations. It leverages advanced **LLM chaining, memory, and retrieval-augmented generation (RAG)** to enhance user interactions.

## 🚀 Features  
- **Conversational AI** – Natural language processing with GPT-based responses.  
- **Memory Integration** – Maintains context throughout the conversation.  
- **Retrieval-Augmented Generation (RAG)** – Enhances responses with relevant knowledge sources.  
- **Multi-Model Support** – Uses OpenAI GPT for generating responses.  
- **Tool Calling & Function Execution** – Enables dynamic operations within chat.  

## 🏗️ Tech Stack  
### 🔹 **Language Models & Processing**  
- **LangChain** – Framework for chaining LLM prompts and responses.  
- **OpenAI GPT (GPT-4/GPT-3.5)** – Core model for text generation.  

### 🔹 **Retrieval-Augmented Generation (RAG)**  
- **FAISS** – Efficient similarity search for document retrieval.  
- **Vector Embeddings** – Enhances chatbot knowledge base.  

### 🔹 **Tool Usage & Function Calling**  
- **LangChain Tools** – Enables AI to perform predefined tasks dynamically.  
- **Custom Functions** – Allows execution of real-time computations.  

### 🔹 **Deployment & APIs**  
- **Streamlit** – Interactive user interface.  

## 🛠️ Setup & Installation  
1. Clone this repository:  
    ```bash  
    git clone https://github.com/your-repo/langchain-ai-assistant.git  
    cd langchain-ai-assistant  
    ```  

2. Create a virtual environment:  
    ```bash  
    python -m venv env  
    source env/bin/activate  # On Windows: env\Scripts\activate  
    ```  

3. Install dependencies:  
    ```bash  
    pip install -r requirements.txt  
    ```  

4. Set up API keys (if using OpenAI):  
    ```bash  
    export OPENAI_API_KEY='your_api_key_here'  
    ```  

5. Run the chatbot interface:  
    ```bash  
    python app.py  
    ```  



