# Alekhya Viswanath, portfolio

My career drawn as a transit map: an engineering line, a field projects line, an operations line and a strategy line, with the transfers between them marked.

Live site: https://YOUR-GITHUB-USERNAME.github.io

## Files

- `index.html` is the whole site (styles and scripts are inside it)
- `resume.pdf` is the file behind the "Download resume" button

## Publish on GitHub Pages

1. On GitHub, create a new public repository named exactly `YOUR-GITHUB-USERNAME.github.io`.
2. Click **Add file > Upload files**, drag in `index.html`, `resume.pdf` and this `README.md`, then click **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then **Save**.
4. Wait a minute or two and open `https://YOUR-GITHUB-USERNAME.github.io`.

## Updating it

- Edit text directly in `index.html` on GitHub (pencil icon) and commit. The site refreshes within a minute or two.
- To add a station to the map, add an entry to the `stations` list in the script near the bottom, and a matching `<li class="stop" id="...">` in the route section with the same `id`.
- To swap the resume, upload a new file named `resume.pdf`.
