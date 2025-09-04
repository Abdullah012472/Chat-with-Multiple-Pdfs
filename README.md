# Chat with Multiple PDFs using Gemini 💁

This project is a Streamlit web app that allows you to upload multiple PDF documents and chat with them using Google Gemini AI. The app extracts text from your PDFs, processes it into chunks, stores embeddings in a FAISS vector database and lets you ask natural language questions to get accurate answers from your documents.

## 📦 Installation
1. **Clone the repository**  
   ```bash
   https://github.com/Abdullah012472/Chat-with-Multiple-Pdfs.git
   ```
2. **Create a virtual environment with Python 3.10**
    ```bash
    uv venv --python=3.10
    ```
3. **Activate the virtual environment**
    ```bash
    .venv\Scripts\activate      # On Windows
    source .venv/bin/activate   # On Linux/Mac
    ```

4. **Install dependencies**
    ```bash
    uv pip install -r requirements.txt
    ```
5. **Set up environment variables**
   
   Create a .env file in the project root and add your API key:
    ```bash
    GOOGLE_API_KEY=your_api_key_here
    ```
7. **Run the app**
    ```bash
    uv run streamlit run app.py
    ```
