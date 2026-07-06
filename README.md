# Marcin Priachin Consulting Website

A static one-page personal consulting website for short-term Unity, XR, AR/VR, prototype, architecture, and project rescue work.

## Run locally

No build step is required. Open `index.html` directly in a browser.

Optional local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy on GitHub Pages

1. Commit and push `index.html`, `styles.css`, `script.js`, and `README.md` to the repository.
2. In GitHub, open the repository settings.
3. Go to **Pages**.
4. Set the source to the main branch and root folder.
5. Save the settings and wait for GitHub Pages to publish the site.

For a user site repository named `marcinpriachin.github.io`, GitHub Pages will usually publish at:

```text
https://marcinpriachin.github.io
```

## Edit text and links

- Main page copy: edit `index.html`.
- Contact links: update the placeholders in the Contact section of `index.html`.
- Visual styling: edit `styles.css`.
- Small browser behavior: edit `script.js`.

Current placeholder links:

- `mailto:your.email@example.com`
- `https://www.linkedin.com/in/your-profile`
- `https://github.com/your-profile`
