# Lamhe — Frontend (GitHub Pages)

Static site for the Lamhe farewell party landing page and registration form.
This site talks to the Flask backend hosted on Render.

## Files
- `index.html` — Landing page
- `register.html` — Multi-step registration form (vanilla JS)
- `config.js` — **Edit this** to point to your Render backend URL
- `static/images/` — Poster, favicon, UPI QR
- `.nojekyll` — Tells GitHub Pages not to run Jekyll

## Configure the backend URL
Open `config.js` and replace the placeholder with your Render URL:
```js
window.LAMHE_CONFIG = {
  BACKEND_BASE_URL: "https://lamhe-backend.onrender.com",
  ...
};
```
