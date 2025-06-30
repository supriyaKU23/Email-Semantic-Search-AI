
# 📧 Enron Email Semantic Search AI

This project builds a semantic search engine using the **Enron Email Dataset**. It allows users to enter natural language queries and retrieves semantically similar emails using embeddings and vector search. The project is implemented fully in a Jupyter Notebook.

---

## 📌 Features

- 📄 Load and clean the Enron email dataset
- ✂️ Chunk long emails and extract metadata
- 🔢 Convert email chunks into semantic vectors using Sentence Transformers
- 📦 Store and search vectors using FAISS
- 🔍 Retrieve relevant email chunks based on user query
- 💬 Generate answers from retrieved documents using a basic summarization approach

---

## 🏗️ Architecture

![emailsearchaiarchtecturediagram](https://github.com/user-attachments/assets/96455531-dbb8-46bc-93f0-a2139a5aa8f6)


---

## 📁 Files

```
📜 Email_Search_AI_Project_full_dataset.ipynb  ← Main notebook containing the complete pipeline
https://www.kaggle.com/datasets/wcukierski/enron-email-dataset
```

---

## 🧪 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/email-search-ai.git
cd email-search-ai
```

2. Open the notebook:

```bash
jupyter notebook Email_Search_AI_Project.ipynb
```

3. Follow each cell step-by-step to:
   - Load and process data
   - Generate embeddings
   - Perform semantic search
   - View results

---

## 🔍 Example Use Case

> **Query**: “What were the decisions made about trading strategies in 2001?”

→ The system returns semantically related emails discussing power trading, strategies, and internal decisions from that timeframe.

---

## 🛠️ Tech Used

- Python (Jupyter Notebook)
- FAISS (for vector similarity search)
- Sentence Transformers (for embeddings)
- Pandas, NumPy (for data handling)

---

## 📚 Dataset

- **[Enron Email Dataset on Kaggle](https://www.kaggle.com/datasets/wcukierski/enron-email-dataset)**

---

## 🙋‍♀️ Author

**Supriya Uppala.**  

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
