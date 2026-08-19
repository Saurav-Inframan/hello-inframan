# hello-inframan

Minimal Node.js HTTP server for testing deploys on Inframan.

- `GET /` — returns a plain text greeting
- `GET /health` — returns `{"status":"ok"}`

## Run locally

```
npm start
```

## Docker

```
docker build -t hello-inframan .
docker run -p 3000:3000 hello-inframan
```
