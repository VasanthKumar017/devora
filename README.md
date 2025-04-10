# Devora

A professional, fully extensible microservice-based landing page built with **React** (frontend), **Node.js** (backend), and **SQL** database support. Designed for freelancers, developers, and small agencies to manage and showcase their digital services.

---

## 🚀 Features

- 🔧 **Admin Dashboard** to visually manage services and categories
- 🧠 **Feature Flags** to soft-hide services without deleting
- 🔐 **Authentication-ready** with pluggable login (username/password)
- 💬 **Chatbot support** for client interaction
- 🎯 **SEO & Performance Optimized** (meta tags, sitemap, robots.txt)
- 📱 **Responsive & PWA-ready** (mobile-first design)
- 🔍 **Accessibility-first (a11y)** with ARIA and keyboard navigation
- 📦 **Component-based architecture** with scoped logic & CSS
- 🧱 Scalable file structure & CI/CD-ready

---

## 📂 Project Structure (Simplified)

```
devora/
├── client/               # React frontend
│   └── src/
│       ├── components/   # Reusable UI components
│       ├── pages/        # Page-level views
│       ├── assets/       # Static assets (images, icons)
│       ├── styles/       # Component-scoped CSS
│       └── App.jsx       # App entry point
│
├── server/               # Node.js backend
│   └── src/
│       ├── routes/       # RESTful API routes
│       ├── controllers/  # Business logic
│       ├── models/       # DB models (SQL)
│       └── config/       # DB connection, env config
│
├── .env                  # Environment variables
├── .gitignore            # Git exclusions
├── README.md             # This file
└── package.json          # Project dependencies
```

---

## 📥 Installation

```bash
# 1. Clone the repo
https://github.com/VasanthKumar017/devora.git
cd devora

# 2. Install client and server dependencies
cd client && npm install
cd ../server && npm install

# 3. Create a .env file in /server and /client if needed

# 4. Start development servers
cd client && npm run dev
cd ../server && npm run dev
```

---

## 🧪 Usage

Once running, you can:
- View the landing page on `http://localhost:3000`
- Access admin dashboard (in-progress)
- Add/edit/delete services via admin UI

---

## 🤝 Contributing

We welcome contributions!
1. Fork this repo
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes
4. Commit: `git commit -m 'Add new feature'`
5. Push to your fork
6. Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License** — see `LICENSE` file for details.

---

## 🛠 Templates

### ISSUE_TEMPLATE.md
```markdown
## Issue Summary

- **Bug or Feature**:
- **Steps to Reproduce**:
- **Expected Behavior**:
- **Actual Behavior**:

## Environment
- OS:
- Browser:
- Node Version:
```

### PULL_REQUEST_TEMPLATE.md
```markdown
## Description

- Brief description of what this PR does

## Related Issues

- Closes #issue_number

## Checklist

- [ ] Code compiles without error
- [ ] All new code is covered with tests
- [ ] I have added necessary documentation
```



