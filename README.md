# ✉️ Email Writer Assistant (AI-Powered)

An **AI-powered Chrome Extension** that helps you **generate professional email replies** directly within **Gmail** using **OpenAI / Gemini API**.

---

## 🚀 Features
- ✍️ **AI-generated Email Replies** — Get smart, context-aware responses.
- 🔒 **Secure API Integration** — Uses Spring Boot backend.
- 🌐 **Chrome Extension** — Easy to use inside Gmail.
- ⚡ **Fast & Lightweight** — Minimal performance impact.
- 🛠️ **Customizable Prompts** — Control tone & style.

---

## 🏗️ Tech Stack
- **Frontend (Extension):** HTML, CSS, JavaScript  
- **Backend (API):** Spring Boot (Java)
- **AI Model:** Google Gemini 
- **Version Control:** Git & GitHub

---

## 📦 Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/<your-username>/email-writer-assistant.git
cd email-writer-assistant
2️⃣ Backend Setup (Spring Boot)
bash
Copy code
cd backend
mvn clean install
mvn spring-boot:run
The backend will start at: http://localhost:8080

3️⃣ Frontend Setup (Chrome Extension)
Open Google Chrome → Go to chrome://extensions

Enable Developer Mode (top right).

Click "Load unpacked".

Select the extension/ folder.

Open Gmail → Pin the extension → Start using it.

🔑 API Configuration
Inside backend/src/main/resources/application.properties:

properties
Copy code
api.key=YOUR_GEMINI_API
server.port=8080
📸 Screenshots
Extension UI	Email Suggestion

🧑‍💻 How to Use
Open Gmail.

Click on the Email Writer Assistant extension.

Select "Generate Reply".

AI will suggest a professional response.

Edit if needed → Click Insert Reply.

🛠️ Future Enhancements
🔹 Support for multiple AI models

🔹 Improved email tone customization

🔹 Dark mode UI for the extension

🤝 Contributing
Pull requests are welcome!
For major changes, open an issue first to discuss what you’d like to improve.

📜 License
This project is licensed under the MIT License.

📬 Contact
Author: Shubham Agnihotri
Email: shubhamagnihotri2022@gmail.com
LinkedIn: www.linkedin.com/in/shubham-agnihotri-306386276
