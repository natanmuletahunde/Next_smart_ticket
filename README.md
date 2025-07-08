<div align="center">
  <h1>🎫 Smart Ticketing System</h1>
  <p>A modern ticket management platform built with Next.js 14 (App Router).</p>
  
  <p>
    <img src="https://img.shields.io/badge/-Next.js-000?style=for-the-badge&logo=next.js&logoColor=white" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
    <img src="https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
    <img src="https://img.shields.io/badge/-JSON_Server-F4D03F?style=for-the-badge&logo=json&logoColor=black" />
  </p>

  <p>Manage, create, and track tickets with dynamic routing, SSR/ISR, and a smooth UI ✨</p>
</div>

---

## 🚀 Features

- ✅ Create, Read, Update, Delete (CRUD) tickets
- 📁 File-based routing with dynamic `[id]` pages
- ⚡ Fast refresh and real-time updates with `router.refresh()`
- 🧠 Smart loading using `Suspense` and `loading.js`
- 💅 Styled with Tailwind CSS
- ⏱ Uses `revalidate` for static/dynamic page control
- 🧪 JSON Server as mock backend for testing
- 🔍 Search and filter functionality (optional)
- 📱 Fully responsive

---

## 🧠 Tech Stack

- [Next.js 14 (App Router)](https://nextjs.org/docs/app)
- [React 18](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [JSON Server](https://github.com/typicode/json-server)
- [Node.js](https://nodejs.org)

---

## 📸 Screenshots

| Ticket List | Ticket Details | Create Form |
|------------|----------------|-------------|
| ![List](https://via.placeholder.com/300x180?text=Ticket+List) | ![Details](https://via.placeholder.com/300x180?text=Ticket+Details) | ![Form](https://via.placeholder.com/300x180?text=Create+Ticket) |

---

## 🛠️ Getting Started

### 📦 Clone the Repository

```bash
git clone https://github.com/yourusername/smart-ticket-system.git
cd smart-ticket-system

📥 Install Dependencies

npm install
# or
yarn

🔌 Start JSON Server (Mock API)

npx json-server --watch data/db.json --port 4000

    Make sure db.json is inside data/ folder and includes the tickets array.

🔄 Run the App

npm run dev

Visit: http://localhost:3000
🔃 Folder Structure (App Router)

app/
├── layout.jsx
├── page.jsx (Homepage)
├── loading.jsx
└── tickets/
    ├── page.jsx         # Ticket list
    ├── create/
    │   └── page.jsx     # Create ticket
    └── [id]/
        └── page.jsx     # Ticket details

⚙️ Customization

    To change your mock user email, edit the CreateForm.jsx:

user_email: 'youremail@example.com'

    Customize priority pills using Tailwind in globals.css:

.pill.high {
  @apply text-red-500 border-red-500;
}

🌍 Deployment

Deploy on Vercel in seconds:

🤝 Contributing

    Fork this repo

    Create your feature branch: git checkout -b feature/new-feature

    Commit your changes: git commit -m "Added feature"

    Push to the branch: git push origin feature/new-feature

    Open a pull request ✅

📧 Contact

For questions, reach out to: natanmuleta911@gmail.com
⭐ Show Your Support

If you liked this project:

🌟 Give it a star
🐦 Share it
📢 Follow me

    Built with 💙 by Natan Muleta — Powered by Next.js.


---

Let me know if you want me to generate a custom project logo, badges, or GIF demos too!
