# HireConnect

HireConnect is a **full-stack job portal** built with React.js, Tailwind CSS, Supabase, Clerk, and Shadcn UI.  
It helps **job seekers** find opportunities and **recruiters** post and manage job listings in a secure, modern, and user-friendly platform.

---

## 🌟 Key Features

- 🔐 **Authentication** – Secure login & signup with Clerk  
- 👨‍💼 **Job Seekers** – Create profile, search jobs, and apply easily  
- 🏢 **Recruiters** – Post jobs, manage applicants, and track listings  
- 🎨 **UI/UX** – Modern, responsive design using Tailwind CSS & Shadcn UI  
- ☁️ **Backend** – Supabase handles database, APIs, and storage  
- 📱 **Responsive** – Optimized for mobile, tablet, and desktop

---

## 👤 Who It's For

- **Students & Freshers** preparing for placements  
- **Job Seekers** looking for new opportunities  
- **Recruiters & Employers** to post and manage job openings  
- **Developers** exploring how to integrate Supabase & Clerk in real-world apps  

---

## ⚙️ Tech Stack

**Frontend:** React.js, Vite, Tailwind CSS, Shadcn UI  
**Backend/Database:** Supabase (Postgres + Auth + Storage)  
**Authentication:** Clerk  
**Deployment:** Vercel  

---

## 📁 Folder Structure

```

HireConnect/
│── public/                # Static assets (favicon, images, etc.)
│── src/                   # Main source code
│   ├── components/        # Reusable UI components
│   ├── pages/             # Page views (Home, Jobs, Dashboard, Auth, etc.)
│   ├── hooks/             # Custom React hooks
│   ├── utils/             # Helper functions
│   ├── App.jsx            # Root component
│   └── main.jsx           # Entry point
│
│── .eslintrc              # ESLint configuration
│── .gitignore             # Git ignore file
│── components.json        # Shadcn UI components config
│── index.html             # HTML entry file
│── jsconfig.json          # Path & alias configuration
│── package.json           # Project dependencies
│── package-lock.json      # Dependency lock file (npm)
│── postcss.config.js      # PostCSS configuration
│── tailwind.config.js     # Tailwind CSS configuration
│── vercel.json            # Deployment config for Vercel
│── vite.config.js         # Vite build configuration
│── yarn.lock              # Dependency lock file (yarn)
│── README.md              # Project documentation

````

---

## 🔑 Environment Variables

Create a `.env` file in the project root and add the following:

```bash
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
````

---

## 🚀 Local Setup

### 1️⃣ Clone and Install

```bash
git clone https://github.com/rajagupta142/HireConnect.git
cd HireConnect
npm install
```

### 2️⃣ Backend (Supabase & Clerk)

* Create a project on [Supabase](https://supabase.com/)
* Copy **Project URL** & **Anon Key**
* Setup [Clerk](https://clerk.com/) for authentication
* Add values to your `.env` file

### 3️⃣ Frontend

```bash
npm run dev
```

Visit 👉 [http://localhost:5173](http://localhost:5173)

---

## ✅ To-Do / Enhancements

* 📄 Resume upload & parsing
* 🔍 Advanced job filters (location, salary, remote)
* 📧 Email notifications for job updates
* 🛠️ Admin dashboard for recruiters
* ⭐ Job bookmarking feature

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 📬 Contact

**Author:** Raja Gupta

* 📌 GitHub: [@rajagupta142](https://github.com/rajagupta142)
* 📌 LinkedIn:


