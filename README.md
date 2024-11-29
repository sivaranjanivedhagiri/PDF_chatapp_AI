# PDF_chatapp_AI

**Introducing **PDF Chat AI App**! 🚀**

Chat seamlessly with multiple PDFs using **Langchain, Google Gemini Pro, and FAISS Vector DB** for lightning-fast, accurate responses. Powered by the awesome **Google Gemini Open-Source Language Model**, this app transforms your PDF experience with instant, intelligent interactions.

With** Streamlit Deployment,** it's all available at your fingertips. 📚💬
**Transform your PDF experience now! 🔥✨**

**Project Flow chart : **

![image](https://github.com/user-attachments/assets/d5f1c0fb-d22c-47a0-b671-f760e8b34189)


The application follows these steps to provide responses to your questions:

**PDF Loading **: The app reads multiple PDF documents and extracts their text content.

**Text Chunking** : The extracted text is divided into smaller chunks that can be processed effectively.

**Language Model** : The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

**Similarity Matching **: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

**Response Generation** : The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.


**Requirements for PDF_chatapp_AI :**

**Streamlit**
Purpose: A Python library for building interactive web applications.
Use: For creating a user-friendly front-end interface to interact with the PDFs and the chatbot.

**google-generativeai**
Purpose: A package that provides generative AI capabilities for chatbots, virtual agents, and more.
Use: To integrate Google’s generative AI models for intelligent responses to PDF queries.
python-dotenv

Purpose: A library for loading environment variables from a .env file.
Use: To securely manage API keys and sensitive configurations, ensuring they are not hardcoded in your code.

**langchain**
Purpose: A custom library for natural language processing (NLP) tasks.
Use: To handle conversational retrieval, text splitting, embeddings, vector stores, and chat models. This is essential for managing interactions with the PDFs and generating responses.
PyPDF2

Purpose: A Python library for reading and manipulating PDF files.
Use: For extracting and processing text from multiple PDF documents, enabling the chatbot to interact with them effectively.

**faiss-cpu**
Purpose: A library developed by Facebook for efficient similarity search, machine learning embeddings, and content-based filtering.
Use: To perform fast and efficient vector searches for finding relevant information in PDFs based on user queries.
langchain_google_genai

Purpose: An integration package between LangChain and Google’s generative AI SDK.
Use: To extract text from PDFs and generate accurate responses to user queries, utilizing Google’s powerful AI models.



