## 🚀 30-Day Coding Challenge: Day 29

This project is the twenty-ninth entry in my 30-day coding challenge. Today's goal was to build a complete, data-driven application that combines many of the React concepts learned so far. This simple blog demonstrates full CRUD (Create, Read, Update, Delete) functionality, client-side view management, and data persistence.

### 📖 Project Overview

This is a fully functional, single-page blog application built with React. It allows users to create new posts using Markdown, view a list of all posts, read individual posts in a formatted view, edit existing posts, and delete them. All blog posts are saved to the browser's `localStorage`, ensuring that the content persists between sessions. The application manages different views (list, read, edit, create) using React state to simulate a multi-page experience.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jul-04-2025 18-57-33](https://github.com/user-attachments/assets/11547c69-f90e-4855-92ca-0ffcce4e088e)


### 🌟 Key Features

* **Full CRUD Operations:** Users can Create, Read, Update, and Delete blog posts.
* **Persistent Storage:** All posts are automatically saved to `localStorage`, so no data is lost on page refresh.
* **Markdown Support:** The post editor accepts Markdown syntax, which is then parsed and rendered as styled HTML in the reading view using the `marked.js` library.
* **Client-Side View Management:** A state-driven approach handles rendering different "pages" (list, view, edit, create) within a single-page application structure.
* **Component-Based Architecture:** The application is logically broken down into components for each view (`PostList`, `PostView`, `PostEditor`).
* **Clean & Responsive UI:** A clean, blog-style layout built with Tailwind CSS that is easy to navigate and works well on all devices.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/Marked.js-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=white)

* **React:** The core library for building the user interface and managing state.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Marked.js:** The third-party library used for Markdown parsing.
* **Tailwind CSS:** For all styling and layout.
* **Font Awesome:** For icons.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-simple-blog.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-simple-blog
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a comprehensive exercise that brought together many key React concepts:

* **Implementing Full CRUD:** Mastering the logic for creating, reading, updating, and deleting items from an array in state.
* **Managing Views with State:** Implementing a simple form of client-side routing to create a single-page application feel.
* **Persisting Complex State:** Using `localStorage` and `useEffect` to save and load an array of objects, making the application stateful across sessions.
* **Integrating Third-Party Libraries:** Using an external library like `Marked.js` to add powerful functionality.
* **Component Communication:** Building a more complex application where multiple components communicate with a central parent component via props and callback functions.
