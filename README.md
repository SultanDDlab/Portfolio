# Monolith Audio Portfolio

A minimal static portfolio prepared for GitHub Pages.

## Files

- `index.html`: homepage content and project links
- `styles.css`: visual design and responsive layout
- `script.js`: automatic copyright year

## Edit the site

### Contact information

In `index.html`, replace:

```html
your@email.com
```

with your real email address.

### Project links

Each project currently uses:

```html
<a class="project" href="#">
```

Replace `#` with the path or URL for the project.

Example:

```html
<a class="project" href="projects/project-one.html">
```

### Social links

Replace the `#` values in the footer with your profile URLs.

### Text and project titles

Edit the visible text directly inside `index.html`.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder.
3. Open the repository settings.
4. Select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the root folder.
7. Save.

GitHub will provide the public website address after deployment.

## Local preview

Open `index.html` in a browser.

For a more reliable local preview, run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
