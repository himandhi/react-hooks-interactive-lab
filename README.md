# React Hooks Interactive Lab

## 📌 Project Overview

This project is an interactive learning lab built using **React** to understand and practice **React Hooks** from basic to advanced level.

Instead of building a normal application, this project focuses on **learning each React Hook separately** using small interactive demos.  
Each hook is shown with a short explanation and a live example so learners can clearly understand how it works.

The project is divided into **3 days**:
- Day 1 – Core Hooks
- Day 2 – Performance & Structure Hooks
- Day 3 – Custom Hooks

---

## ✨ Features

- Single Page React Application
- Sidebar with list of React Hooks (Day 1, Day 2, Day 3)
- Search bar to quickly find hooks
- Live interactive demo for each hook
- Simple UI for easy understanding
- Clean folder structure with separated lab components
- Custom hooks implemented and reused

---

## ⚙️ How the Project Works

- The **Header** contains the project title and a search input.
- The **Sidebar** shows all available hooks.
- When a hook is selected, the **Main Panel** displays:
  - The hook name
  - A short explanation
  - A live interactive demo

Each hook demo is written as a **separate component** to keep the code clean and understandable.

Custom hooks are stored in a separate `hooks` folder and reused inside demo components.

---

## 📚 React Hooks Covered

### 🔹 Day 1 – Core Hooks
- `useState` – State management with counter and input
- `useEffect` – Timer with cleanup
- `useRef` – Input focus and previous value tracking
- `useId` – Accessible form IDs

### 🔹 Day 2 – Structure & Performance
- `useMemo` – Expensive calculation caching
- `useCallback` – Stable function reference
- `useContext` – Sharing data without prop drilling
- `useReducer` – Action-based state management

### 🔹 Day 3 – Custom Hooks
- `useToggle` – Boolean toggle logic
- `useInput` – Reusable input handling
- `useDebounce` – Delayed value update
- `usePrevious` – Store previous value

---

## 🗂️ Folder Structure

```plaintext
react-lab-final/
└── hook-playground/
    ├── node_modules/
    ├── public/
    ├── src/
    │   ├── assets/
    │   ├── hooks/                 # Custom reusable hooks
    │   │   ├── useDebounce.jsx
    │   │   ├── useInput.jsx
    │   │   ├── usePrevious.jsx
    │   │   └── useToggle.jsx
    │   ├── labs/                  # Individual hook demo components
    │   │   ├── UseStateLab.jsx
    │   │   ├── UseEffectLab.jsx
    │   │   ├── UseRefLab.jsx
    │   │   ├── UseIdLab.jsx
    │   │   ├── UseMemoLab.jsx
    │   │   ├── UseCallBackLab.jsx
    │   │   ├── UseContextLab.jsx
    │   │   ├── UseReducerLab.jsx
    │   │   ├── UseDebouncedLab.jsx
    │   │   ├── UseInputLab.jsx
    │   │   ├── UsePreviousLab.jsx
    │   │   └── UseToggleLab.jsx
    │   ├── App.jsx                # Main application component
    │   ├── App.css
    │   ├── main.jsx               # Application entry point
    │   └── index.css
    ├── .gitignore
    ├── eslint.config.js
    ├── index.html
    ├── package.json
    ├── package-lock.json
    ├── README.md
    └── vite.config.js
```
---

## 🛠️ Technologies Used

- React
- Vite
- JavaScript (ES6)
- HTML
- CSS
- VS Code
- Git & GitHub

---

## ▶️ How to Run the Project Locally

1. Clone the repository
2. Navigate to the project folder
3. Install dependencies:
    npm install
4. Start the development server:
    npm run dev
5. Open the browser and visit:
    http://localhost:5173

---

## 🎯 Conclusion

This project helped me gain a strong understanding of **React Hooks** by building practical examples instead of only learning theory.

By completing this interactive lab, I learned:
- How React re-renders components
- How to manage side effects
- How to improve performance
- How to create and reuse custom hooks
- How to structure a real React project

This project was built as part of a **React Hooks Bootcamp Project**.

