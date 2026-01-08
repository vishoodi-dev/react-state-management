# React State Management – Fundamentals

## 📌 What is State in React?
**State** is a built-in React object used to store data or information about a component.  
When state changes, the component **re-renders** to reflect the updated UI.

State is:
- Mutable
- Local to a component (by default)
- Managed internally by React

---

## 🧠 Why State is Important
State allows React applications to be:
- **Dynamic**
- **Interactive**
- **Data-driven**

Without state, React components would be static and unable to respond to user actions.

---

## 🧩 Local State vs Global State

### Local State
- Used within a single component
- Managed using `useState` or `useReducer`
- Best for UI-specific data

**Examples:**
- Input values
- Toggle buttons
- Modal open/close

### Global State
- Shared across multiple components
- Managed using Context API or libraries like Redux, Zustand

**Examples:**
- User authentication
- Theme (dark/light mode)
- Cart data

---

## ⚙️ useState Hook

### Syntax
```js
const [state, setState] = useState(initialValue);
