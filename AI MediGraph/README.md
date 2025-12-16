

---

# 🏥 AI MediGraph

### Neo4j-Powered Hospital Intelligence Chatbot

An intelligent healthcare chatbot system that combines **Graph Databases (Neo4j)** with **AI-driven conversational intelligence** to provide structured, contextual, and reliable hospital-related insights.

---

## 📌 Project Overview

**AI MediGraph** is designed to enhance hospital intelligence by connecting structured medical data with natural language interaction.
The system leverages **Neo4j knowledge graphs** to represent hospital entities and relationships, enabling precise and context-aware responses.

---

## 🎯 Key Objectives

* Enable intelligent querying of hospital data
* Represent medical relationships using graph databases
* Provide accurate, explainable responses through an AI chatbot
* Support scalable healthcare data integration

---

## 🧠 Features

* 🤖 **AI Chatbot API** for hospital intelligence
* 🧩 **Neo4j Knowledge Graph** for structured healthcare data
* 🔍 Context-aware question answering
* ⚡ Fast and scalable backend architecture
* 🐳 Dockerized for easy deployment
* 🔄 CI pipeline using GitHub Actions

---

## 🏗️ Project Architecture

```
AI MediGraph
├── chatbot_api/              # Backend chatbot service
│   └── Dockerfile
├── chatbot_frontend/         # Frontend interface (if applicable)
├── hospital_neo4j_etl/       # Neo4j ETL & graph creation scripts
├── data/                     # Sample / processed datasets
├── tests/                    # Unit & integration tests
├── .github/workflows/        # GitHub Actions CI
├── docker-compose.yml
├── pyproject.toml
└── README.md
```

---

## ⚙️ Tech Stack

| Layer           | Technology              |
| --------------- | ----------------------- |
| Language        | Python                  |
| Database        | Neo4j (Graph DB)        |
| Backend         | FastAPI / Python API    |
| AI              | LLM-based chatbot logic |
| DevOps          | Docker, GitHub Actions  |
| Version Control | Git & GitHub            |

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Nhowmitha-suresh/AI-MediGraph-Neo4j-Powered-Hospital-Intelligence-Chatbot.git
cd AI-MediGraph-Neo4j-Powered-Hospital-Intelligence-Chatbot
```

---

### 2️⃣ Run Using Docker

```bash
docker-compose up --build
```

---

### 3️⃣ Access Services

* **Chatbot API:** `http://localhost:8000`
* **Neo4j Browser:** `http://localhost:7474`

---

## 🧪 Testing

```bash
pytest tests/
```

---

## 🔐 Environment Variables

Create a `.env` file:

```env
NEO4J_URI=bolt://localhost:7687
NEO4J_USER=neo4j
NEO4J_PASSWORD=your_password
```

---

## 🔄 CI/CD

* Automated Docker image build & push using **GitHub Actions**
* Docker images published to **Docker Hub**

---

## 📈 Future Enhancements

* Voice-based medical assistant
* Integration with EHR systems
* Advanced reasoning over medical graphs
* Multilingual healthcare chatbot
* Cloud deployment (AWS / Azure)

---

## 👩‍💻 Author

**Nhowmitha S**
AI & Data Science Undergraduate
🔗 [GitHub](https://github.com/Nhowmitha-suresh)
🔗 [LinkedIn](https://www.linkedin.com/in/nhowmitha-suresh-438b85281/)

---

## 📄 License

This project is licensed under the **MIT License**.

---


