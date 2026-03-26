# 💳 Cassandra BankBot AI

Cassandra BankBot AI is a chatbot system designed to handle banking-related queries and provide user-specific account information. The system uses structured data (JSON) and integrates with a local AI model for controlled responses.

---

## 📌 Features
- 🤖 Chatbot for banking queries  
- 🔒 Restricted to banking-related questions only  
- 📂 Retrieves user data (balance, loans, transactions) from JSON  
- ⚡ Fast and simple response system  
- 🧠 Integrated with Ollama Phi-3 model API  

---

## 🛠️ Technologies Used
- Python  
- Streamlit (for UI)  
- JSON (for data storage and retrieval)  
- Ollama (Phi-3 model for chatbot responses)  

---

## 📂 Project Structure
Cassandra_BankBotAI/

│── app.py  # Main application

│── banking_library.py   # Handles banking logic & JSON data

│── README.md            # Project documentation

│── LICENSE              # MIT License

---

## ▶️ How to Run the Project

1. Install required libraries:
   pip install streamlit

2. Make sure Ollama is installed and running Phi-3 model:
   ollama run phi3

3. Run the application:
   streamlit run app.py

4. Open in browser:
   http://localhost:8501

---

## 📊 Functionality
- Fetches user account details such as:
  - 💰 Account balance  
  - 📄 Loan details  
  - 📊 Transaction history  
- Responds only to banking-related queries  
- Uses AI model for generating conversational responses  

---

## ⚠️ Limitations
- Works only with predefined JSON data  
- Limited to banking domain queries  
- Requires local Ollama setup  

---

## 📜 License
This project is licensed under the MIT License.

---

## 👩‍💻 Author
AireneMariahSaji
