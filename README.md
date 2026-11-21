# Weight Converter

A clean, responsive web application built with vanilla HTML, CSS, and JavaScript that converts weight from pounds (`lb`) to kilograms (`kg`) in real time with input validation and auto-reset timers.

## Preview

<img width="1917" height="842" alt="Screenshot 2026-11-21 201155" src="https://github.com/user-attachments/assets/054100b0-c1c0-42bf-988a-8023ce736ccd" />

## Features

* **Real-Time Pounds-to-Kilograms Conversion:** Dynamically calculates weight in kilograms (`value / 2.2`, rounded to 2 decimal places) as you type or adjust the number input.
* **Input Validation & Error Messaging:** Displays `"Please enter a valid number!"` in red if the entered value is less than or equal to `0` or not a valid number, and clears the error and input after 2 seconds.
* **Auto-Clear Result Timer:** Automatically resets the input field and converted result after 10 seconds using `setTimeout` and `clearTimeout`[cite: 11].
* **Glassmorphic Card UI:** Styled with Flexbox, a `yellow` to `lightblue` linear gradient background, translucent card styling, and monospaced typography[cite: 11].

---

## Project Structure

```text
├── index.html      # Weight converter form, result display, and error message elements
├── style.css       # Gradient background, glassmorphic card, and input styling
├── index.js        # Conversion math, validation logic, timers, and input listener
└── preview.png     # Application screenshot for the README
