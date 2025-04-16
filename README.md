InstaGrowthGPT 📈🤖

An AI-powered Instagram growth app that analyzes your content, boosts engagement, prevents shadowbans, and automates your content strategy — all in one clean platform.

🚀 Features

📊 Dashboard

Real-time Instagram follower growth

Engagement rate & post performance

GPT-powered daily growth tips

📝 Content Analyzer

Upload any caption

GPT rewrites it for higher engagement

Suggests best time to post and optimized hashtags

🤖 AI Caption Butler

Describes your image → auto-generated captions

Customized to your audience and niche

🎥 Reel & Story Analyzer

Suggests frame-level improvements

Recommends trending music and pacing changes

📅 Scheduler

Set it and forget it: AI-generated captions auto-loaded into post scheduler

📈 Weekly Reports

Auto-email summary of performance

Trend insights and suggested next moves

🔒 Anti-Shadowban System

Scans captions for banned hashtags and IG-sensitive phrases

GPT rewrite avoids risky content without killing your vibe

🧠 Powered by:

Instagram Graph API

OpenAI GPT-4

MongoDB Atlas

Render.com / Vercel

🛠️ Tech Stack

Frontend: React (Next.js or Vite)

Backend: Express.js (Node)

DB: MongoDB

Deployment: Render or Vercel

📁 Project Structure

instagrowthgpt/
├── frontend/                 # UI (Next.js or Vite)
├── backend/                  # Express API w/ IG login, GPT tools
│   └── routes/safe-rewrite.js
├── render.yaml               # Render deployment config
├── vercel.json               # Optional Vercel support
└── .env.example              # Reference environment variables

🧪 Local Setup

git clone https://github.com/your-username/instagrowthgpt.git
cd instagrowthgpt

# Setup frontend
cd frontend && npm install && npm run dev

# Setup backend (in new terminal)
cd ../backend && npm install && node index.js

🌐 Deploy on Render

Push to GitHub

Go to render.com

Create two web services: one for frontend (static), one for backend (Node)

Use render.yaml for guidance

🔐 Environment Variables (.env)

INSTAGRAM_CLIENT_ID=your_id
INSTAGRAM_CLIENT_SECRET=your_secret
IG_WEBHOOK_TOKEN=some_secret_word
MONGO_URI=your_mongodb_connection
OPENAI_API_KEY=sk-xxxx
REPORT_EMAIL=you@gmail.com
REPORT_PASS=your_email_app_password

💡 Coming Soon

Multi-platform support (TikTok, YouTube Shorts)

Auto-DM responder

GPT-powered trend forecasting

🙌 Credits

Built with love by Peter using OpenAI + caffeine.

“The AI copilot for serious content creators.”

# pp
