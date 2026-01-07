# React State Management – From Basics to Advanced
## Overview
This project demonstrates **React state management concepts from fundamentals to modern solutions**, with practical examples and clear use cases.

It covers **local state, shared state, global state, and scalable state management patterns** used in real-world React applications.

## 🛍️Concepts Covered

- useState – Local component state

- useEffect – Side effects & lifecycle handling

- Props & Lifting State Up

- React Context API – Global UI state

- Redux Toolkit – Scalable application state

- Zustand – Lightweight global state

- State management comparison

- React state management interview questions

## Tech Stack

- React 18

- JavaScript (ES6+)

- Redux Toolkit

- Zustand

- Tailwind CSS

## 📂 Project Structure

```txt
src/
├── basics/
│   ├── UseStateExample.jsx
│   └── UseEffectExample.jsx
├── context/
│   └── ThemeContext.jsx
├── redux/
│   ├── store.js
│   └── cartSlice.js
├── zustand/
│   └── useStore.js
└── App.jsx
```
## State Management Overview
### useState
Used for local component-level state.
- Forms
- Toggles
- Simple UI interactions

### useEffect
Handles side effects.
- API calls
- Subscriptions
- Cleanup logic
- Props & Lifting State
- Used when multiple components share the same state.
- Simple but leads to prop drilling in large apps
  
### Context API
Provides global state without prop drilling.
- Theme
- Authentication
- Language preferences

### Redux Toolkit
Best for large-scale applications.
- Predictable state
- Centralized store
- Built-in best practices
  
### Zustand
Lightweight alternative to Redux.
- Minimal boilerplate
- No providers
- Easy to scale for medium-sized apps
