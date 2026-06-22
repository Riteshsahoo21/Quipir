# 🚀 Quipir

**Quipir** is a full-stack AI Creator Platform and CMS that enables users to generate, manage, and enhance content using Generative AI. Turn your ideas into engaging posts, articles, and media in seconds, then publish and share them with the community through a social experience inspired by platforms like X (formerly Twitter).

## 🛠️ Tech Stack

* **Framework:** Next.js 15
* **Frontend:** React 19
* **Styling:** Tailwind CSS
* **UI Components:** Shadcn UI
* **Backend & Database:** Convex
* **Authentication:** Clerk
* **Rich Text Editor:** React Quill
* **Media Management:** ImageKit (Image & Video APIs with AI-powered Digital Asset Management)
* **AI Integration:** Gemini API for Generative AI

## ✨ Features

* 🤖 Generate high-quality content with Generative AI
* 📝 Create and edit posts using a rich text editor
* 🖼️ Upload, organize, and manage images with ImageKit
* 🔐 Secure authentication and user management with Clerk
* 📂 AI-powered Content Management System (CMS)
* 🌐 Publish and share content through a social feed
* ⚡ Real-time backend and data synchronization powered by Convex
* 📱 Responsive, modern UI built with Tailwind CSS and Shadcn UI

# PREVIEW




https://github.com/user-attachments/assets/dc2a406f-4dae-40b4-b265-d3002f542c09




## 🚀 Setup

### 1. Clone the repository

```bash
git clone https://github.com/Riteshsahoo21/Quipir.git
cd creatr
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create a `.env.local` file

Create a `.env.local` file in the project root and add your own credentials:

```env
# Convex
CONVEX_DEPLOYMENT=your_convex_deployment
NEXT_PUBLIC_CONVEX_URL=https://your-project.convex.cloud
NEXT_PUBLIC_CONVEX_SITE_URL=https://your-project.convex.site

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

CLERK_JWT_ISSUER_DOMAIN=https://your-clerk-domain.clerk.accounts.dev

# ImageKit
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=https://ik.imagekit.io/your_endpoint
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key

# Unsplash
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=your_unsplash_access_key

# Gemini
GEMINI_API_KEY=your_gemini_api_key
```

### 4. Start the development server

```bash
npm run dev
```

Visit **http://localhost:3000** in your browser to access the application.










https://github.com/user-attachments/assets/dfcfa410-3bed-491f-95cb-2d39c93ef28a

