# 🎬 CineRental -- Movie Rental Web Application

A modern and responsive movie rental application built with **React**,
**Vite**, **Tailwind CSS**, and **React Context API**. It allows users
to explore movies, view details, toggle dark/light mode, and manage a
shopping cart with real‑time notifications.

------------------------------------------------------------------------

## 🚀 Live Demo

👉 **https://your-live-demo-url.com**

------------------------------------------------------------------------

## 📌 Features

### 🎥 Movie Management

-   Browse a collection of movies displayed in a responsive grid layout\
-   View detailed movie information in a modal\
-   Add movies to the cart\
-   Prevents adding duplicates with meaningful toast notifications

### 🛒 Shopping Cart

-   View all selected movies in a cart modal\
-   Remove items from cart\
-   Inline price display\
-   Toast notifications for add/remove actions

### 🌙 Theme Switching

-   Full dark/light mode support powered by TailwindCSS
    `darkMode: 'class'`

### ⚛️ State Management

-   Uses **React Context + useReducer** for global cart management\
-   Maintains theme state using **React Context**

### ✨ Modern UI

-   Built with Tailwind CSS for a clean, professional design\
-   Responsive components\
-   Smooth modals and layout transitions

------------------------------------------------------------------------

## 🧩 Tech Stack

  Technology              Description
  ----------------------- ---------------------
  **React**               Frontend library
  **Vite**                Fast dev bundler
  **TailwindCSS**         Styling
  **React Context API**   State management
  **React Toastify**      Toast notifications

------------------------------------------------------------------------

## 📂 Project Structure

    src/
     ├── assets/
     ├── components/
     ├── cine/
     ├── reducers/
     ├── utils/
     ├── App.jsx
     ├── Page.jsx
     ├── Header.jsx
     ├── Sidebar.jsx
     ├── MovieList.jsx
     ├── MovieCard.jsx
     └── ...

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

``` bash
git clone https://github.com/your-username/cinerental.git
cd cinerental
```

### 2️⃣ Install Dependencies

``` bash
npm install
```

### 3️⃣ Run the Development Server

``` bash
npm run dev
```

### 4️⃣ Build for Production

``` bash
npm run build
```

------------------------------------------------------------------------

## 🧠 Context API Overview

### Theme Context

Provides: - `darkMode` - `setDarkMode()`

### Movie Context

Provides: - `state.cartData` - `dispatch({ type, payload })`

------------------------------------------------------------------------

## 📸 Screenshots (Optional)

You can include UI screenshots here:

    ![Home Page](./screenshots/home.png)
    ![Movie Details](./screenshots/modal.png)

------------------------------------------------------------------------

## 🤝 Contributing

Contributions are welcome!\
Feel free to submit issues or pull requests.

------------------------------------------------------------------------

## 📜 License

This project is licensed under the **MIT License**.

------------------------------------------------------------------------

## ❤️ Acknowledgements

-   Icons & graphics sourced from project assets\
-   Built with modern React & TailwindCSS best practices
