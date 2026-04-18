# Counter Web App

A simple and responsive counter application built using HTML, CSS, and JavaScript.
It allows users to increment, decrement, reset, and store the counter value using browser storage.

---

## Features

* Increase and decrease counter
* Reset counter to zero
* Save counter value using localStorage
* Load saved value after refresh
* Responsive design for mobile and desktop
* Basic animations for better user experience

---

## Technologies Used

* HTML
* CSS
* JavaScript

---

## How It Works

* The counter value is stored in a variable (`count`)
* The UI is updated dynamically using JavaScript
* The value is saved using:

  ```js
  localStorage.setItem("count", count);
  ```
* The saved value is retrieved using:

  ```js
  localStorage.getItem("count");
  ```

---

## Project Structure

```
counter-app/
 └── index.html
```

---

## How to Run

1. Download or clone the project
2. Open `index.html` in a browser
3. Use the buttons to interact with the counter

---

## Learning Outcomes

* DOM manipulation
* Event handling in JavaScript
* Using browser storage (localStorage)
* Building responsive UI with CSS

---

## Future Improvements

* Add dark mode
* Add counter history
* Convert to React

---

## Author

Yazhini S
