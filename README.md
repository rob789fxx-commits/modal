# ✨ React Modal Window

A simple interactive modal window application built with React.

This project was created as part of my React learning journey to practice component creation, state management, conditional CSS classes, animations, and handling user interactions.

## 🚀 Features

- 🪟 **Modal Window** — Opens a popup window when the user clicks a button.
- ❌ **Close Button** — Closes the modal using an SVG close icon.
- 🎬 **Smooth Animations** — Uses CSS animations for opening and closing the modal.
- 🖼️ **Dynamic Content** — Supports displaying different content inside the modal using React `children`.
- 🎨 **SCSS Styling** — Uses SCSS for styling and animations.
- ♻️ **Reusable Component** — The modal is implemented as a separate reusable React component.

## 🛠️ Technologies Used

- React
- JavaScript (ES6+)
- SCSS
- JSX
- React Hooks (`useState`)
- CSS Transitions and Animations

## 📂 Project Structure

```text
src/
├── App.jsx
├── index.scss
└── index.js
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

### 2. Navigate to the project folder

```bash
cd REPOSITORY
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm start
```

## 🎮 How It Works

1. The application initially displays a button labeled **Open Modal**.
2. Clicking the button updates the `open` state to `true`.
3. React adds the `show` CSS class to the modal overlay.
4. CSS transitions display the modal with a smooth animation.
5. The modal displays content passed through the `children` prop.
6. Clicking the close icon changes the `open` state to `false`.
7. The modal closes with a CSS transition.

## 🧠 What I Practiced

During this project, I practiced:

- Creating functional React components.
- Managing component state with `useState`.
- Passing data and functions through props.
- Using the `children` prop to create reusable components.
- Handling click events.
- Applying conditional CSS classes.
- Creating animations with CSS and SCSS.
- Working with SVG elements in React.
- Controlling component visibility using state.

## 📌 Project Purpose

This is an educational project designed to strengthen my understanding of React fundamentals.

The application demonstrates how to create a reusable animated modal window using React state, props, and CSS transitions.