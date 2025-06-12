# 🎓 Stream Social LMS 

A **Social Learning Platform** built with **Next.js**, **Supabase**, and **Stream** for real-time chat, video, and audio. 

> ✅ Inspired by: [FreeCodeCamp Article](https://www.freecodecamp.org/news/how-to-build-a-social-learning-platform-using-nextjs-stream-and-supabase/)

## 🚀 Features
- 👥 User Authentication with Supabase
- 💬 Real-time Chat (Stream Chat SDK)
- 🎥 Video & Audio Calling (Stream Video SDK)
- 📦 Supabase Storage for Instructor Headshots
- 🖼️ Beautiful UI with Shadcn UI

---

## ⚙️ Getting Started

1️⃣ **Clone the repository**
```bash
git clone https://github.com/Gyan0706/Learning-Platform.git
cd Learning-Platform
```
2️⃣ **Install dependencies**
```bash
npm install
```
3️⃣ **Setup Environment Variables**
Create a .env.local file and add:
```bash
NEXT_PUBLIC_SUPABASE_URL=<your_supabase_url>
NEXT_PUBLIC_SUPABASE_ANON_KEY=<your_supabase_anon_key>
STORAGE_URL=https://<supabase_url>/storage/v1/object/public/

NEXT_PUBLIC_STREAM_API_KEY=<your_stream_api_key>
STREAM_SECRET_KEY=<your_stream_secret_key>
NEXT_PUBLIC_PAGE_URL=http://localhost:3000
NEXT_PUBLIC_STREAM_CHANNEL_IMAGE_URL=https://api.dicebear.com/9.x/pixel-art/svg?seed=
```
4️⃣ **Configure Supabase**

📂 Setup Supabase tables, Row Level Security (RLS) policies

🖼️ Create a Supabase storage bucket called headshots

5️⃣ **Start the development server**
```bash
npm run dev
```
🧰 **Tech Stack & Tools**
| Tool             | Usage                                         |
| ---------------- | --------------------------------------------- |
| **Next.js**      | Frontend Framework                            |
| **Shadcn UI**    | Modern UI Components                          |
| **Supabase**     | Auth & Database                               |
| **Stream Chat**  | Real-time Messaging                           |
| **Stream Video** | Audio & Video SDK for Real-time Communication |

📄 **References**

- [Shadcn UI Docs](https://ui.shadcn.com/docs/installation)
- [Supabase Auth with Next.js](https://supabase.com/docs/guides/auth/server-side/nextjs)
- [Stream Chat SDK](https://getstream.io/chat/docs/sdk/react/)
- [Stream Video SDK](https://getstream.io/video/docs/react/)


