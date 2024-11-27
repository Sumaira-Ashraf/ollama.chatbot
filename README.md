# ollama.chatbot
 Ollama can host various LLMs, including Mistral, a powerful language model known for its advanced capabilities in text generation, translation, summarization, and code generation. 
Markdown
## Document Query App with Ollama Mistral

This repository provides a Streamlit application that allows you to query documents using Ollama Mistral for text retrieval and generation (RAG).

**Installation:**

1. Clone this repository: `git clone https://github.com/your-username/document_query_app.git`
2. Install required libraries: `pip install -r requirements.txt`

**Running the App:**

1. Navigate to the project directory: `cd document_query_app`
2. Run the application: `streamlit run app.py`

**Instructions:**

1. Open http://localhost:8501/ in your web browser.
2. Enter URLs of the documents you want to query (one per line).
3. Type your question in the "Question" field.
4. Click the "Query Documents" button.

**Explanation:**

* `app.py` defines the core functionality of the app, including input processing, document retrieval, embedding generation, RAG execution, and answer display.
* `requirements.txt` lists the necessary Python libraries for the project.
