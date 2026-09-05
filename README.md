# The Mansio Society for Gospel Living

Static site: Home, Vision, and Intellectual Lineage.

## Files

- `index.html` — home
- `vision.html` — Inhabit vision paper
- `intellectual-lineage.html` — sources and formation
- `styles.css` — shared look and feel

## Put it on GitHub Pages

1. Create a new GitHub repository (public, if you want a free `username.github.io` or project site).
2. Upload these files to the **root** of the repo (not inside a subfolder).
3. On GitHub: **Settings → Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**.
5. Branch: `main` (or `master`), folder: `/ (root)`. Save.

GitHub will give you a URL like `https://yourname.github.io/repo-name/`.

## Custom domain (mansiosociety.org / .com)

1. In the same Pages settings, add `mansiosociety.org` (and www if you want it).
2. At your domain registrar, point the domain at GitHub Pages (GitHub shows the DNS records to use).
3. Optional: add a file named `CNAME` in the repo whose only line is `mansiosociety.org`.

## Edit by hand

Open any `.html` file in a text editor. Keep `styles.css` in the same folder. After you commit and push, Pages rebuilds in a minute or two.

This folder is plain HTML/CSS/JS. No build step, Node, or Netlify config is required.
