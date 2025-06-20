# 📦 Droply — Storage and File Sharing Platform

**Droply** is a modern file storage and sharing platform built with Next.js 15, React 19, TailwindCSS, Appwrite, and TypeScript. Upload, manage, and share files securely with a clean, fast, and responsive UI.

---

## 📚 Table of Contents

- 🤖 Introduction  
- ⚙️ Tech Stack  
- 🔋 Features  
- 🚀 Quick Start  
- 🕸️ Snippets  
- 🔗 Assets  
- 📺 More  
- 🤝 Contributing  
- 👨‍💻 Author

---

## 🤖 Introduction

**Droply** makes file management easy — allowing users to upload, organize, and share files with ease. Built using the latest web technologies like **Next.js 15**, **React 19**, and **Appwrite**, Droply combines speed, simplicity, and modern design in one intuitive experience.

---

## ⚙️ Tech Stack

- **Next.js 15** – Full-stack React framework with server components  
- **React 19** – Latest UI framework with concurrent rendering  
- **Appwrite** – Backend-as-a-Service for storage, auth, database  
- **Tailwind CSS** – Utility-first styling framework  
- **ShadCN** – Accessible and customizable UI components  
- **TypeScript** – Strongly typed JavaScript  
- **Vercel** – Hosting & deployment platform for frontend frameworks

---

## 🔋 Features

- 🔐 **Appwrite Authentication** – Signup, login, logout functionality  
- 📤 **File Uploads** – Upload documents, images, videos, and more  
- 📁 **Manage Files** – Preview, rename, delete, and organize your files  
- 📥 **Download** – Download any file directly  
- 🔗 **Share** – Create and copy shareable public links  
- 📊 **Dashboard** – View stats like total storage, file breakdown, recent uploads  
- 🔍 **Global Search** – Search files instantly  
- ↕️ **Sorting** – Sort by file name, size, or date  
- 📱 **Fully Responsive** – Optimized for all screen sizes

---

## 🚀 Quick Start

### 🔧 Prerequisites

Make sure you have the following installed:

- Git  
- Node.js  
- npm  

### 📥 Clone, Install & Run

```bash
# Clone the repository
git clone https://github.com/your-username/droply.git
cd droply

# Install dependencies
npm install

# Create a `.env.local` file in the root and add your Appwrite credentials:
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT="your_project_id"
NEXT_PUBLIC_APPWRITE_DATABASE="your_database_id"
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION="your_users_collection_id"
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION="your_files_collection_id"
NEXT_PUBLIC_APPWRITE_BUCKET="your_bucket_id"
NEXT_APPWRITE_KEY="your_secret_api_key"

# Replace all placeholders with your actual values from Appwrite console

# Start the development server
npm run dev

# Open in your browser
http://localhost:3000
```

---

## 🕸️ Snippets

Helpful files and utilities used in Droply:

- `tailwind.config.ts` – Tailwind setup  
- `globals.css` – Global styles  
- `constants/index.ts` – App constants  
- `lib/utils.ts` – Utility functions  
- `index.d.ts` – Custom types

---

## 🔗 Assets

- Appwrite – [https://appwrite.io](https://appwrite.io)  
- Vercel – [https://vercel.com](https://vercel.com)  
- Lucide Icons – [https://lucide.dev](https://lucide.dev)  
- Google Fonts – [https://fonts.google.com](https://fonts.google.com)

---

## 📺 More

Enhance **Droply** by adding:

- 🗂️ Folder and tag system  
- 🔒 Role-based file access  
- 📬 Email notifications for uploads or shares  
- 🎨 Dark/light mode toggle  
- 🌍 Multi-language support  
- 💬 File preview & comment system

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

## 👨‍💻 Author

Created by [@arpit-negi](https://github.com/arpit-negi)  
Built with ❤️ to simplify cloud storage for modern teams and individuals.
