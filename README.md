# 🧠 AI Agent Chat App with Phi and Google GenAI

This is a conversational AI web app built using **Streamlit**, **Phi**, and **Google Generative AI**. Ask questions, get answers, and explore intelligent conversations with real-time responses.

---
## 🔗 Live Demo

👉 [Click here to try it out!](https://video-summarizer-vcut.onrender.com/)

## 🚀 Features

- Natural Language Chat Interface
- Supports Phi API and Google GenAI
- Search answers using DuckDuckGo
- Streamlit-based frontend

---

## 🔧 Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo 
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add your API keys

Create a `.env` file in the root directory:

```
PHI_API_KEY=your_phi_api_key_here
GOOGLE_API_KEY=your_google_api_key_here
```

> ⚠️ **Important:** Never commit your `.env` file to GitHub.

### 4. Run the app locally

```bash
streamlit run app.py
```

---

## 🌍 Deployment on Render

1. Push your code to a public GitHub repo  
2. Visit [Render](https://render.com)  
3. Click **"New Web Service"**  
4. Connect your GitHub repo  
5. Configure Render settings:
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `streamlit run app.py`
   - Add environment variables: `PHI_API_KEY`, `GOOGLE_API_KEY`

---

## 📁 File Structure

```
📁 your-repo/
├── app.py
├── requirements.txt
├── .env (do not push)
└── README.md
```
---
## 📸 Screenshot
<img width="1794" height="719" alt="image" src="https://github.com/user-attachments/assets/eff0290c-1cb8-4c19-b001-c79f14221a41" />

## 📜 License

This project is licensed under the [MIT License](LICENSE).
---
