Ollama PDF RAG
Author: M Shasankar

Overview
This project enables chatting with PDF documents locally using Ollama and LangChain. It combines advanced Retrieval-Augmented Generation (RAG) techniques to process and query PDFs efficiently. The project offers:

Streamlit-based Web Interface for easy interaction.
Jupyter Notebook for experimentation and fine-tuning.
Features
Local Chat with PDFs: Run entirely on your local machine, ensuring privacy.
Streamlit App: Simple, interactive UI for uploading and querying PDFs.
Jupyter Notebooks: For exploring and experimenting with document queries.
Custom RAG Pipeline: Leverages Ollama + LangChain for Retrieval-Augmented Generation.
Technologies Used
Python 3.10+
LangChain for natural language processing.
Streamlit for building the web UI.
Ollama for running local language models.
Setup and Installation
Prerequisites
Ensure you have the following installed on your system:

Python (3.10 or higher)
Ollama: Install from https://ollama.ai
Git
Clone the Repository
bash
Copy code
git clone https://github.com/ShasankarM/ollama_pdf_rag.git
cd ollama_pdf_rag
Install Dependencies
bash
Copy code
pip install -r requirements.txt
How to Run the Project
1. Run the Streamlit App
Launch the Streamlit web interface for chatting with PDFs:

bash
Copy code
streamlit run streamlit_app.py
Upload your PDF file and start querying interactively.
2. Experiment with Jupyter Notebooks
You can explore the custom RAG pipeline by running the local_ollama_rag.ipynb or updated_rag_notebook.ipynb:

bash
Copy code
jupyter notebook
Project Structure
lua
Copy code
ollama_pdf_rag/
│-- .gitignore             # Ignored files and folders
│-- LICENSE                # License information
│-- README.md              # Project documentation
│-- requirements.txt       # Project dependencies
│-- streamlit_app.py       # Streamlit UI app
│-- updated_rag_notebook.ipynb  # Jupyter notebook for RAG pipeline
│-- local_ollama_rag.ipynb      # Alternate Jupyter notebook
│-- st_app_ui.png          # Screenshot of Streamlit UI
│-- PDFs/
    │-- WEF_The_Global_Cooperation_Barometer_2024.pdf  
    │-- scammer-agent.pdf  
    │-- LLMs.pdf  
Screenshots
Streamlit UI for PDF interaction:


License
This project is licensed under the MIT License.

