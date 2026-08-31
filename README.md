# jonathanteubner.com

Static site, no build step. Files:
- `index.html` — homepage
- `writing.html` — writing page
- `assets/style.css` — shared stylesheet
- `assets/img/` — headshot + panel photo

Deployed via Netlify, auto-deploying on every push to `main`.

## Contact form
The contact form on the homepage uses Netlify Forms (`data-netlify="true"`).
Submissions email jonathan.teubner@gmail.com — configured in
Netlify: Site settings → Forms → Form notifications.
