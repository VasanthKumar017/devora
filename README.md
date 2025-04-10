# 🚀 Devora

**Devora** is a fully modular, microservice-based landing page and service management platform built with React and Node.js. Designed for freelancers, agencies, or service providers who want a customizable and scalable way to showcase their services — with full admin control, CI/CD support, and future-ready features.

---

## 📦 Tech Stack

| Frontend      | Backend      | Database | Styling       | Auth (Planned) | DevOps         |
|---------------|--------------|----------|----------------|----------------|----------------|
| React         | Node.js + Express | MySQL/PostgreSQL | Tailwind CSS   | Basic Login ➔ JWT (planned) | GitHub Actions (CI/CD) |

---

## 📁 Project Structure

```
devora/
├── client/               # React frontend
│   ├── components/       # Modular components (Header, Services, etc.)
│   ├── styles/           # Per-component CSS
│   └── ...
├── server/               # Node.js backend (Express)
│   ├── routes/
│   ├── controllers/
│   └── ...
├── database/             # SQL schema, seeders
├── .github/
│   ├── workflows/ci.yml  # GitHub Actions CI/CD
│   ├── ISSUE_TEMPLATE.md
│   └── PULL_REQUEST_TEMPLATE.md
├── .gitignore
├── README.md
└── package.json
```

---

## 🛠 Features

- ✅ Modular microservice layout
- ✅ Admin Dashboard to manage services (add/edit/hide)
- ✅ Feature Flags to soft-hide services
- ✅ CI/CD with GitHub Actions
- ✅ Component-based folder organization
- ✅ Easily add/remove services & categories
- ✅ Basic authentication (username/password)
- 🔚 JWT/Sessions for auth
- 🔚 Chatbot integration
- 🔚 Content export (CSV/JSON)

---

## ⚙️ Setup Instructions

### 1. Clone the Repo
```bash
git clone https://github.com/VasanthKumar017/devora.git
cd devora
```

### 2. Install Dependencies
```bash
# For backend
cd server
npm install

# For frontend
cd ../client
npm install
```

### 3. Run Dev Environment
```bash
# Backend
cd server
npm run dev

# Frontend (in another terminal)
cd client
npm run dev
```

### 4. Environment Variables

Create a `.env` file in both `server/` and `client/` folders (if needed) with your credentials like:

```
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASS=yourpassword
```

---

## 🔄 CI/CD Pipeline

This project uses **GitHub Actions** to:

- Lint/test code
- Build client
- Optionally deploy in the future

> Workflow file: `.github/workflows/ci.yml`

---

## 💬 Contributing

1. Fork the repo
2. Create a new branch: `feature/your-feature-name`
3. Commit your changes
4. Push and open a Pull Request

---

## 📄 License

MIT (or add one)

---

## 🧠 Credits

Created by **Vasanth Kumar A M**  
[GitHub](https://github.com/VasanthKumar017) | [Portfolio](https://vasanthkumar017.github.io)
```
