# React + Vite
# 🌿 e‑plantShopping

**e‑plantShopping** is a React-based single-page e‑commerce application that allows users to browse a curated selection of indoor plants, add items to a shopping cart, and manage their order in real time. The project focuses on modern frontend development practices, including component-based architecture, global state management, and responsive UI design.

---

## 📌 Project Overview

This application simulates an online plant shop experience, where users can:

- Explore different categories of plants  
- View plant details including images and prices  
- Add items to a shopping cart  
- Adjust quantities or remove items with instant updates  

The project demonstrates practical usage of **React**, **Redux Toolkit**, and **Vite** to build a clean, fast, and interactive frontend application.

---

## ✅ Features

- 🌱 **Plant Catalog**  
  Browse multiple plant categories displayed using reusable card components.

- 🛒 **Shopping Cart Functionality**  
  - Add plants to the cart  
  - Increase or decrease item quantities  
  - Remove items completely  
  - Automatic price and total calculations  

- 🔄 **Global State Management**  
  Cart state is handled centrally using Redux Toolkit for predictable updates.

- 📊 **Live Cart Counter**  
  The cart icon dynamically reflects the total number of selected items.

- 📱 **Responsive Design**  
  Works smoothly across desktop and mobile screen sizes.

---

## 🧱 Technology Stack

- **React** – Component-based UI development  
- **Redux Toolkit** – Global state management  
- **Vite** – Fast development server and build tool  
- **JavaScript (ES6+)** – Application logic  
- **CSS** – Styling and layout  

---

## 📂 Project Structure

```text
src/
├── components/
│   ├── AboutUs.jsx
│   ├── ProductList.jsx
│   ├── CartItem.jsx
│   └── Navbar.jsx
├── redux/
│   └── CartSlice.jsx
├── App.jsx
├── App.css
└── main.jsx
