# AI Agent Document Processing with LangChain

This project demonstrates how to process, chunk, and index documents using LangChain to build a vector store for retrieving information about AI agents. It supports multiple document types like text, web pages, and PDFs, and uses OpenAI embeddings for similarity search.

## Features

- Load documents from:
  - Text files
  - Web pages
  - PDF files
- Process documents by chunking with customizable size and overlap.
- Index documents in a vector store using OpenAI embeddings.
- Perform similarity search to retrieve the most relevant documents for a query.

## Requirements

- Python 3.7+
- Libraries:
  - `langchain-community`
  - `dotenv`
  - `bs4`
  - `chromadb`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
2.Create a virtual environment and activate it:

```bash
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```
3. Install dependencies
```bash
   pip install -r requirements.txt
```
4. Setup your .env file.
```bash
   OPEN_AI_API_KEY=your_openai_api_key
```

![image](https://github.com/user-attachments/assets/1c4310a9-cf9a-406c-9d2b-25d9239d8dc5)
