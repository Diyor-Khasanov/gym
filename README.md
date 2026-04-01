# 🏋️ Gymate — Gym Web Application

A modern, responsive **gym website** built with **React 18**, **Firebase**, and **Tailwind CSS**. Gymate offers a clean and engaging interface for a fitness-focused audience, featuring smooth page navigation, an image carousel, and Firebase-powered backend services.

🔗 **Live Demo:** [gym-xi-ten.vercel.app](https://gym-xi-ten.vercel.app)

---

## ✨ Features

- 🏠 **Landing Page** — Visually rich hero section and gym highlights
- 🎠 **Image Carousel** — Smooth, responsive image slider via `react-responsive-carousel`
- 🔐 **Firebase Integration** — Authentication and/or database support powered by Firebase
- 🌍 **Client-side Routing** — Multi-page navigation with React Router DOM v6
- 📱 **Fully Responsive** — Mobile-first design using Tailwind CSS
- ⚡ **Fast & Lightweight** — Built with Create React App for an optimized production build

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Framework | React 18 |
| Styling | Tailwind CSS 3 |
| Backend / Auth | Firebase 9 |
| Routing | React Router DOM 6 |
| Carousel | react-responsive-carousel |
| Build Tool | Create React App (react-scripts) |
| Testing | React Testing Library, Jest |
| Deployment | Vercel |

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** v16 or higher
- **npm** v8 or higher

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Diyor-Khasanov/gym.git

# 2. Navigate into the project
cd gym

# 3. Install dependencies
npm install
```

### Firebase Setup

This project uses Firebase. To connect your own Firebase project:

1. Go to [Firebase Console](https://console.firebase.google.com/) and create a new project.
2. Register a web app and copy your Firebase config.
3. Create a `.env` file in the project root and add your credentials:

```env
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

### Running Locally

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Building for Production

```bash
npm run build
```

The optimized output will be in the `build/` folder.

### Running Tests

```bash
npm test
```

---

## 📁 Project Structure

```
gym/
├── public/               # Static assets (favicon, index.html)
├── src/
│   ├── components/       # Reusable UI components (Navbar, Footer, Carousel, etc.)
│   ├── pages/            # Route-level page components (Home, About, etc.)
│   ├── firebase.js       # Firebase configuration & initialization
│   ├── App.js            # Root component with routing
│   └── index.js          # Application entry point
├── tailwind.config.js    # Tailwind CSS configuration
├── package.json          # Project metadata & dependencies
└── .gitignore
```

---

## 📦 Deployment

This project is deployed on **Vercel**. To deploy your own instance:

1. Fork this repository.
2. Import the repo into [Vercel](https://vercel.com).
3. Add your Firebase environment variables in the Vercel project settings.
4. Vercel will auto-detect Create React App — click **Deploy**.

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

---

## 👤 Author

**Diyor Khasanov**
- GitHub: [@Diyor-Khasanov](https://github.com/Diyor-Khasanov)
