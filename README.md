# 📚 Research Paper Semantic Search Engine

<p align="center">
  <img src="ScreenShots/cover.png" width="900">
</p>

Finding the right research paper isn't always easy. Many relevant papers don't contain the exact keywords we search for, which means traditional keyword-based search can miss useful results.

This project solves that problem using **Semantic Search**, where papers are retrieved based on the meaning of the query instead of exact word matches.

It was developed as part of my **second internship project** at **Coding Blocks School of Technology (CBSOT)**.

---

## 🚀 Features

- Semantic search using Sentence Transformers
- Fast similarity search with FAISS
- Automatic summarization of retrieved research papers
- Keyword extraction using KeyBERT
- Named Entity Recognition (NER) using spaCy
- Research Insights showing the most common entities across retrieved papers
- Match Level indicator based on similarity score

---

## 🛠️ Tech Stack

- Python
- Google Colab
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- KeyBERT
- spaCy
- Pandas
- NumPy

---

## ⚙️ How It Works

```text
User Query
     │
     ▼
Sentence Transformer
     │
     ▼
Query Embedding
     │
     ▼
FAISS Similarity Search
     │
     ▼
Top Matching Research Papers
     │
     ├── Summary Generation
     ├── Keyword Extraction
     ├── Named Entity Recognition
     ▼
Research Insights
```

---

## 📷 Sample Output

The project displays:

- Research paper title
- Similarity score
- Match level
- Generated summary
- Extracted keywords
- Named entities
- Research Insights (Top Entities)

---

## 💡 Future Improvements

Some ideas I plan to work on in future versions:

- Streamlit frontend for a better user experience
- RAG (Retrieval-Augmented Generation) pipeline
- Scientific NER model for research-specific entities
- Improved ranking and filtering of search results
- Research paper recommendation system

---

## 📂 Project Structure

```text
├── Research_Paper_Semantic_Search.ipynb
├── paper_embeddings.npy
├── paper_faiss.index
├── README.md
└── screenshots/
```

---

## ▶️ Getting Started

Clone the repository

```bash
git clone https://github.com/yourusername/Research-Paper-Semantic-Search-Engine.git
```

Move into the project folder

```bash
cd Research-Paper-Semantic-Search-Engine
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the notebook in Google Colab or Jupyter Notebook.

---

## 📌 What I Learned

While building this project, I got hands-on experience with:

- Semantic Search
- Vector Embeddings
- FAISS Indexing
- Transformer-based Summarization
- Keyword Extraction
- Named Entity Recognition
- Working with NLP pipelines

---

## 👨‍💻 Author

**Harshit Rao**

B.Tech Computer Science Engineering
---

If you found this project interesting or have any suggestions, feel free to connect with me or leave your feedback.
