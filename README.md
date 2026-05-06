# 🤖 AI Chatbot using Gemini API (React)

A web-based AI chatbot built using React and integrated with the Gemini API to generate real-time responses. The application provides an interactive chat interface with dynamic message rendering and smooth user experience.

---

## 🚀 Features

- 💬 Real-time AI responses using Gemini API  
- ⚛️ Built with React functional components and hooks  
- 🔄 Dynamic chat rendering using state management  
- 📜 Chat history handling (in-memory)  
- 📱 Smooth auto-scroll for better user experience  
- 🎨 Clean and interactive UI  

---

## 🛠️ Tech Stack

**Frontend:**
- React.js (Vite)
- JavaScript (ES6+)
- HTML, CSS

**AI Integration:**
- Gemini API (via REST)

---

## 📂 Key Implementation Details

- Used `useState` to manage chat history dynamically  
- Implemented `useEffect` for auto-scrolling chat view  
- Used `useRef` to control DOM behavior (chat scroll)  
- Structured API request in Gemini format (`contents → parts → text`)  
- Cleaned API response using regex before rendering  

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/dev-utkarshcodes/AI-Chatbot.git
cd your-repo-name
2️⃣ Install dependencies
npm install
3️⃣ Setup Environment Variables

Create a .env file in the root directory:

VITE_API_URL=your_gemini_api_endpoint
4️⃣ Run the application
npm run dev
🧪 How It Works
User enters a message
Message is added to chat history
Chat history is formatted for Gemini API
API returns response
Response is cleaned and displayed dynamically
⚠️ Limitations
Chat history is stored only in memory (not persistent)
Limited context handling for long conversations
Error handling can be further improved
🔮 Future Improvements
Persistent chat history (database/local storage)
Better context handling for multi-turn conversations
Backend integration for secure API handling
UI enhancements and deployment
📸 Screenshots
 ### 🧾 Initial Chat Screen
![Chat UI](screenshots/chat_window.png)

### 🤖 AI Response Example
![Response](screenshots/response.png)

### 📱 Chatbot Expanded View
![Open](screenshots/interface.png)

📌 Learning Outcomes
Integrated LLM API into a React application
Learned API handling and async programming
Managed dynamic UI updates using React hooks
Explored prompt formatting for LLMs

👨‍💻 Author
Your Utkarsh Shukla
GitHub:  https://github.com/dev-utkarshcodes