# 🤖 Chainlit Web Dev Expert Agents

This project is a smart conversational assistant built using **Chainlit**, **OpenAI-compatible models** (e.g., Gemini via OpenRouter), and **agent handoff logic**. It can intelligently route user queries to the appropriate domain expert — either frontend or backend — depending on the question.

---

## 🚀 Features

- 🧠 **Web Dev Agent:** Smart router that identifies if a question is frontend or backend related.
- 🎨 **Frontend Agent:** Handles queries related to HTML, CSS, JavaScript, React, Next.js, and Tailwind CSS.
- 🛠️ **Backend Agent:** Specializes in API design, authentication, databases, Express.js, Django, and other server-side tech.
- 🔄 **Streaming Responses:** Powered by `chainlit`, users get streaming feedback for a smooth experience.
- 🔐 **Environment Support:** Secure API key loading using `.env`.

---

## 📁 File Structure

```bash
project/
├── main.py             # Core logic with agents and event handlers
├── .env                # Your environment variables (not committed to Git)
├── requirements.txt    # Required Python dependencies
└── README.md           # You're reading it!

🧩 Requirements

chainlit
python-dotenv
openai

🔑 Environment Setup
GEMINI_API_KEY=your_openrouter_or_google_gemini_api_key_here

🧪 How to Run
chainlit run main.py

🤝 Agent Logic Overview
Web Dev Agent: Routes questions based on topic (frontend vs backend).

Frontend Agent: UI/UX expert.

Backend Agent: API/database/server expert.

# CHECK THIS DEPLOY LINK:
web-production-380b2.up.railway.app

📜 License
MIT License — feel free to use, modify, and share.

👤 Author
Developed by Sohail with ❤️ using Chainlit and Gemini.

