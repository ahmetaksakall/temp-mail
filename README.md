🚀 Tempcatch - Temporary Email (Temp Mail) Service

Tempcatch is a fast, privacy-friendly temporary email service that helps you avoid spam and protect your real inbox. Generate disposable email addresses instantly, receive emails in seconds, and stay anonymous — no signup required.

🌍 Live Demo: https://tempcatch.io/en

✨ Features

⚡ Instant temporary emails — create a disposable address in one click

🧼 Clean & simple inbox — minimal UI focused on speed

🔔 Real-time inbox refresh — see new messages as they arrive

🕵️ Privacy-first — no registration, no personal data stored

⏳ Auto-expiration — temporary inboxes expire automatically

🌐 Multi-domain support (if available) — generate emails across domains

📱 Responsive design — works great on desktop and mobile

🧩 API-ready architecture (optional) — easy to extend for integrations

🖼️ Screenshots

Add a couple of screenshots to make the repo pop.

🧱 Tech Stack

Replace these with your real stack.

Frontend: [React / Next.js / Vue / etc.]

Backend: [Node.js / FastAPI / Laravel / etc.]

Temp Mail Provider: [Mail.tm / 1secmail / custom SMTP / etc.]

Storage/Cache: [Redis / Postgres / Mongo / etc.]

Realtime: [SSE / WebSockets / Polling]

Deployment: [Vercel / Netlify / Docker / VPS]

⚙️ Getting Started
1) Clone the repository
git clone https://github.com/<your-username>/tempcatch.git
cd tempcatch

2) Install dependencies
npm install
# or
yarn
# or
pnpm install

3) Set up environment variables

Create a .env file in the project root:

# App
NEXT_PUBLIC_APP_NAME=Tempcatch
NEXT_PUBLIC_APP_URL=http://localhost:3000

# Provider (example)
MAIL_PROVIDER_BASE_URL=https://api.provider.com
MAIL_PROVIDER_API_KEY=your_key_here

# Optional
REDIS_URL=redis://localhost:6379
DATABASE_URL=postgres://user:pass@localhost:5432/db

4) Run locally
npm run dev


Open:
http://localhost:3000
