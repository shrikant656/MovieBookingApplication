# Movie Booking Application

A movie booking application similar to Book My Show, built with **Express**, **Node.js**, **React**, and **Ant Design**.

## Project structure

- **Client/book-my-show** — React frontend (Create React App)
- **Server/book-my-show** — Node.js/Express backend

## Tech stack

### Client (React)

| Category      | Technologies |
|---------------|--------------|
| UI            | React 19, Ant Design 5 |
| Routing       | React Router DOM 7 |
| HTTP          | Axios |
| Payments      | React Stripe Checkout |
| Utilities     | Moment.js |
| Testing       | Jest, React Testing Library |

### Server (Node.js)

| Category      | Technologies |
|---------------|--------------|
| Runtime       | Node.js |
| Framework     | Express 5 |
| Database      | MongoDB (Mongoose) |
| Auth          | bcrypt, jsonwebtoken |
| Security      | Helmet, CORS, express-rate-limit, express-mongo-sanitize |
| Other         | dotenv, Nodemailer, Stripe |

## Prerequisites

- Node.js (LTS recommended)
- MongoDB (local or Atlas)
- npm or yarn

## Getting started

### 1. Backend (Server)

```bash
cd Server/book-my-show
npm install
npm start
```

Runs the API with **nodemon** (default entry: `server.js`). Ensure MongoDB is running and `.env` is configured if used.

### 2. Frontend (Client)

```bash
cd Client/book-my-show
npm install
npm start
```

Runs the React app in development mode (default: [http://localhost:3000](http://localhost:3000)).

### Build for production (Client)

```bash
cd Client/book-my-show
npm run build
```

### Run tests

- **Client:** `npm test` (from `Client/book-my-show`)
- **Server:** `npm test` (from `Server/book-my-show`; add tests as needed)
