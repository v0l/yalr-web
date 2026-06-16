# yalr-web

Project website for [YALR — Yet Another LLM Router](https://github.com/v0l/yalr).

A single-file, dependency-free landing page (`index.html`) with an animated
canvas routing visualization, built with the "Oxide Signal" aesthetic.

## Develop

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Deploy

Deployed to Cloudflare Pages via Wrangler:

```bash
wrangler pages deploy . --project-name yalr-web
```
