# Greenwich DevOps Society Website

Starter site for the Greenwich DevOps Society organization page on GitHub Pages.

## What Is Included

- `index.html` - Homepage content and layout.
- `styles.css` - Site styling, color theme, and responsive behavior.

## Local Preview

You can open `index.html` directly in a browser, or run a local static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish On GitHub Pages

For an organization website, the repository should be named:

`<org-name>.github.io`

If this repo already has that name, publishing is straightforward:

1. Push the files to the default branch (`main`).
2. Open repository **Settings** > **Pages**.
3. Under **Build and deployment**, choose:
	- **Source**: `Deploy from a branch`
	- **Branch**: `main` and `/ (root)`
4. Save and wait for the first deployment.

Your site URL will be:

`https://<org-name>.github.io`

## Customize Quickly

- Update organization name and text in `index.html`.
- Change brand colors in the `:root` variables in `styles.css`.
- Replace the contact email (`hello@example.com`) in `index.html`.