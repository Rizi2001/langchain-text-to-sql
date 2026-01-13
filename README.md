# 🧩 LangChain Text-to-SQL (Vertex AI + BigQuery)

An **R&D exploration** of using **LangChain with Vertex AI LLMs** to generate SQL queries over **BigQuery datasets** from natural language.

## 🎯 Objective

To evaluate the feasibility of **Text-to-SQL** on real-world BigQuery schemas using:
- LangChain
- Vertex AI LLMs
- Structured enterprise datasets

## 🧠 Key Learnings

- Performs reasonably on **small / simple schemas**
- Struggles with:
  - Large schemas
  - Deep table relationships
  - Ambiguous column naming
- Highlights limitations of naïve Text-to-SQL approaches without:
  - Schema pruning
  - Table selection
  - Intermediate reasoning layers

## 🛠️ Tech Stack

- Python  
- LangChain  
- Google Vertex AI (Text-Bison)  
- BigQuery  
- Jupyter Notebook

## 🧪 What This Repo Contains

- Experimental notebook implementing Text-to-SQL
- Prompting and schema injection strategies
- Query generation attempts and failure analysis

## 📌 Why This Matters

This repo demonstrates:
- Practical experimentation with LLM limitations
- Awareness of real-world enterprise data challenges
- Understanding of why production Text-to-SQL requires additional layers

## 🔬 Status

🚧 **Experimental / R&D**  
Not production-ready — intended for learning and evaluation.
