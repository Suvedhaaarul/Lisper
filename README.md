# Lisper

# 🔐 Secrets API Project (Node.js Version)

A backend Node.js application that fetches **random secrets** from the [App Brewery Secrets API](https://secrets-api.appbrewery.com/random) and displays them in the browser.

This project was built to practice:
- **API consumption on the server side**
- **Rendering data in the browser**
- Using `fetch`/`axios` in Node.js
- Simple **Express.js** server logic

## 🌐 External API Used

- **Endpoint:** `https://secrets-api.appbrewery.com/random`
- **Returns:** A random secret in JSON format
- **Authentication:** None required

## 🧰 Tech Stack

- Node.js
- Express.js (for routing)
- axios or node-fetch (to make API calls)
- EJS or simple HTML rendering (based on your implementation)

## 🚀 Features

- Runs on a local Express server
- Fetches and displays a **random secret** on each page refresh
- Clean and simple layout to display the result
- Backend makes the API call and sends data to the frontend

## 💻 How to Run Locally


Install dependencies:
npm install

Run the server:
node index.js

Open your browser and visit:
http://localhost:3000

📘 Learning Highlights
Making HTTP requests from a Node backend

Integrating third-party public APIs

Serving responses using Express

Optionally rendering views using EJS
