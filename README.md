# Footballers App

Footballers App is a web application that allows users to create and manage custom football teams and players.

Users can create their own teams, add players to each team, edit or remove players and browse their teams through a simple web interface.

The application also includes account functionality, search features and a responsive layout that works across different screen sizes.

---

## Features

- Create and manage football teams
- Add players to individual teams
- Edit and delete players
- Delete teams
- User signup, login and logout
- Search and filter teams
- View team and player information
- Responsive interface for desktop and mobile
- Persistent application data

---

## Tech Stack

- JavaScript
- Node.js
- Express.js
- Handlebars
- LowDB
- HTML
- CSS

---

## How It Works

The application uses Express.js to handle routing and application logic.

Data is stored using LowDB and the project is organised into separate controllers, models and views.

Handlebars is used to generate the web pages dynamically while the frontend uses HTML, CSS and JavaScript.

---

## Project Structure

```text
app/
│
├── controllers/
├── models/
├── public/
├── utils/
├── views/
├── routes.js
├── server.js
├── package.json
└── README.md
