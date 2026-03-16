# AURA - Soluciones de IA para Clínicas de Estética

Landing page for **Aura IA** by Laion Solutions — an AI platform designed to optimize management and growth for aesthetic clinics by automating lead capture, customer service, and appointment scheduling.

## Tech Stack

- **HTML/CSS/JS** — Static single-page site
- **Nginx** — Web server with gzip and static asset caching
- **Docker** — Containerized deployment via `nginx:alpine`

## Project Structure

```
├── index.html      # Main landing page
├── assets/
│   ├── css/        # Stylesheets
│   ├── js/         # JavaScript modules
│   └── images/     # Images and icons
├── Dockerfile      # Container build config
└── nginx.conf      # Nginx server configuration
```

## Running Locally

### With Docker

```bash
docker build -t aura .
docker run -p 80:80 aura
```

Then open `http://localhost` in your browser.

### Without Docker

Serve `index.html` with any static file server, e.g.:

```bash
npx serve .
```
