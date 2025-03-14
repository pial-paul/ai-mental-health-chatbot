# 🧠 About the Project  

## 🎯 **Inspiration**  
Mental health is an essential part of our well-being, yet many people hesitate to seek help due to stigma, lack of access, or fear of judgment. Inspired by the need for a safe, anonymous, and accessible support system, I decided to build a **Mental Health Chatbot**. The goal was simple: create a chatbot that could provide thoughtful, empathetic responses to users seeking mental health support.  

## 🏗 **How I Built It**  
The chatbot is powered by **Groq’s LLaMA 3.3-70B Versatile model**, ensuring intelligent and meaningful conversations. Here's the tech stack I used:  

- **LangChain** for orchestrating LLM-based interactions  
- **ChromaDB** for storing and retrieving knowledge from mental health resources  
- **PyPDFLoader** to process and extract text from research papers and documents  
- **Sentence Transformers** for embedding text and improving search accuracy  
- **Gradio** for a simple, user-friendly chat interface  
- **Google Colab** for cloud-based execution and testing  

The chatbot reads mental health-related PDFs, stores key insights in a vector database, and retrieves relevant information when users ask questions.  

## 🚀 **What I Learned**  
This project was an exciting challenge, and I learned a lot:  
✅ How to use **LangChain** for building intelligent retrieval-based applications  
✅ The power of **vector databases (ChromaDB)** for storing and searching text  
✅ How **embeddings (Sentence Transformers)** improve search accuracy  
✅ The importance of designing **empathetic and responsible AI responses**  

## 🛠 **Challenges I Faced**  
- **Balancing AI responses:** Ensuring that the chatbot remains supportive while making it clear that it is not a replacement for professional help.  
- **Optimizing embeddings:** Finding the right model for accurate search results.  
- **Handling PDF parsing:** Some documents were structured poorly, making text extraction difficult.  

Despite the challenges, seeing the chatbot respond meaningfully to users made it all worthwhile!  
