# Task: Multiple pdf chatbot
The MultiPDF Chat App is a pyton application. By using this app we chat with multiple PDF files at once. We can ask questions about the PDFs using normal language, and the app will give us helpful answers based on what's written in the documents. This app uses a smart system to give us the right answers to our questions. 

# How it works:

<img width="623" alt="image" src="https://github.com/sunandhini96/multiple-pdf-chat/assets/63030539/3f532766-957b-4735-9a92-ea17fb4bfeb2">

### Steps : 
1. PDF LOading: This app load multiple pdfs and extract all the text content from all pdfs.
2. Text Chunking: Extracted text converted into chunks.
3. Embeddings: From the chunks created the vector representation through embeddings.
4. Vector Store: All embeddings stored in the vector store.
5. Similarity matching: By user providing the question, text converted into embeddings using same embedding model used in previously, similarity searching get the context from checks text data.
6. Response Generation: By providing chunks data to llm models output would be generated.

# Usage:
``` python -r requirements.txt ```

```streamlit run app.py```

# Output :
<img width="1276" alt="image" src="https://github.com/sunandhini96/multiple-pdf-chat/assets/63030539/06bada7b-ad0b-4beb-a9c3-e8a94fd4f16f">

   
