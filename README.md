---------

<h1 align="center">✨ Slack Clone with Chat & Video Calling ✨</h1>



<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Node.js-18+-green?logo=node.js" /></a>
  <a href="#"><img src="https://img.shields.io/badge/React-18-blue?logo=react" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Vite-🔥-ff69b4?logo=vite" /></a>
  <a href="#"><img src="https://img.shields.io/badge/MongoDB-Atlas-brightgreen?logo=mongodb" /></a>
  <a href="#"><img src="https://img.shields.io/badge/License-MIT-yellow" /></a>
</p>

---

## 🚀 Features

- 💬 **Real-time Messaging** with Threads, Reactions & Pinned Messages  
- 📂 **File Sharing**: Images, PDFs, ZIPs & more  
- 📊 **Polls** with Multiple Options, Anonymous Mode, Suggestions & Comments  
- 🔐 **Clerk Authentication** with Secure User Management  
- 📨 **Direct Messages** & Private Channels  
- 📹 **1-on-1 & Group Video Calls** with Screen Sharing & Recording  
- 🎉 **Real-time Reactions** during Calls  
- 🔧 **Background Jobs** powered by Inngest  
- 🚨 **Error Monitoring** with Sentry  
- 🤖 **AI-powered Code Suggestions** with CodeRabbit  
- 🎯 **Scalable Tech Stack** powered by Stream  
- 🚀 **Free Deployment Setup**  
- ⏳ And much more!

---

## 🛠️ Tech Stack

- **Frontend**: React + Vite + Tailwind CSS  
- **Backend**: Node.js + Express + MongoDB  
- **Authentication**: Clerk  
- **Messaging & Video**: Stream  
- **Background Jobs**: Inngest  
- **Monitoring**: Sentry  
- **AI**: CodeRabbit  

---

## ⚙️ Environment Setup

### 🔙 Backend (`/backend`)

```env
PORT=5001
MONGO_URI=your_mongo_uri_here
NODE_ENV=development

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key_here
CLERK_SECRET_KEY=your_clerk_secret_key_here

STREAM_API_KEY=your_stream_api_key_here
STREAM_API_SECRET=your_stream_api_secret_here

SENTRY_DSN=your_sentry_dsn_here

INNGEST_EVENT_KEY=your_inngest_event_key_here
INNGEST_SIGNING_KEY=your_inngest_signing_key_here

CLIENT_URL=http://localhost:5173
````

### 🖥️ Frontend (`/frontend`)

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key_here
VITE_STREAM_API_KEY=your_stream_api_key_here
VITE_SENTRY_DSN=your_sentry_dsn_here
VITE_API_BASE_URL=http://localhost:5001/api
```

---

## 🧑‍💻 Run Locally

### 🔧 Backend

```bash
cd backend
npm install
npm run dev
```

### 💻 Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 📸 Screenshots

<p align="center">
  <img src="/frontend/public/worklink.png" alt="App Screenshot" width="800"/>
</p>

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a PR or an Issue anytime.

---

## 📜 License

MIT License

Copyright (c) 2025 **Muhammad Wasim**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

```
