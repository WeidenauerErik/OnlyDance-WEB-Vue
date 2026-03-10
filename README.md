# 💻 OnlyDance — Web Frontend (Vue 3)

**OnlyDance Web** is the browser-based counterpart to the OnlyDance AR app. It lets users learn and manage dance choreographies directly in their browser — no AR device required.

Built with **Vue 3** and **TypeScript**, the frontend communicates with the [OnlyDance Symfony Backend](https://github.com/WeidenauerErik/OnlyDance-AR-Symfony) to load dances, manage user accounts, and sync choreographies across platforms.

> 🌐 Live: [onlydance.at](https://onlydance.at)

---

## ✨ Features

- Browse and learn **online choreographies** curated by OnlyDance
- Create, edit, and save your **own dances**
- User **authentication** (register / login)
- Fully responsive design for desktop and mobile
- Real-time sync with the Symfony REST API

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | Vue 3 |
| Language | TypeScript |
| Build Tool | Vite |
| Routing | Vue Router |
| HTTP Client | Fetch API / Axios |
| Backend | [OnlyDance Symfony API](https://github.com/WeidenauerErik/OnlyDance-AR-Symfony) |

---

## 📦 Project Structure

```
OnlyDance-WEB-Vue/
├── src/
│   ├── components/        # Reusable Vue components
│   ├── views/             # Page-level views (routes)
│   ├── router/            # Vue Router configuration
│   ├── stores/            # State management
│   └── assets/            # Static assets
├── public/                # Public root
├── .env                   # Environment variables (API base URL etc.)
├── vite.config.ts         # Vite configuration
└── tsconfig.json
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+

### Installation

```bash
git clone https://github.com/WeidenauerErik/OnlyDance-WEB-Vue.git
cd OnlyDance-WEB-Vue
npm install
```

### Development

```bash
npm run dev
```

The app will be available at `http://localhost:5173`.

### Production Build

```bash
npm run build
```

The compiled output will be in the `dist/` folder, ready to deploy to any static hosting provider.

### Environment Variables

Configure your `.env` file before running:

```env
VITE_API_BASE_URL=https://your-symfony-backend.com/api
```

---

## 🔗 Related Repositories

| Repository | Description |
|---|---|
| [OnlyDance-AR-Symfony](https://github.com/WeidenauerErik/OnlyDance-AR-Symfony) | Backend REST API (Symfony/PHP) |
| [OnlyDance-AR-Unity](https://github.com/WeidenauerErik/OnlyDance-AR-Unity) | AR mobile client (Unity) |

---

## ✨ Author

**Erik Weidenauer**
