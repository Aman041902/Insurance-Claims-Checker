# 🏥 GenAI Insurance Claim Checker

**GenAI Insurance Claim Checker** is an AI-powered system that analyzes uploaded medical documents and invoices to determine whether a patient's insurance claim should be accepted or rejected — based on exclusion criteria, bill validation, and document completeness.

This project leverages **LLMs**, **Flask**, **FAISS**, and **LangChain** to automate medical claim verification in a transparent and explainable way.

---

## 📌 Features

- 📄 **PDF Upload**: Users can upload medical bills and related documents in PDF format.
- 🧠 **LLM-Based Judgement**: GPT-3.5-turbo is used to analyze and generate a report justifying acceptance or rejection.
- 🧾 **Bill Parsing**: Extracts the disease and expense amount from uploaded invoices.
- 🚫 **General Exclusion List Check**: Rejects claims containing excluded diseases (e.g., HIV, STD, Alzheimer's).
- ✅ **Document Verification**: Checks whether required documents are included.
- 📊 **Detailed Claim Report**: Includes executive summary, claim description, and approval status with max approved amount.

---

## ⚙️ Tech Stack

| Component           | Description                                         |
|---------------------|-----------------------------------------------------|
| 🧠 LLM               | OpenAI GPT-3.5-Turbo                                |
| 📚 Embeddings        | OpenAI Embeddings (`text-embedding-ada-002`)       |
| 🔍 Vector DB         | FAISS                                               |
| 📄 PDF Parser        | PyPDF2                                              |
| 💬 Framework         | Flask                                               |
| 🛠 Utilities         | LangChain + Scikit-learn (for similarity)          |

---

