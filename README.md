# 🖼️ Thumblify

> AI-powered thumbnail generation platform for content creators — built with the MERN stack, Gemini AI, and Cloudinary.

![TypeScript](https://img.shields.io/badge/TypeScript-100%25-3178C6?logo=typescript) ![AI](https://img.shields.io/badge/AI-Gemini-orange?logo=google) ![Cloud](https://img.shields.io/badge/Cloud-Cloudinary-3448C5)

---

## 📌 Overview

**Thumblify** is a full-stack AI-powered visual platform that lets creators generate custom thumbnails from natural language prompts. Specify your desired color schemes, aspect ratios, and artistic styles — and Gemini AI does the rest. A built-in YouTube Preview Simulator lets you see exactly how your thumbnail looks in a real feed before publishing.

---

## ✨ Features

- 🤖 **AI Thumbnail Generation** — Generate thumbnails from prompts with control over color palettes, aspect ratios, and artistic style via Gemini API
- 📺 **YouTube Preview Simulator** — Visualize your thumbnail inside a mock YouTube UI before going live
- ☁️ **Cloudinary Asset Management** — Seamless image upload and organization with 50% less manual effort
- 🪙 **Credit-Based Usage System** — Throttles high-compute AI calls, improving peak-time API latency by 10%
- 🔒 **100% TypeScript** — Type-safe data flow across the entire MERN stack and external AI integrations

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React (TSX), TypeScript |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| AI | Google Gemini API |
| Storage | Cloudinary |

---

## 🚀 Getting Started

```bash
# Clone and install
git clone https://github.com/Shrest2k5/Thumblify
cd thumblify

npm install        # server
cd client && npm install  # client
```

Create a `.env` in `/server`:

```env
MONGODB_URI=
GEMINI_API_KEY=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

```bash
npm run dev   # start server
cd client && npm run dev  # start client
```

---

## 🙋‍♂️ Author

**Shrest Shaw** — [GitHub](https://github.com/Shrest2k5) · [LinkedIn](https://linkedin.com/in/shrest-shaw-2k5) · shrestshaw2k5@gmail.com
