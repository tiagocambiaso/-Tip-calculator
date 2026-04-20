# 💰 Tip & Consumption Calculator

A professional-grade tip and consumption calculator built with **React** and **TypeScript**. This project focuses on complex state management using the `useReducer` hook, providing a clean and scalable architecture for handling restaurant orders and tip percentages.

## ✨ Key Features

* **Menu Management:** Select items from a predefined menu to build a consumption list.
* **Custom Tip Percentages:** Choose between different tip levels (10%, 20%, 50%) to calculate the final amount.
* **Real-time Order Tracking:** The application automatically calculates the subtotal, the total tip amount, and the final grand total as you add or remove items.
* **Clean State Transitions:** Features a "Place Order" functionality that clears the current session, simulating a real-world checkout flow.

## 🛠️ Technologies and Tools

* **Core:** React 18 + TypeScript + Vite.
* **Styling:** Tailwind CSS (v4).
* **State Management:** Advanced React Hooks.
* **Deployment:** Vercel.

## 🧠 Technical Highlights: Why useReducer?

In this project, I migrated the logic from multiple `useState` calls to a centralized **`useReducer`** architecture. This approach offers several advantages:

* **Centralized Logic:** All order modifications (adding items, removing items, setting tips, and clearing the order) are handled within a single reducer function.
* **Type Safety:** Leveraging TypeScript interfaces for both the `State` and the `Actions`, ensuring the data flow is predictable and bug-free.
* **Scalability:** The logic is decoupled from the UI components, making it easier to maintain and extend with new features in the future.
* **Optimization:** Used alongside React best practices to ensure efficient rendering.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone [https://github.com/tiagocambiaso/-Tip-calculator]