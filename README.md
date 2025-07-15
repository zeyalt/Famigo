# Famigo: Your AI-Powered Family Weekend Planner

Famigo is an AI-powered companion designed to help families in Singapore discover personalized, kid-friendly weekend activities. It intelligently curates recommendations based on user preferences, weather forecasts, and event calendars, streamlining the planning process and reducing parental mental load.

## Features

*   **Personalized Activity Recommendations:** Get suggestions tailored to your family's interests.
*   **Intelligent Timeframe Interpretation:** Understands vague temporal queries like 'next weekend' and converts them to precise dates.
*   **Enhanced Image Generation:** Refines brief user prompts into detailed descriptions for high-quality activity images.
*   **Conversational Interface:** An integrated, memory-aware chatbot for seamless planning.
*   **Contextual Understanding (RAG):** Utilizes Retrieval-Augmented Generation to provide relevant information from documents.

## Technologies

*   **LangChain:** For agentic orchestration and tool routing.
*   **OpenAI GPT-4:** For advanced text generation and reasoning.
*   **OpenAI DALL-E:** For image generation.
*   **OpenAI Embeddings (`text-embedding-ada-002`):** For converting text into vectors for semantic search.
*   **FAISS:** For efficient vector similarity search.
*   **PyMuPDFLoader:** For loading PDF documents.
*   **RecursiveCharacterTextSplitter:** For efficient document chunking.
*   **SQLite:** For database management.

## How to Run

Famigo is developed as an end-to-end prototype primarily in Google Colab notebooks (`.ipynb` files). To run the project:

1.  **Clone this repository** (if applicable).
2.  **Open the relevant Google Colab notebook** (e.g., `Project_ZeyaLwinTun.ipynb`).
3.  **Install dependencies** (usually listed at the beginning of the notebook).
4.  **Set your `OPENAI_API_KEY`** as an environment variable.
5.  **Run the cells sequentially** within the notebook.

Familiarize yourself with the notebook's instructions for interacting with the chatbot and tools. 
