# 🤖 Intelligent ChatBot for FAQs

### 🧠 MCA Major Project  
**Created by:**  
- **Mohit Khatri** (Roll No: 2423993)  
- **Ujjwal Kumar** (Roll No: 24242027)  
- **Dibya Singh** (Roll No: 2423969)  

---

## 📘 Project Overview

The **Intelligent ChatBot for FAQs** is a machine learning–based system designed to automatically answer frequently asked questions.  
It uses **Natural Language Processing (NLP)** techniques with **PyTorch** for model training and **Flask** as the web framework to deploy an interactive chat interface.

The system understands user input, classifies the intent, and returns an accurate, context-aware response from the knowledge base.  
This chatbot can be integrated into websites, portals, or applications to reduce human workload and provide instant automated support.

---

## 🎯 Project Aim

To develop an **AI-powered chatbot** that can interact with users in natural language and provide instant, accurate answers to frequently asked questions in real time.

---

## 🧩 Objectives

- To understand user queries through Natural Language Processing (NLP).  
- To build and train a neural network model using PyTorch.  
- To create a user-friendly web interface using Flask and JavaScript.  
- To provide quick and accurate responses to FAQs automatically.  
- To reduce manual intervention and improve response efficiency.

---

## ⚙️ System Features

| Feature | Description |
|----------|-------------|
| **NLP-based understanding** | Tokenization and bag-of-words model for intent classification. |
| **Machine Learning** | Uses a feed-forward neural network trained with PyTorch. |
| **Flask API** | Provides endpoints for predicting chatbot responses. |
| **Interactive frontend** | Simple, responsive chat interface built with HTML, CSS, and JavaScript. |
| **Custom training** | Easily editable `intents.json` file for new FAQ data. |
| **Offline support** | Works locally without internet access after setup. |
| **Expandable** | Can integrate with databases or APIs for advanced use. |

---

## 🧮 System Architecture

User -> Frontend -> Flask Backend -> PyTorch Model -> Response

---

## 🧰 Technology Stack

| Component | Technology Used |
|------------|----------------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Backend** | Python (Flask Framework) |
| **Machine Learning** | PyTorch |
| **NLP Tools** | NLTK (Tokenization, Stemming) |
| **Data File** | `intents.json` |
| **IDE/Editor** | VS Code / PyCharm |
| **Version Control** | Git + GitHub |
| **Deployment (optional)** | Docker / Render / Heroku |

---

## 🗃️ Project Structure

Intelligent-ChatBot-For-FAQs/
├── src/
│   ├── chat.py
│   ├── train.py
│   ├── model.py
│   ├── nltk_utils.py
│   └── app.py
├── static/
│   ├── index.html
│   └── app.js
├── intents.json
├── requirements.txt
├── LICENSE
├── README.md
└── .gitignore

---

## 🧠 Working of the ChatBot

1. Input Processing  
2. Tokenization  
3. Bag of Words Conversion  
4. Prediction (PyTorch Model)  
5. Response Selection  
6. Output to User  

---

## 🧑‍💻 Installation and Setup

1. Clone Repository  
2. Create Virtual Environment  
3. Install Dependencies  
4. Train Model  
5. Run Chatbot (console or Flask app)

---

## 🖥️ Example Interaction

User: Hello  
Bot: Hi there! How can I help you today?

User: What is your name?  
Bot: I’m your friendly FAQ assistant chatbot!

---

## 📦 Requirements

Python 3.9 or above  
Flask >= 2.0  
PyTorch >= 1.8  
NLTK  
NumPy

---

## 🚀 Future Enhancements

- Voice input support  
- Transformer-based NLP models  
- Database integration  
- Admin dashboard  
- Cloud deployment

---

## 🧑‍🏫 Applications

- College Help Desks  
- E-commerce Support  
- Banking Systems  
- Technical Support Portals  
- General Inquiry Chatbots

---

## 🔒 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Authors

| Name | Role | Roll No | Contribution |
|------|------|----------|--------------|
| **Mohit Khatri** | Lead Developer | 2423993 | Model, API, Training Script |
| **Ujjwal Kumar** | Frontend Developer | 24242027 | UI, HTML, JS |
| **Dibya Singh** | Research & Documentation | 2423969 | Intents, Testing, Report |

---

## 📚 References

- PyTorch Docs: https://pytorch.org/docs  
- Flask Docs: https://flask.palletsprojects.com  
- NLTK Docs: https://www.nltk.org  

---

## 🏁 Conclusion

The **Intelligent ChatBot for FAQs** demonstrates the use of AI and NLP in automating user communication.  
Built by MCA students, this project integrates theory with practical machine learning concepts to create an intelligent, real-world application.
