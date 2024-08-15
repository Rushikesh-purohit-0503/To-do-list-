# Todo List App

![React](https://img.shields.io/badge/React-v18.2.0-blue.svg?style=flat&logo=react)
![Vite](https://img.shields.io/badge/Vite-v4.0.0-blueviolet.svg?style=flat&logo=vite)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v3.2.0-38B2AC.svg?style=flat&logo=tailwind-css)
![License](https://img.shields.io/badge/License-MIT-green.svg)

# **In this learning project one can get the knowledge of context API in React.js** 
## 📝 Overview

The **Todo List App** is a web application that allows users to manage their tasks with features like adding, editing, deleting, and marking tasks as completed. This app is built using **React**, **Vite**, and **Tailwind CSS** for a fast, modern, and responsive user experience.

## ✨ Features

- ✅ **Add Tasks**: Add new tasks with ease.
- ✏️ **Edit Tasks**: Modify existing tasks.
- ❌ **Delete Tasks**: Remove tasks when no longer needed.
- 🔄 **Toggle Completion**: Mark tasks as completed or pending.
- 💻 **Responsive Design**: Designed with Tailwind CSS for a seamless experience across devices.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/en/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

**1. Clone the repository**:

   ```bash
   git clone https://github.com/Rushikesh-purohit-0503/To-do-list.git
   cd todo-list-app
  ```

**2. Install Dependencies**:

  ```bash
  npm install
  ```

**3. Start the Development Server**:
  ```bash
  npm run dev
  ```

## 📂 Project Structure

- **`src/`**: Contains all the source code.
  - **`components/`**: React components for the app.
  - **`context/`**: Context providers and custom hooks.
  - **`App.css`**: Global styles for the app.
  - **`index.js`**: Entry point for the React app.

## 🛠 Technologies Used

- **[React](https://reactjs.org/)**: Front-end library for building user interfaces.
- **[Vite](https://vitejs.dev/)**: Next-generation front-end tooling for fast development and build times.
- **[Tailwind CSS](https://tailwindcss.com/)**: Utility-first CSS framework for rapid UI development.

## 🔧 Configuration

### 🖌 Tailwind CSS Configuration

Customize your design in `tailwind.config.js` or add custom styles in `src/index.css`.

Example `tailwind.config.js`:

  ```bash
  /** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
  ```
## 📝 Usage

- **Adding a Todo**: Enter a todo message and click "Add" to create a new todo item.
- **Editing a Todo**: Click the pencil icon to enable editing. Update the message and click the file icon to save.
- **Toggling Completion**: Click the checkbox to mark a todo as completed or not completed.
- **Deleting a Todo**: Click the trash can icon to remove a todo item.

## ⚙️ Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository.**
2. **Create a new branch** for your feature or bugfix.
3. **Make your changes** and commit them with descriptive messages.
4. **Push your changes** to your forked repository.
5. **Submit a pull request** with a detailed description of your changes.


## 🏁 Conclusion

This project provides a practical example of using the Context API in React. By managing state with the Context API, the app demonstrates how to share data across components without prop drilling, making it a valuable learning experience for anyone looking to understand state management in React.

