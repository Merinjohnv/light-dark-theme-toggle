# Light / Dark Mode Toggle

A simple and modern Light/Dark mode theme toggle built using **HTML, CSS, and JavaScript**.  
With a single click, users can switch between light and dark themes, and their preference is saved using **LocalStorage** so it persists even after refreshing the page.

---

## Features

- One-click theme toggle (Light ↔ Dark)
- Smooth color transitions
- Theme icon change
- Persistent theme using LocalStorage
- Clean, minimal, and responsive UI
- Uses CSS variables for global theme management

---

## Technologies Used

- HTML5
- CSS3 (CSS Variables)
- JavaScript (DOM manipulation & LocalStorage)

---

## How It Works

- CSS variables define all theme colors.
- A `data-theme` attribute (`light` or `dark`) is applied to the `<html>` element.
- JavaScript toggles the theme on button click.
- The selected theme is stored in **LocalStorage**.
- On page load, the saved theme is applied automatically.

---

## Live Demo

👉 https://merinjohnv.github.io/light-dark-theme-toggle/
