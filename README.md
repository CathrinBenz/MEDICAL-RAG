#  Medical RAG Diabetes Question Answering System
An AI-powered Medical RAG system that retrieves relevant diabetes-related medical information and generates context-aware answers using LangChain, FAISS, Hugging Face, and Qwen2.5.

##  Overview

The Medical RAG Diabetes Question Answering System is an AI-powered application that provides accurate and context-aware answers to diabetes-related medical questions using Retrieval-Augmented Generation (RAG). Instead of relying solely on a Large Language Model (LLM), the system first retrieves relevant information from a medical knowledge base and then generates responses based on the retrieved context, reducing hallucinations and improving answer reliability.

---

##  Features

-  Semantic search using FAISS vector database.
-  Retrieves relevant information from medical documents.
-  Generates context-aware responses using the Qwen2.5 LLM.
-  Retrieval-Augmented Generation (RAG) pipeline.
-  Supports multiple medical PDF documents.
-  Fast document retrieval with vector embeddings.
-  Natural language question answering.
-  Reduces hallucinations by grounding answers in retrieved documents.

---

##  Project Architecture

```
                 User Question
                       │
                       ▼
              Document Retriever
             (LangChain + FAISS)
                       │
          Retrieves Relevant Context
                       │
                       ▼
          Qwen2.5 Large Language Model
                       │
                       ▼
            Context-Aware Answer
```

---

##  Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| LangChain | RAG Pipeline |
| FAISS | Vector Database |
| Hugging Face | Embeddings & Model Support |
| Sentence Transformers | Text Embeddings |
| Qwen2.5 LLM | Answer Generation |
| Google Colab | Development Environment |
| PyTorch | Deep Learning Framework |

---

##  Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/Medical-RAG-Diabetes-QA.git
cd Medical-RAG-Diabetes-QA
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

##  Usage

1. Open the Jupyter Notebook or Google Colab notebook.
2. Install the required libraries.
3. Load the diabetes medical documents.
4. Generate vector embeddings.
5. Store embeddings in FAISS.
6. Ask a diabetes-related medical question.
7. The system retrieves relevant information.
8. Qwen2.5 generates the final answer based on the retrieved context.

---

##  Project Structure

```
Medical-RAG-Diabetes-QA/
│
├── RAG_DI.ipynb
├── README.md
├── requirements.txt
├── data/
│   ├── diabetes_documents.pdf
│   └── ...
├── images/
│   ├── architecture.png
│   └── output.png

```

---

##  Sample Questions

- What are the symptoms of diabetes?
- What is Type 2 Diabetes?
- What are the risk factors for diabetes?
- How can diabetes be prevented?
- What foods should diabetic patients avoid?
- What are the common treatments for diabetes?
- What are the complications of uncontrolled diabetes?
- How is diabetes diagnosed?

---

##  Results

- Successfully retrieves relevant medical information using semantic search.
- Generates context-based answers with improved accuracy.
- Reduces hallucinations by grounding responses in retrieved medical documents.
- Demonstrates efficient retrieval and response generation for diabetes-related queries.

---

##  Future Enhancements

- Support multiple diseases instead of only diabetes.
- Integrate a medical chatbot interface using Streamlit or Flask.
- Add multilingual support.
- Deploy the application on Hugging Face Spaces or Render.
- Improve retrieval using hybrid search techniques.
- Integrate citation-based responses.
- Add voice-based medical question answering.

---


---

## Acknowledgements

- LangChain
- Hugging Face
- FAISS
- Qwen2.5
- PyTorch
- Google Colab
