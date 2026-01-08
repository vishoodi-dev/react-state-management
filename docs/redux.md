# React Redux

## 📌 Three core Cocept?
**Shop** - That holds the state of your application
**action** - that describes the changes in the state of the application.
**reducer** - which actually carries out the state transition depending on the action

---

## 🧠 Three Principles
### **First Principle** The state of your whole application is stored in an object tree within a single store. 


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
