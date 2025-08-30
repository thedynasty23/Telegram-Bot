# 🤖 Telegram Bot with AI & N8N  

![n8n](https://img.shields.io/badge/Workflow-n8n-orange?logo=n8n)
![Telegram](https://img.shields.io/badge/Telegram-Bot-blue?logo=telegram)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--powered-black?logo=openai)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Welcome to the **Telegram Bot** project! 🚀  
This bot is powered by **[n8n](https://n8n.io/)**, integrates with **OpenAI** for smart & funny replies 🧠😂, and connects directly to **Telegram** for seamless chat interaction.  

---

## 📸 Demo  
(Images and screenshots are available in the [`Images/`](./Images) folder)  

---

## ✨ Features  
- 💬 **AI-powered conversations** with OpenAI (GPT models)  
- 😂 **Humor mode** – responses can be funny with emojis  
- 🧠 **Short-term memory** – remembers the last few messages (context window)  
- 🌐 **Knowledge boost** with SerpAPI (Google-like search)  
- ⚡ **Built using n8n** – no heavy coding, just smart workflow automation  

---

## 🛠️ How it Works  
The workflow (`Telegram Bot using N8N.json`) includes:  
1. **Telegram Trigger** → Listens for new messages  
2. **Send Chat Action** → Shows typing indicator ✍️  
3. **OpenAI Chat Model** → Generates AI responses using GPT  
4. **AI Agent** → Wraps responses in a fun, emoji-rich style  
5. **Memory Buffer** → Keeps short-term chat history 📝  
6. **SerpAPI** → Fetches real-time info from the web 🌍  
7. **Send Text Message** → Replies back to the user on Telegram  

---

## 🚀 Getting Started  

### 1️⃣ Requirements  
- [n8n](https://n8n.io/) installed (self-hosted or cloud)  
- Telegram Bot Token (create via [BotFather](https://core.telegram.org/bots#botfather))  
- OpenAI API Key 🔑  
- SerpAPI Key (optional for web search)  

### 2️⃣ Import Workflow  
1. Open n8n  
2. Import `Telegram Bot using N8N.json`  
3. Add your **Telegram**, **OpenAI**, and **SerpAPI** credentials  

### 3️⃣ Run the Bot  
- Start your n8n workflow ▶️  
- Send a message to your Telegram bot 📱  
- Enjoy witty, AI-powered responses 🎉  

---

## 📂 Repository Structure  

```
.
├── Images/                   # Demo screenshots 📸
├── Telegram Bot using N8N.json   # Main workflow file ⚙️
└── README.md                 # Project documentation 📘
```

---

## 🧩 Future Enhancements  
- 🔊 Voice-to-text & text-to-voice support  
- 🎨 Rich media replies (stickers, images, GIFs)  
- 📊 Analytics dashboard for usage insights  

---

## 🤝 Contributing  
Pull requests are welcome! If you have cool ideas 💡, open an issue or contribute directly.  

---

## 📜 License  
This project is licensed under the MIT License.  

---

🚀 Built with ❤️ using **n8n**, **OpenAI**, and **Telegram API**
