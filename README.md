# 🚀 DevStack – Technology Stack Explorer

## 📝 Description

DevStack is a modern and responsive web application where users can explore different technologies and manage their personal technology stack.

## 🛠️ Technologies Used

- React.js
- TypeScript
- Tailwind CSS
- DaisyUI
- React-Toastify
- JSON
- Vite

## ✨ 3 Features

1. 🔍 **Explore Technologies** – Users can browse and explore different technologies.
2. 📚 **Manage Tech Stack** – Users can add and remove technologies from their personal stack.
3. 📱 **Responsive Design** – The website works smoothly on desktop, tablet, and mobile devices.















## ❓ React Questions & Answers

### 1. What is JSX, and why is it used in React?

JSX lets us write HTML-like code inside JavaScript. It makes React code easier to write and understand.

### 2. What is the difference between props and state?

Props are used to pass data from a parent to a child component. State is used to store and manage data inside a component.

### 3. What does the `useState` hook do, and where did you use it in this project?

`useState` is used to store and update data in a component. I used it to manage the selected technology stack.

### 4. What does the `useEffect` hook do, and why did you need it to load the JSON data?

`useEffect` is used to run code after the component renders. I used it to load the JSON data when the website starts.

### 5. Why does every item in a `.map()` list need a unique `key` prop?

The `key` helps React identify each item in a list. It helps React update the list correctly.

### 6. What is conditional rendering? Show one place you used it.

Conditional rendering means showing something based on a condition. I used it to show an empty stack message when there are no items.

```jsx
{stack.length === 0 ? (
  <p>Your stack is empty.</p>
) : (
  stack.map((item) => <StackCard key={item.id} item={item} />)
)}
```

### 7. How do you pass data from a parent component to a child component, and how does a child send something back to the parent?

A parent passes data to a child using props. The child can send data back by calling a function passed from the parent through props.
