# data-nlp-auto-chatbot-openai-aparavi
AI-powered chatbot using OpenAI embeddings, Weaviate vector search, and Aparavi ETL to answer natural language questions about automobile specifications.
# 🚘 Automobile Q&A Chatbot using OpenAI, Weaviate & Aparavi

An intelligent question-answering chatbot built to respond to queries about automobile specifications such as horsepower, width, fuel type, and more. It uses an ETL pipeline powered by **Aparavi**, embeddings generated via **OpenAI**, and stored/retrieved through **Weaviate vector search**.

---

## 📌 Problem Statement

Car enthusiasts and buyers often struggle to compare technical specs across various models. This chatbot enables users to ask natural language questions (e.g., "Which car has the highest horsepower under $20k?") and receive accurate answers drawn from a structured dataset processed from unstructured files.

---

## ⚙️ Tech Stack
- **ETL & Preprocessing**: Aparavi Data Toolchain
- **Embedding Model**: OpenAI Text Embeddings
- **Vector Storage**: Weaviate
- **Deployment**: Gradio (web interface)
- **Data Source**: CSV + unstructured text stored in AWS S3

---

## 🔄 Workflow

1. **Document Parsing**  
   - Extracts structured fields from unstructured documents via Aparavi

2. **Preprocessing**  
   - Cleans and standardizes data into tabular format

3. **Embedding Generation**  
   - Applies OpenAI embeddings to questions and answers

4. **Vector Indexing**  
   - Stores document vectors in Weaviate for fast semantic search

5. **Chatbot Interface**  
   - Built with Gradio to answer questions like:
     - “Which car has the lowest fuel consumption?”
     - “Compare width between Ford Mustang and BMW 3 Series”

---

## 📊 Sample Use Case

> **Question**: “Which car has the highest horsepower under 3000mm width?”  
> **Answer**: "Dodge Challenger — 485hp, width: 1920mm"

---

## 📁 Files Included
- `Automobile_team_11-2.ipynb` – Main chatbot logic and vector search queries
- `Report on Aparavi data toolchain enhancements -1.docx` – Description of the ETL pipeline
- `Technical_document_Team_11-1-2.pdf` – Architecture & flow documentation
- `Screenshot_2025-04-02.png` – Flow diagram from Aparavi

---

## 🌐 Business Impact

This approach can be extended to:
- Real estate bots
- Healthcare symptom checkers
- Insurance Q&A systems

The project demonstrates scalable NLP systems using unstructured data pipelines.

---

## 🏷️ Tags
`#openai` `#weaviate` `#nlp` `#vector-search` `#chatbot` `#automobile-data` `#aparavi` `#gradio`

---

## ✍️ Author
**Shalini James Paulraj**  
Graduate Student – Business Analytics & International Business  
[LinkedIn](https://linkedin.com/in/shalinijamespaulraj)
