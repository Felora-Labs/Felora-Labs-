# Felora Labs Website

Modern dark-themed multi-page website for **Felora Labs**.

## Pages
- `index.html` – Home, About, Services, Founder, Contact form
- `members.html` – Team page featuring Shikhar Yadav (Founder) + open positions

## Assets
- `logo.png` – Felora Labs logo
- `shikhar.jpg` – Founder photo

## How to run locally
Just open `index.html` in a browser, or use a simple server:

```bash
npx serve .
# or
python -m http.server 8000
```

## Deploy to Netlify (recommended)
1. Create a new site on [Netlify](https://netlify.com)
2. Drag & drop this folder, **or** connect a GitHub repo
3. The contact form already has `data-netlify="true"` – Netlify will automatically handle submissions
4. (Optional) Set a custom domain

## Customization tips
- Edit the short bio text in both pages if you want a different introduction
- Add more team members by copying the member card structure in `members.html`
- Change colors in the Tailwind config inside the `<script>` tags
- Form works out-of-the-box on Netlify. For other hosts, point the form `action` to Formspree or your backend

## Tech
- Pure HTML + Tailwind CSS (CDN)
- No build step required
- Fully responsive
