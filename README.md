# lucas saunders

A minimal photography and media portfolio with a black-and-white interface and full-color gallery.

[View the live site](https://lucassaundrs.github.io/oaklinevisuals/)

## Project structure

- `index.html` — the complete site, including responsive CSS.
- `README.md` — setup and maintenance notes.
- `.gitignore` — excludes local operating-system files, editor backups, and environment files.

## Preview locally

Open `index.html` in a browser. No dependencies, package installation, or build step are required. Gallery images load from Unsplash and require an internet connection.

Alternatively, with Python 3 installed, run this command from the repository folder:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Edit the site

All content and styling live in `index.html`:

- Header: lowercase name and outlined contact link.
- `#portfolio`: gallery images and captions. Update image URLs, descriptive alt text, and captions together when replacing media. The current gallery uses externally hosted Unsplash images.
- `#about`: commercial, real estate, hospitality, and other services.
- `#contact`: the project invitation and `mailto:lucassaundrs@gmail.com` link.
- The `<style>` block controls layout, typography, and responsive breakpoints.

The email link opens the visitor's email application; there is no contact form or backend.

## Deployment

The site is hosted on GitHub Pages from this repository. Changes committed to `main` trigger the existing Pages deployment. Check the repository's Actions tab for deployment status, then refresh the live site after deployment completes.

## Before publishing changes

- Check the page on desktop and a narrow mobile screen.
- Confirm all gallery images load and text stays within the viewport.
- Check the header contact link and email address.
- Check keyboard focus and image alt text.
- Keep credentials and private files out of the repository.
