# Form Creation and Valid

---

# TASK 1:

Welcome to the **Deep Dive into JavaScript** project!

This project focuses on building a user registration form that performs client-side validation and fetches user data from a public API.

## 🧠 Learning Objectives

By completing this project, you will learn to:

- ✅ Validate form inputs using JavaScript.
- ✅ Interact with HTML elements using the DOM.
- ✅ Fetch and display data from a public API using asynchronous JavaScript.
- ✅ Provide real-time user feedback and persist data using local storage.

## 📁 Project Structure

```bash
Form-Creation-Validation/
├── index.html       # Registration form with required fields
├── style.css        # Basic styling for the form
└── script.js        # JS validation logic and DOM handling
```

## Form Creation and Validation

### 🧱 HTML (`index.html`)

Contains a registration form with fields:
- `username`
- `email`
- `password`

### 🎨 CSS (`style.css`)

Styles the form with responsiveness and accessibility in mind.

### 🔁 JavaScript (`script.js`)

Implements:

- `DOMContentLoaded` event listener
- Form selection with `getElementById`
- Input trimming and validation
- Real-time feedback using a `div`
- Form validation logic for:
  - Username (min. 3 characters)
  - Email (contains '@' and '.')
  - Password (min. 8 characters)

### 💡 Validation Example

If validation passes:
```
Registration successful!
```

If validation fails:
```
- Username must be at least 3 characters long
- Email must include "@" and "."
- Password must be at least 8 characters long
```

## ✅ Repository Requirements

- **Repository Name**: `Form-Creation-Validation`
- **Files to Include**:
  - `index.html`
  - `style.css`
  - `script.js`

---

# TASK 2: *fetch-data*

## 🌐 Fetching User Data from an API

This module fetches user data from the public API at [JSONPlaceholder](https://jsonplaceholder.typicode.com/users) and displays a list of names on the webpage.

### 🧠 Features

- Asynchronous data fetching using `fetch()` and `async/await`.
- Error handling with fallback messages.
- Clean, responsive user interface.

### 🧪 Example Output

User List:

`Leanne Graham`

`Ervin Howell`

`Clementine Bauch`

---

## 🚀 My Happy Coding!

*Master JavaScript DOM manipulation and form validation.*

---

&copy; October 10 - October 20, 2025

ALX Africa | Front-end Development. All rights reserved.
