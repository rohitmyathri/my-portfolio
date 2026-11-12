# M Rohit — Portfolio

A responsive, single-page software engineer portfolio built with HTML, CSS and vanilla JavaScript. The original profile photograph from the supplied project ZIP is retained and displayed in a circular hero frame.

## Contents

- `index.html` — page structure and portfolio content
- `style.css` — theme, layout, responsive breakpoints and motion styles
- `script.js` — mobile navigation, active section state, reveal-on-scroll and footer year
- `rohith photo.jpeg` — profile photograph supplied in the original ZIP

## Run locally

No build step or package installation is required.

1. Extract the project ZIP.
2. Open the `mypofolio-master` folder.
3. Open `index.html` in a browser.

For a local development server (optional), run one of these commands from the project folder:

```bash
# Python 3
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish to GitHub

1. Create a new empty repository on GitHub.
2. Open a terminal in this project folder.
3. Run:

```bash
git init
git add .
git commit -m "Redesign personal portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the repository placeholder with your own GitHub repository URL. No GitHub profile URL is assumed or embedded in the portfolio.

## Deploy on Vercel

### Option A — Import from GitHub

1. Push the project to your GitHub repository.
2. Sign in to Vercel and choose **Add New → Project**.
3. Import the repository.
4. Keep the framework preset as **Other** (static site).
5. Leave the build command and output directory empty/default; the site is served from the repository root.
6. Deploy.

### Option B — Vercel CLI

Install and sign in to the Vercel CLI, then run from this project folder:

```bash
vercel
```

Follow the prompts. For a production deployment, run:

```bash
vercel --prod
```

## Content and links

- The email address is `23211a3230@bvrit.ac.in` and opens the visitor's email application using a `mailto:` link.
- Project, certificate, LinkedIn and GitHub destinations are not configured because verified URLs were not provided. They are labelled **Coming Soon** instead of linking to placeholder destinations.
- There is no contact form. The contact section uses a direct email link and does not claim to submit form data.
- The site uses Google Fonts when an internet connection is available; system sans-serif fallbacks are defined in CSS.

## Updating the portfolio

Edit the text in `index.html`. Keep `rohith photo.jpeg` in the same folder or update the image path in the hero image element. Update the project/certificate placeholders only when real destination URLs are available.
