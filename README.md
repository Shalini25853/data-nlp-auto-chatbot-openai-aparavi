# Automobile Q&A Chatbot using OpenAI, Weaviate & Aparavi

An intelligent question-answering chatbot built to respond to queries about automobile specifications such as horsepower, width, fuel type, and more. It uses an ETL pipeline powered by **Aparavi**, embeddings generated via **OpenAI**, and stored/retrieved through **Weaviate vector search**.

---

## Problem Statement

Car enthusiasts and buyers often struggle to compare technical specs across various models. This chatbot enables users to ask natural language questions (e.g., "Which car has the highest horsepower under $20k?") and receive accurate answers drawn from a structured dataset processed from unstructured files.

---

##  Tech Stack

- **ETL & Preprocessing**: Aparavi Data Toolchain  
- **Embedding Model**: OpenAI Text Embeddings  
- **Vector Storage**: Weaviate  
- **Deployment**: Gradio (web interface)  
- **Data Source**: Confidential automobile dataset (AWS S3)

---

## Workflow Overview

1. **Document Parsing**  
   Extracts structured fields from unstructured documents via Aparavi

2. **Preprocessing**  
   Cleans and standardizes data into tabular format

3. **Embedding Generation**  
   Applies OpenAI embeddings to both questions and records

4. **Vector Indexing & Semantic Search**  
   Uses Weaviate for fast nearest-neighbor matching

5. **Gradio Chatbot Interface**  
   Supports natural language queries like:
   - “Which car has the lowest fuel consumption?”
   - “Compare width between Ford Mustang and BMW 3 Series”

---

## Sample Use Case

> **User Query**: “Which car has the highest horsepower under 3000mm width?”  
> **Bot Response**: “Dodge Challenger — 485hp, width: 1920mm”

---

## Files Included

- `Automobile_team_11-2.ipynb` – Core chatbot pipeline & vector search logic  
- `README.md` – Project overview and methodology

>  **Note**: Some documents and datasets have been omitted due to confidentiality agreements with the company. Technical diagrams and business documentation are not shared publicly.

---

## Business Impact

This chatbot framework demonstrates how vectorized semantic search + LLM embeddings can:
- Reduce dependency on structured queries
- Improve customer support in automotive, real estate, or healthcare
- Scale across industries for Q&A or internal knowledge bots

---

##  Tags

`#openai` `#weaviate` `#nlp` `#vector-search` `#chatbot`  
`#automobile-data` `#aparavi` `#semantic-search` `#gradio`

---

## Author

**Shalini James Paulraj**  
Graduate Student – Business Analytics & International Business  
[LinkedIn](https://linkedin.com/in/shalinijamespaulraj)
