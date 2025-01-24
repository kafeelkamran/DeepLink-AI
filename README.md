# DeepLink-AI

# 🚀 DeepLink AI - A Knowledge Graph-Enhanced RAG System  

DeepLink AI is an **advanced Retrieval-Augmented Generation (RAG) system** that integrates **Neo4j knowledge graphs, Hugging Face embeddings, and LLM-based contextual retrieval**. It enables intelligent document-based query answering with **semantic search, entity relationships, and 3D graph visualization**.

## 📌 Features  

- **📄 Document Upload**: Upload PDFs, extract entities, and structure relationships.  
- **📊 Knowledge Graph Creation**: Automatically stores extracted **entities & relationships** in **Neo4j**.  
- **🔍 Hybrid Search (Vector + Graph)**: Uses **HuggingFace embeddings** for vector search and **Neo4j Cypher queries** for relationship-based retrieval.  
- **📝 LLM-Based Query Answering**: Retrieves **context-aware** answers using **Groq API**.  
- **🌐 3D Graph Visualization**: Interactive **Plotly & PyVis-powered** visualizations for explainable AI.  

---

## 🏗️ System Architecture  

   - A[Upload Document (PDF)] -->|Extract Text & Entities| B[Neo4j Graph Store]
   - B -->|Vector Embedding|
   - C[HuggingFace Model]
   - D[User Query] -->|Hybrid Search| E[Vector + Graph Retrieval]
   - E -->|Context Matching| F[LLM (Groq API)]
   - F -->|Answer Generation| G[Response Display + 3D Graph Visualization]


## 🔧 Technologies Used
|     **Component**	         |      **Technology**       |
|----------------------------|---------------------------|
|    **Frontend (UI)**	     |        Streamlit          |
|    **Vector Store**        |	 HuggingFace Embeddings  |
|   **Graph Database**	     |         Neo4j             |
|   **LLM Processing**	     |        Groq API           |
|   **Visualization**	       |  Plotly, NetworkX, PyVis  |
|   **Document Processing**  |	PyPDFLoader, LangChain   |



# 🚀 Installation
## 1️⃣ Clone the Repository
  bash
          
          git clone https://github.com/yourusername/DeepLink-AI.git
          cd DeepLink-AI

## 2️⃣ Install Dependencies
bash

    pip install -r requirements.txt

## 3️⃣ Configure Neo4j & Groq API
Create a .env file with:

.env

    NEO4J_URI=bolt://localhost:8178
    NEO4J_USER=username
    NEO4J_PASSWORD=yourpassword
    GROQ_API_KEY=your-api-key

## 4️⃣ Run the Streamlit App
bash

    streamlit run app.py
This launches the DeepLink AI Web UI where users can upload PDFs, extract knowledge, and query the system

## 🛠️ Usage Guide
- 1️⃣ **Upload a PDF** → Extracts text, entities, and relationships
- 2️⃣ **View Knowledge Graph** → Auto-generated Neo4j-based graph
- 3️⃣ **Query the System** → Retrieves contextual answers via hybrid search
- 4️⃣ **Explore in 3D** → Plotly & PyVis-powered visualization of relationships

## 📜 License

This project is licensed under the Apache 2.0 License. See LICENSE for details.

## 🤝 Acknowledgements

- [Neo4j](https://neo4j.com/) - Graph database used for storing entities and relationships.
- [Groq](https://www.groq.com/) - Language model for generating relationships from documents.
- [Hugging Face](https://huggingface.co/) - Embedding models used for document vectorization.
- [Plotly](https://plotly.com/) - For generating interactive 3D graphs.
- [LangChain](https://www.langchain.com/) - For handling document processing and RAG logic.

## 💬 Contact  

📩 Mail  to: [Email](mailto:kafeel17kamran@gmail.com)  
🌐 GitHub: [Profile](https://github.com/kafeelkamran)  
🚀 LinkedIn: [linkedin-profile](https://www.linkedin.com/in/kafeel-kamran-ahmed-8a05792a1/)
