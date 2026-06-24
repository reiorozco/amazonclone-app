<h1 align="center">🛒 Amazon Clone</h1>

<p align="center">
  An e-commerce Amazon clone with cart, authentication and Stripe payments.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white"/>
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge"/>
</p>

## ✨ Features

- 🛍️ Product catalog and shopping cart
- 🔐 Authentication with Firebase Auth
- 💳 Checkout with Stripe payments
- 🗄️ Orders persisted in Firebase
- 🧮 State management with Redux Toolkit

## 🛠️ Tech Stack

- **Core:** React · Vite
- **State:** Redux Toolkit · React Redux
- **Backend services:** Firebase (Auth + Firestore) · `react-firebase-hooks`
- **Payments:** Stripe (`@stripe/react-stripe-js`)
- **UI:** Material UI (MUI) · Emotion
- **Routing:** React Router

## 🚀 Getting Started

```bash
git clone https://github.com/reiorozco/amazonclone-app.git
cd amazonclone-app
npm install
```

### Environment variables
Create a `.env` from `.env.example` with your Firebase and Stripe credentials.

### Run
```bash
npm run dev      # start dev server
npm run build    # production build
npm run preview  # preview production build
```

> ℹ️ A Stripe webhook / functions backend is required for live payments.

## 📸 Screenshots

> _Add screenshots or a short GIF of the storefront and checkout here._

## 📄 License

Released under the [MIT License](LICENSE).
