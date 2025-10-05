<p align="center">
  <!-- Outlined SVG Logo -->
  <svg width="320" height="80" viewBox="0 0 320 80" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="LUMORA Logo">
    <rect width="320" height="80" fill="none"/>
    <path d="M20 60V20h10v30h20v10H20z" fill="#C6A664"/> <!-- L -->
    <path d="M70 60V20h10v40h-10z" fill="#C6A664"/> <!-- U -->
    <path d="M110 60V20h30v10h-20v5h15v10h-15v15h-10z" fill="#C6A664"/> <!-- M -->
    <path d="M160 60V20h15c10 0 15 5 15 10s-5 10-10 10c5 0 10 5 10 10s-5 10-15 10h-15zM175 35c3 0 5-2 5-5s-2-5-5-5h-5v10h5zM175 50c3 0 5-2 5-5s-2-5-5-5h-5v10h5z" fill="#C6A664"/> <!-- O -->
    <path d="M220 60V20h10l15 20V20h10v40h-10l-15-20v20h-10z" fill="#C6A664"/> <!-- R -->
    <path d="M280 60V20h15c10 0 15 5 15 10s-5 10-15 10h-5v20h-10zM295 35c3 0 5-2 5-5s-2-5-5-5h-5v10h5z" fill="#C6A664"/> <!-- A -->
  </svg>
</p>

<h1 align="center">🌟 LUMORA</h1>
<p align="center"><b>Shining the Future of Freelancing in Dubai & UAE</b></p>

---

## 📖 Introduction
**LUMORA** is a bilingual digital platform (English & Arabic) designed to connect freelancers with businesses and employers across Dubai and the UAE.  

The brand identity is inspired by Dubai’s balance of **heritage & innovation**:  
- 🌞 **Light Mode** reflects desert sand, golden tones, and calm elegance.  
- 🌙 **Dark Mode** symbolizes Dubai’s vibrant nightlife, metallic gold luxury, and neon accents.  

The name *LUMORA* comes from *“Lumen” (light)* + *“Ora” (time)*, representing *a bright future in the digital era*.  

---

## 🎯 Vision & Mission
- 🌍 Build a trusted bridge between freelancers and employers in the UAE.  
- 💼 Empower global talent to access opportunities in Dubai.  
- 🔒 Provide transparency and security in hiring and payments.  
- 🤝 Foster collaboration through modern project management tools.  

---

## ⚙️ Core Features
- **Bilingual Platform (EN/AR)** 🌐  
- **User Profiles** for freelancers & employers  
- **Smart Job Posting & Bidding System**  
- **Secure Payments (Escrow)** 💳  
- **Real-Time Chat** 💬  
- **Project Tracking & File Sharing** 📂  
- **Ratings & Reviews** ⭐  
- **Light/Dark Mode with Dubai-inspired palette** 🎨  

---

## 🎨 Design Language

### 🌞 Light Mode
- **Background**: `#F9F6F1` (Off-white desert sand)  
- **Primary Gold**: `#C6A664`  
- **Text Color**: `#1F1F1F`  
- **Luxury Gray**: `#D1C7B8`  
- **Accent**: `#0D6E6E` (Modern deep teal)  

### 🌙 Dark Mode
- **Background**: `#0E0E0E`  
- **Metallic Gold**: `#D4AF37`  
- **Text**: `#FFFFFF`  
- **Luxury Gray Shadows**  
- **Accent**: `#1AA6A6` (Dubai neon teal)  

---

## 📂 Project Structure (Next.js 15 App Router)
```bash
/app                  → Next.js App Router: routes & layouts
   /dashboard         → Nested dashboard route
   /quiz              → Quiz routes
   /api               → API Routes (route.ts)
   /components        → React components
   /providers         → Theme/Zustand/Context providers
   /styles            → Tailwind & global styles
/public                → Static assets (logos, images, SVGs)
README.md
package.json
tsconfig.json
next.config.js
