# 💱 Currency Converter App

A simple and responsive **Currency Converter** built using **React** and **Tailwind CSS**.  
It allows users to convert amounts between different currencies using real-time exchange rates.

---

## 🚀 Features

- 🌍 Convert between multiple currencies
- 🔄 Swap **From** and **To** currencies
- ⚡ Real-time exchange rates using API
- 🎨 Full-screen background image
- 📱 Fully responsive (mobile-friendly)
- ♿ Accessible inputs using `useId`
- 🧩 Reusable `InputBox` component

---

## 🛠️ Tech Stack

- **React (Vite)**
- **Tailwind CSS**
- **JavaScript (ES6+)**
- **Custom React Hooks**
- **Currency Exchange API**

---

## 📁 Folder Structure

src/
├── components/
│ ├── InputBox.jsx
│ └── index.js
├── hooks/
│ └── useCurrencyInfo.js
├── App.jsx
├── main.jsx
└── index.css

## 🧠 How It Works

- The user enters an amount in the input box
- Selects the **source** and **target** currency
- Exchange rates are fetched using a custom hook
- The converted amount is calculated instantly
- Components are reused for clean and maintainable code

## 🙌 Conclusion

This project demonstrates core React concepts such as reusable components,
custom hooks, state management, and responsive UI design using Tailwind CSS.
