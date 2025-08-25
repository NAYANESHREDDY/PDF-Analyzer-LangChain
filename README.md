# PDF-Analyzer-LangChain
PDF analysis pipeline using LangChain, HuggingFace, FAISS, and Flan-T5 for semantic search &amp; Q&amp;A.
# PDF Analyzer using LangChain & HuggingFace

A document analysis pipeline built in Google Colab to parse and query PDFs.  
- Split text into chunks with `RecursiveCharacterTextSplitter`.  
- Built a FAISS semantic search engine using HuggingFace embeddings.  
- Integrated a local transformer (Flan-T5) for context-aware Q&A with sources.  

## How to Run
1. Open `pdf_analyzer.ipynb` in Google Colab.  
2. Install dependencies from `requirements.txt`.  
3. Run cells to query your own PDF.  

## Example Query
**Q:** "What is the main topic of this PDF?"  
**A:** "The PDF discusses …"  
