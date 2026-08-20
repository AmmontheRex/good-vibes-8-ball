# Good Vibes 8-Ball

A single-file magic 8-ball web toy. Pure HTML/CSS/JS — no build step, no dependencies
(fonts load from Google Fonts over the network).

## Files

- `good-vibes-8-ball.html` — the entire app

## Hosting

Serve the directory with any static web server. Point the site root at
`good-vibes-8-ball.html` (or copy/symlink it to `index.html`).

nginx example:

```nginx
server {
    listen 80;
    server_name _;
    root /var/www/good-vibes-8-ball;
    index good-vibes-8-ball.html;
}
```

Or for a quick test:

```bash
python3 -m http.server 8080
```
