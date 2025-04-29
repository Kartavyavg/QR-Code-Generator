# 📷 QR Code Generator

Welcome to the **QR Code Generator** — a simple, browser-based web application that lets you instantly convert any text or URL into a QR code! Built entirely using **HTML**, **CSS**, and **JavaScript**, this project demonstrates how to leverage a third-party API to create dynamic QR codes with a clean and user-friendly interface.

![QR Code Generator Screenshot](preview.png) <!-- Optional: Add a screenshot of your UI -->

---

## 🌐 Live Demo

> Coming soon or host on GitHub Pages / Netlify for instant preview!

---

## 🧠 Motivation

QR codes are now everywhere — from contactless payments to login authentication, they're used to encode URLs, text, and more in a scannable format. This project was built to:

- Understand DOM manipulation with JavaScript
- Practice using third-party APIs
- Create responsive, mobile-first web apps
- Share a real, useful tool with others online

---

## 🚀 How It Works

1. **User Input**: The user enters text or a URL into an input field.
2. **API Request**: On clicking "Generate", a request is made to [goqr.me’s API](https://goqr.me/api/doc/create-qr-code/) to create a QR code.
3. **Display**: The QR code image is displayed dynamically below the input.
4. **UX Logic**: If the same input is submitted again, it’s ignored. If the input is cleared, the QR image disappears.

---

## 🛠️ Built With

| Tech           | Usage                        |
|----------------|------------------------------|
| HTML5          | Page structure               |
| CSS3           | Styling & responsiveness     |
| JavaScript     | Interactivity & logic        |
| QRServer API   | QR code image generation     |
| Google Fonts   | ‘Poppins’ font styling       |

---

## 🎮 How to Use

1. Clone or download this repository:

   ```bash
   git clone https://github.com/Kartavyavg/QR-Code-Generator.git
   cd QR-Code-Generator
