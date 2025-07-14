<h1 align="center"> MERN Stack Note Taking App </h1>

A collaborative note-taking and idea management application built with the MERN stack (MongoDB, Express, React, Node.js).

## Features

- Create, read, update, and delete notes
- RESTful API with Express and MongoDB
- Rate limiting with Upstash Redis
- Completely Responsive UI

---

## 🧪 .env Setup

### Backend (`/backend`)

```
MONGO_URI=<your_mongo_uri>

UPSTASH_REDIS_REST_URL=<your_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_rest_token>

NODE_ENV=development
```

## 🔧 Run the Backend

```
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```
cd frontend
npm install
npm run dev
```
