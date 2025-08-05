# 📄🔍 Multimodal RAG (PDF with Images)

This project demonstrates a **Multimodal Retrieval-Augmented Generation (RAG)** pipeline that processes **PDFs containing images** using OpenAI's multimodal capabilities. The goal is to extract both text and image-based information from documents and enable intelligent querying over them.

## 🚀 Features

- Extracts **textual and visual content** from PDFs
- Leverages **OpenAI GPT-4o** for understanding and generating insights
- Uses **RAG architecture** for improved context-aware responses
- Handles **image embedding and interpretation** via multimodal models

## 🧰 Tech Stack

- Python
- Jupyter Notebook
- OpenAI GPT-4o
- PyMuPDF / PDFPlumber (for PDF parsing)
- PIL / OpenCV (for image processing)
- LangChain / FAISS / Chroma (for vector search, optional)
- Streamlit (if used for UI)

## 🧑‍💻 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/multimodal-rag-pdf.git
   cd multimodal-rag-pdf
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set your OpenAI API Key:
   ```bash
   export OPENAI_API_KEY=your_key_here
   ```

4. Run the notebook:
   Open `1-multimodalopenai.ipynb` in Jupyter and run all cells.

## 🖼️ Input Format

- Accepts PDF files with **embedded images**
- Uses visual region processing to extract and interpret image zones

## 📦 Output

- Textual summaries or answers enhanced by visual context
- Can return captions, image-based insights, or combined QA

## 📌 Example Use Cases

- Legal document review (with embedded diagrams)
- Medical reports (e.g., radiology scans + text)
- Academic research papers with visual data
- Invoice/document analysis

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Built with ❤️ using OpenAI GPT-4o and the power of multimodal AI.

