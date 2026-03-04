# AD311 – Simple Node.js Web Server

This project implements a basic HTTP server using Node.js without any external frameworks. It serves two HTML pages (`home.html` and `about.html`) and returns a custom 404 message for all other routes. This assignment demonstrates understanding of core Node.js modules (`http` and `fs`), routing, file serving, and basic server behavior.

---

## Features

- Serves **home.html** at `/`
- Serves **about.html** at `/about`
- Returns a **404 response** for all unknown routes
- Uses only built‑in Node.js modules (`http`, `fs`)
- Runs on **port 3000**

---

## Project Structure

```
ad311-node-web-server/
│
├── server.js
├── home.html
├── about.html
└── README.md
```

---

## How to Run the Server

### 1. Install Node.js  
Make sure Node.js is installed on your system (v18+ recommended).

### 2. Start the server  
Run the following command in the project directory:

```
node server.js
```

You should see:

```
Server running on port 3000
```

### 3. Open the pages in your browser

- Home page:  
  `http://localhost:3000/`

- About page:  
  `http://localhost:3000/about`

- Any other route (example):  
  `http://localhost:3000/xyz` → returns **Page not found**

---

## Routes

| Route | Description |
|-------|-------------|
| `/` | Loads **home.html** |
| `/about` | Loads **about.html** |
| Any other path | Returns a 404 message |

---

## 404 Behavior

Any route not explicitly handled by the server returns:

```
Page not found
```

This satisfies the assignment requirement for custom 404 handling.

---

## Demonstration Video Requirements

Your submission must include a short video demonstrating:

- The server running in the terminal  
- Loading the home page  
- Loading the about page  
- Triggering the 404 page  
- Explaining how the server works  

(As stated in the assignment instructions on Canvas.)

---

## Author

David Davis  
North Seattle College – AD311  
