# Birthday Website 🎂

A small static site (no build step) for a birthday surprise.

## 1. Personalize it

Open `script.js` and edit the `CONFIG` block at the top:

- `name`, `fromName`
- `birthdayMonth` / `birthdayDay` (drives the countdown; confetti fires automatically on the day)
- `intro`, `reasons`, `moments`, `finalNote`

To add photos, create an `images/` folder, drop pictures in, and set `photo: "images/your-photo.jpg"` on a moment.

## 2. Preview locally

Just double-click `index.html`, or run `python3 -m http.server` in this folder and open http://localhost:8000.

## 3. Put it on GitHub

```bash
git init
git add .
git commit -m "Birthday site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## 4. Publish with GitHub Pages

On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.**

After a minute your site will be live at `https://<your-username>.github.io/<repo-name>/`.

Tip: the link is public to anyone who has it, so avoid putting private details (full names, address, etc.) in the text.
