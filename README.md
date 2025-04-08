# RAG with PDF Upload & Chat History

A powerful Retrieval-Augmented Generation (RAG) system designed for document-based Q&A, featuring **PDF upload** and **chat history retention**. This project utilizes **Hugging Face embeddings** and the **Gemma2-9B-IT model** for accurate and context-aware responses.

## 🚀 Features

- **User Input Required**: Users must input their own GROQ_API_KEY to use this application.
- **PDF Upload Support**: Easily upload and process documents for efficient retrieval.
- **Chat History Retention**: Maintains conversation history for better contextual understanding.
- **RAG Architecture**: Enhances response accuracy by retrieving relevant document snippets.
- **Gemma2-9B-IT Model**: Leverages a powerful model for high-quality response generation.
- **Hugging Face Embeddings**: Enables efficient and semantic document retrieval.
- **LangChain Integration**: Ensures seamless retrieval and generation workflow.
- **Streamlit UI**: Provides an intuitive interface for interaction.

## 🛠️ Installation

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/KrishBhimani/RAG-with-PDF-Upload-and-Chat-History.git
```

### 2️⃣ Create a Virtual Environment

#### For Windows:
```sh
python -m venv venv
venv\Scripts\activate
```

#### For macOS/Linux:
```sh
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```sh
pip install -r requirements.txt
```

### 4️⃣ Set Up Environment Variables

Create a `.env` file in the project root and add:

```ini
HF_TOKEN="your_api_key_here"
LANGCHAIN_API_KEY="your_api_key"
LANGCHAIN_PROJECT="your_project_name_here"
```

Ensure `.env` is excluded from version control by adding it to `.gitignore`.

### 5️⃣ Run the Streamlit App

```sh
streamlit run app.py
```
