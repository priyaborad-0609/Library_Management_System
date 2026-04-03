<div align="center">

# 📚 Library Management System

### A fully dynamic & feature-rich Library Management System built with React.js ⚛️

This project simulates real-world library operations — Books, Members, Issuing/Returning, Fines, and Reports — all handled from the frontend with no backend required.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

## 🎬 Demo Video

<div align="center">

[![Watch Demo Video](https://img.shields.io/badge/▶%20Watch%20Demo-Google%20Drive-blue?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1VaXH9Hc2MN-gu38WVbALk3hTybRn8jDI/view?usp=sharing)

</div>

---

 The dashboard shows live stats — total books, members, issued books, fines, and reservations — along with a bar chart overview and a book rating distribution pie chart.

---

## 📌 Overview

A complete **Library Management System** built entirely on the frontend using React.js. Manage books, members, issue/return cycles, and fines — all from a clean, responsive UI with data persisted via `localStorage`.

---

## 🚀 Features

### 📖 Books Management
- Add new books (title, author, genre, ISBN, price, availability)
- Edit and update book details (edition, availability, etc.)
- Delete outdated or removed books
- Search & filter by title, author, or genre
- Track availability status — **Available**, **Issued**, **Reserved**

### 👥 Member Management
- Add members with full details (ID, name, email, phone, address)
- Update member information anytime
- Delete inactive members
- Search by name or member ID
- Assign membership type — **Student**, **Faculty**, or **Public**

### 🔄 Issue & Return
- Issue books to members with a set due date
- Auto-update book availability on issue/return
- Support multiple books issued per member
- Smooth return handling with status tracking

### 💰 Fine Management
- Automatic late return fine calculation
- View fine history per member
- Mark fines as paid / unpaid

### 🔑 Admin Controls
- Admin login with basic authentication
- Full CRUD operations across all modules
- Dashboard with key stats at a glance

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React.js | UI & component logic |
| Tailwind CSS | Styling |
| React Router v6 | Client-side routing |
| localStorage | Data persistence |
| Vite | Build tool & dev server |

---


## 📁 Project Structure
```
library-management-system/
├── public/
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # Books, Members, Issue, Fines, Dashboard
│   ├── context/          # Global state management
│   ├── utils/            # Fine calculation, date helpers
│   ├── App.jsx
│   └── main.jsx
├── screenshots/
│   └── dashboard.png
├── package.json
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the project
2. Create your feature branch — `git checkout -b feature/AmazingFeature`
3. Commit your changes — `git commit -m 'Add some AmazingFeature'`
4. Push to the branch — `git push origin feature/AmazingFeature`
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
Made with ❤️ using React.js
</div>
