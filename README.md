# Calculator

A functional browser-based calculator with a customisable interface, built using HTML, CSS, and JavaScript. Users can change the display colour, set a custom background colour, and toggle a surprise dog background mode.

---

## About

This project is a fully working calculator that handles basic arithmetic operations. Beyond the core functionality, it features a settings panel that lets users personalise the look of the app. All preferences are passed through URL parameters, so the chosen settings persist when the page is refreshed.

---

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division
- Customisable display colour (green, red, blue, yellow, purple, or default)
- Custom background colour via a colour picker
- "Dog!" toggle mode — replaces the background with a silly dog image
- All settings are stored and applied using URL query parameters
- Error handling — displays "Error" if an invalid expression is entered
- Dark themed UI with purple operator buttons and hover/active states

---

## Built With

- **Languages:** HTML, CSS, JavaScript
- **Concepts used:** DOM manipulation, `URLSearchParams` for reading URL query parameters, CSS Grid for button layout, form submission for settings, `eval()` with try/catch for expression evaluation, dynamic inline style changes

---

## How to Run

Visit the live version hosted on GitHub Pages.

---

## How to Use

1. Open the calculator in your browser
2. Click number and operator buttons to build an expression
3. Press `=` to calculate the result
4. Press `C` to clear the display
5. Use the settings panel in the top left to:
   - Change the display background colour
   - Pick a custom page background colour
   - Toggle dog mode on or off

---

## What I Learned

- Using `URLSearchParams` to read and apply query parameters from the URL, allowing settings to persist across page loads without a backend
- Manipulating DOM element styles dynamically with JavaScript based on user input
- Laying out a button grid cleanly using CSS Grid with `repeat(4, 1fr)`
- Styling interactive states with CSS `:hover` and `:active` pseudo-classes
- Handling runtime errors gracefully with `try/catch` around `eval()`
- Building a settings panel that submits via GET form to update the URL

---

