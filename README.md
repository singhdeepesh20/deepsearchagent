# DeepSearchAgent-Your Intelligent Agent
DeepSearch is an intelligent AI-powered browser search agent built with LangChain and Groq’s LLM API. It combines academic research tools like Arxiv, Wikipedia, and DuckDuckGo to deliver smart, contextual, and insightful search and research results—all from a clean and interactive Streamlit web app interface.

---

## Features

- **Multi-tool Search**: Integrates Arxiv API, Wikipedia, and DuckDuckGo search for comprehensive query coverage.  
- **Context-Aware AI Agent**: Uses LangChain's Zero-Shot React Description agent with Groq’s LLM for intelligent reasoning.  
- **Interactive Chat Interface**: Streamlit-based chat UI with styled user and assistant message bubbles.  
- **Background and UI Enhancements**: Custom background image with overlay, loading spinner, and polished chat UX.  
- **Secure API Key Input**: Groq API key securely entered via sidebar.

---

## Installation

1. Clone the repository:


   git clone https://github.com/yourusername/deepsearch-ai-agent.git
   cd deepsearch-ai-agent
   
2. Create and activate a virtual environment (recommended):


python -m venv venv
source venv/bin/activate  # Linux/macOS
.\venv\Scripts\activate   # Windows
Install dependencies:


3. Install requirements

pip install -r requirements.txt
Create a .env file (if needed) to store environment variables like API keys.


4.Run the Streamlit app:


streamlit run app.py
Enter your Groq API Key in the sidebar input to enable AI functionality.

Type your questions or research queries in the chat input box.

The AI agent will fetch and combine results from Arxiv, Wikipedia, and DuckDuckGo, then display a smart, contextual response.

## Technologies Used
-> Streamlit — Web app framework

-> LangChain — AI agent framework

-> Groq LLM API — Language model backend

-> Arxiv API Wrapper — Academic research data

-> Wikipedia API Wrapper — Knowledge base

-> DuckDuckGo Search API — Web search

## Contributing
Contributions, bug reports, and feature requests are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.



DuckDuckGo Search API — Web search
