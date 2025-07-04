# Rainfall Prediction RAG with Gemini

This project demonstrates a Retrieval-Augmented Generation (RAG) pipeline using Google Gemini and LangChain for rainfall prediction research papers.

## Features

- Loads and splits PDF documents
- Embeds text using Google Generative AI Embeddings
- Stores and retrieves document vectors with Chroma
- Answers questions using Gemini LLM with retrieved context

## Setup

1. **Clone the repository:**
   ```
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

2. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Add your API keys:**
   - Create a `.env` file and add your Google Generative AI API key:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```

4. **Add your PDF file:**
   - Place your research paper PDF (e.g., `my_paper.pdf`) in the project directory.

## Usage

Open and run the Jupyter notebook `rag gemini.ipynb` step by step to:

- Load and split the PDF
- Create embeddings and vector store
- Retrieve relevant documents
- Ask questions and get concise answers

## Notes

- The `.env` file is excluded from version control for security.
- Replace `my_paper.pdf` with your own document as needed.

## License

MIT License