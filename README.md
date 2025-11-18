# Space Atlas

Small Express + MongoDB API for storing and querying celestial bodies.

Getting started

- Prerequisites: `node` (v14+), `npm`, and a MongoDB URI.
- Install dependencies:

```powershell
npm install
```

- Create a `.env` file with at least:

```
PORT=3000
MONGODB_URI=<your_mongo_uri>
JWT_SECRET=<your_jwt_secret>
```

- Run the server in development:

```powershell
npm run dev
```

Project structure

- `server.js` — app entrypoint
- `routes/` — API routes
- `controllers/` — request handlers
- `models/` — Mongoose models
- `config/db.js` — MongoDB connection

Notes

- Do NOT commit sensitive secrets. Use GitHub Secrets for CI or a `.env` local file.
- I added a `.gitignore` that excludes `node_modules` and `.env`.

License

MIT
