# Good Vibes 8-Ball

A single-file magic 8-ball web toy. Pure HTML/CSS/JS — no build step, no dependencies
(fonts load from Google Fonts over the network).

## Files

- `index.html` — the entire app

## Hosting

Serve the directory with any static web server — `index.html` is the entry point.

nginx example:

```nginx
server {
    listen 80;
    server_name _;
    root /var/www/good-vibes-8-ball;
    index index.html;
}
```

Or for a quick test:

```bash
python3 -m http.server 8080
```
