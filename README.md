# FRC Team 11270 Website

This repository contains the public website for FRC Team 11270.

## Hosting

The site is hosted on Cloudflare Pages as a static website.

The source code is stored in GitHub. When changes are pushed to the `main`
branch, Cloudflare automatically deploys the updated site.

## Project Structure

This is a plain static website. There is no web framework, package manager,
build command, or server-side code.

- `index.html` contains the main website content and page layout.
- `img/` contains images, icons, logos, and other visual assets.
- `pdf/` contains downloadable PDF files.
- `robots.txt` and `sitemap.xml` support search engine indexing.

## Updating the Website

1. Clone this repository to your local computer.
2. Edit `index.html` and any related assets in `img/` or `pdf/`.
3. Preview the site locally before publishing.

On Windows, open PowerShell or Command Prompt and run:

```powershell
cd frc_team_11270
python -m http.server
```

Then open `http://localhost:8000` in your browser.

To preview from a phone on the same Wi-Fi network, open:

```text
http://<your-computer-ip-address>:8000
```

## Publishing Changes

After checking the site locally:

1. Commit your changes.
2. Push the commit to the GitHub repository.
3. Wait for Cloudflare Pages to finish deploying from the `main` branch.
4. Open the live website and confirm the update appears correctly.

## Maintenance Notes

- Keep file names simple and avoid spaces in asset names.
- Compress large images before adding them to the repository.
- Update `sitemap.xml` if new public pages are added.
- Test the site on both desktop and mobile screen sizes before publishing.
