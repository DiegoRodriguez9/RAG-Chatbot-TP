RAG Chatbot (AI)

Este proyecto implementa un **Retrieval-Augmented Generation (RAG) Chatbot** capaz de responder preguntas utilizando información proveniente de documentos (manuales pdf) externos, combinando recuperación semántica y modelos de lenguaje.

El objetivo es demostrar un flujo completo de **carga de documentos → embeddings → búsqueda vectorial → generación de respuestas**.

---

## 🧠 ¿Qué hace este proyecto?
- Carga documentos (PDF / texto)
- Divide la información en fragmentos (chunking)
- Genera **embeddings** para cada fragmento
- Almacena los embeddings en un **vector store**
- Recupera los fragmentos más relevantes ante una pregunta
- Reconoce imágenes enviadas por el usuario
- Búsqueda de similitud 
- Genera una respuesta usando un **LLM**

---

## ⚙️ Tecnologías utilizadas
- Python 3.x
- Jupyter Notebook
- LangChain
- FAISS (vector database)
- OpenAI / LLM API


---

