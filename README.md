 UnIQ Insight Bot  
**An AI-powered chat companion for OpenChat communities.**  

## 🚀 Project Overview  
UnIQ Insight is a lightweight AI bot designed to enhance productivity and engagement within OpenChat communities. It simplifies conversations by providing real-time summaries, smart reminders, and contextual suggestions without requiring heavy computational resources.  

## 🌟 Key Features  
- **Conversation Summaries:** Generate concise highlights of group discussions.  
- **Smart Reminders:** Schedule and receive task follow-ups.  
- **Contextual Link Suggestions:** Get relevant resources based on chat topics.  
- **Lightweight & Efficient:** API-driven, ensuring fast performance.  

## 🔧 Tech Stack  
- **Backend:** Node.js & Express.js  
- **APIs:** OpenAI for summaries, Google Search for suggestions  
- **Database:** In-memory storage for prototype (expandable)  
- **Hosting:** Vercel/Railway  

## 📦 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Tonyflam/UnIQ-Insight-Bot.git

Install dependencies:
```bash
  cd UnIQ-Insight-Bot  
  npm install

Set environment variables in a .env file:
 ```OPENAI_API_KEY=your-api-key  
    PORT=3000

Run the bot locally:
```bash
npm run dev


⚙️ How It Works

Message Hook: The bot listens for new messages in OpenChat groups.
Summarization: It analyzes chat threads and generates concise summaries.
Reminders: Users can set reminders by using /remind [time] [message].
Link Suggestions: Based on keywords, the bot suggests useful resources.

🚀 Deployment
To deploy on a free-tier platform like Vercel or Railway:

Connect your GitHub repo.
Set environment variables.
Deploy the app.

🎥 Demo (Coming Soon)
A demo video showcasing UnIQ Insight in action will be added here.
🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit pull requests.
📄 License
This project is licensed under the MIT License.
💬 Built for OpenChat
Built with passion by David Praise Francis-Omogbai for the OpenChat Botathon 2025.
