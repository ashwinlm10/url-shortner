# URL Shortener

A simple URL Shortener application built with **Node.js**, **Express**, **MongoDB**, and **EJS**. Users can register, log in, generate short URLs, and track clicks.

---

## Features

- User authentication (Signup / Login)
- Generate unique short URLs
- Redirect to original URLs via short URLs
- Track number of clicks per URL
- View all URLs created by users
- Analytics page showing URL visit history

---

## Tech Stack

- **Backend:** Node.js, Express
- **Database:** MongoDB, Mongoose
- **Frontend:** EJS templating
- **Authentication:** Cookie-based sessions
- **Unique ID Generation:** `uuid` and `shortid`

---

Project Structure
short-url/
├─ controllers/      # Route controllers for URL and User
├─ middleware/       # Authentication middleware
├─ models/           # Mongoose models
├─ routes/           # Express routes
├─ service/          # Session management and helpers
├─ views/            # EJS templates
├─ index.js  

---

Dependencies

.express

.mongoose

.cookie-parser

.ejs

.uuid

----

About This Project

The URL Shortener project is a web application that allows users to convert long URLs into short, easy-to-share links. It provides user authentication so only registered users can create short URLs and track their usage. Each short URL records the number of clicks and stores a visit history, giving insights into how often the links are accessed.

Key functionalities include:

User Management: Signup and login with cookie-based sessions.

URL Shortening: Generate unique, short links for long URLs.

Redirection: Automatically redirect users from the short URL to the original URL.

Analytics: Track the number of clicks and detailed visit history for each short URL.

Dashboard: View all URLs created by the logged-in user and monitor their performance.

This project demonstrates a full-stack web application using Node.js, Express, MongoDB, and EJS.

.shortid

.nodemon (optional for development)

---

